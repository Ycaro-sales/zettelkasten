---
id: 1723496300-RLUY
aliases:
  - apresentacao-lua
tags: []
---
# apresentacao-lua

## What 

- Lua é uma linguagem de scripting e extensão simples, poderosa, eficiente, leve e embutivel que pode ser usada tanto por si própria(Autonoma) quanto como uma linguagem de extensão
- Ela é uma linguagem multi-paradigma que permite trabalhar com programação procedural, programação orientada a objetos, programação orientada a dados e descrição de dados
- Combina uma sintaxe procedural simples com poderosos construtos de descrição de dados baseados em arrays associativos e uma semantica extensivel
- Ela é tipada dinamicamente, e roda interpretando bytecode com a maquina virtual a base de registradores, tendo gerenciamento de memória automático com coletor de lixo, fazendo com que seja ideal para configurações, scripting e prototipagem rapida 

- Ela é implementada como uma biblioteca escrita, em clean C, um subset de standard C e C++
- a Distribuição de Lua inclui um programa host chamado lua que usa a biblioteca lua para oferecer um interpretador de lua autonomo, para uso interativo ou usar em grupos de arquivos
- Lua tem a intenção de ser usada tanto como uma linguagem de scripting leve, poderosa e embutivel, quanto como uma linguagem autonoma leve, eficiente e poderosa
- Como Lua é originalmente uma linguagem de extensão, ela não tem nenhuma noção de um programa principal, ela funciona embutida em um cliente host(esse host é frequentemente um programa Lua autonomo), o host pode chamar funções para executar um pedaço de código Lua, ler variaveis do codigo lua e pode registrar funções em C que podem ser chamadas por código Lua, através dessas funções lua pode ser aumentada para lidar com um extenso espectro de dominios, criando linguagens customizadas que compartilham de um arcabouço sintatico
 
linguagem de extensão
- Clear and simple syntax (since it is not the main language for most of its users).
- Small size and small implementation (so the cost of adding it to the host will not be too high).
- Good data-description facilities (to make it useful as a configuration language).
- Adequate extensibility (to allow its use in high abstraction levels—for interfacing with users in diverse domains).

- Lua é pequena, toda implementação da linguagem possui menos de 6000 linhas de código ANSI C. Além das facilidades comuns a maiores das linguagens procedurais, Lua possui alguns recursos especiais que a tornam uma linguagem de alto nivel, poderosa e extensivel

	- Ability to define and manipulate functions as first-class values, which greatly simplifies the implementation of object-oriented facilities.
	- Associative arrays—powerful language constructs that implement most data containers.
	- Garbage collection, negating the need for explicit managing of memory allocations—a major source of programming errors.
	- A fallback mechanism, allowing extension of the semantics of the language.
	![[Pasted image 20240813124545.png]]
	- Reflexive facilities, allowing the creation of highly polymorphic parts.

## Who
- foi projetada, implementada e mantida por Roberto Lerusalmschy, Waldemar Celes e Luiz Henrque de Figueiredo pelo Grupo de Tecnologia de Computação Gráfica da PUC-RJ
![[Pasted image 20240813112143.png]]
## Where

- Exemplos de onde ela pode ser utilizada:
- Jogos(Factorio, Hades, Project Zomboid, World of Warcraft, ...)
![[Pasted image 20240813122500.png]]
- Extensao de programas(Neovim, Unity, React Lua e programas que utilizam da interface do C)
- Aplicações Industriais(Ginga)
- Web (Lapis)

## Why

#### Lua é Rápida
Lua has a deserved reputation for performance. To claim to be "as fast as Lua" is an aspiration of other scripting languages. Several benchmarks show Lua as the fastest language in the realm of interpreted scripting languages. Lua is fast not only in fine-tuned benchmark programs, but in real life too. Substantial fractions of large applications have been written in Lua.

Com o luaJIT ela se torna uma das linguagens de script mais rapidas
#### Lua é Portatil
 Lua is distributed in a small package and builds out-of-the-box in all platforms that have a standard C compiler. Lua runs on all flavors of Unix and Windows, on mobile devices (running Android, iOS, BREW, Symbian, Windows Phone), on embedded microprocessors (such as ARM and Rabbit, for applications like Lego MindStorms), on IBM mainframes, etc. 

#### Lua é Embutivel
Lua is a fast language engine with small footprint that you can embed easily into your application. Lua has a simple and well documented API that allows strong integration with code written in other languages. It is easy to extend Lua with libraries written in other languages. It is also easy to extend programs written in other languages with Lua. Lua has been used to extend programs written not only in C and C++, but also in Java, C#, Smalltalk, Fortran, Ada, Erlang, and even in other scripting languages, such as Perl and Ruby.
#### Lua é Poderosa (Apesar de ser simples)
A fundamental concept in the design of Lua is to provide _meta-mechanisms_ for implementing features, instead of providing a host of features directly in the language. For example, although Lua is not a pure object-oriented language, it does provide meta-mechanisms for implementing classes and inheritance. Lua's meta-mechanisms bring an economy of concepts and keep the language small, while allowing the semantics to be extended in unconventional ways.
#### Lua é pequena
Adding Lua to an application does not bloat it, thus also contributing to its security. The tarball for Lua 5.4.7, which contains source code and documentation, takes 365K compressed and 1.3M uncompressed. The source contains around 31000 lines of C. Under 64-bit Linux, the Lua interpreter built with all standard Lua libraries takes 279K and the Lua library takes 464K


## How

- Blocos são definidos por palavras chaves
- apenas palavras chaves 21
	![[Pasted image 20240813104126.png]]
- Tipos dinamicos
![[Pasted image 20240813105142.png]]
- estruturas de controle
 ![[Pasted image 20240813110249.png]]

##### Estrutura de dado padrao
- Tabelas
	![[Pasted image 20240813114331.png]]
	
	- Paradigma funcional
	![[Pasted image 20240813114850.png]]
	- Orientacao a objetos
	-![[Pasted image 20240813115424.png]]

#### Lua e C
![[Pasted image 20240813120152.png]]
![[Pasted image 20240813121645.png]]
## Bibliografia

https://scholar.google.com.br/scholar_url?url=https://devforum-uploads.s3.dualstack.us-east-2.amazonaws.com/uploads/original/4X/7/3/5/735ebc5723eb4017431f8cd69e1fa10d9d350d56.pdf&hl=pt-BR&sa=X&ei=hXe6ZvSCHO7A6rQP1tCx2QY&scisig=AFWwaebXyM02i564ZplsORvEqBMc&oi=scholarr
https://www.lua.org/about.html
https://www.lua.org/authors.html
https://www.youtube.com/watch?v=jUuqBZwwkQw
https://www.youtube.com/watch?v=I_rzFahRFeE
https://www.lua.org/ddj.html
https://www.youtube.com/watch?v=f5MpjDtnFP4&t=100s
https://www.lua.org/manual/5.4/manual.html#1
