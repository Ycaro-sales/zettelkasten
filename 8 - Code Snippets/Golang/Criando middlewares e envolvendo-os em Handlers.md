2024-07-27 10:56
Tags: [[Backend Development]] 
Linguagem: [[Golang]]
Bibliotecas: [[Golang Standard Library]]

# Criando middlewares e envolvendo-os em Handlers

## Declaração

```go
func adminOnly(h http.handle) http.Handler {
	return http.HandlerFunc(func(w http.ResponseWriter, r *httpRequest){
		if !currentUser(r).IsAdmin {
			http.NotFound(w, r)	
			return
		}
		h(w, r)
	})
}
```

Se você estiver tendo problemas onde o middleware necessita de muitas dependências você poder returnar o middleware da seguinte maneira

```go
func newMiddleware(
	logger Logger,
	db *DB, 
	slackClient *slack.Client,
	rroll []byte,
) func(h http.Handler) http.Handler
```
## Utilização

### Sem retornar o middleware:
```go
func addRoutes(mux *http.ServeMux){
	mux.HandleFunc("/api/", handleAPI())
	mux.HandleFunc("/about", handleAbout())
	mux.HandleFunc("/admin", adminOnly(handleAdminIndex()))
}
```

### Retornando o middleware:
```go
middleware := newMiddleware(logger, db, slackClient, rroll)

mux.HandleFunc("/route1", middleware(handleSomething()))
mux.HandleFunc("/route2", middleware(handleSomething2()))
mux.HandleFunc("/route3", middleware(handleSomething3()))
mux.HandleFunc("/route4", middleware(handleSomething4()))
```

# Referencias
[how i write http servieces in go after 13 years](https://grafana.com/blog/2024/02/09/how-i-write-http-services-in-go-after-13-years/#the-adapter-pattern-for-middleware)