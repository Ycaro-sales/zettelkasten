tags: [[R]]
```R
medponderada <- function (x,w)
{sum(x*w)/sum(w)}


lista <-c(1,2,3,4) #Cria uma lista de valores com os argumentos - retorna a lista
cumsum(lista) #soma cumulativa dentro de uma lista de valores, retorna o valor da soma
cumprod(lista) #Produto Cumulativo dentro de uma lista, retorna o valor do produto
median(lista) #Calcula a mediana de uma lista e retorna o valor
mean(lista) #Calcula a média de uma lista
```