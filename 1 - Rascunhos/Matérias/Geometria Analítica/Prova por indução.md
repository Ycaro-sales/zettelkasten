## Teorema
- Principio do menor número inteiro
	- Se $L$ é um subconjunto de $\mathbb{Z}$, não vazio e limitado inferiormente, então $L$ possui mínimo
	- $\{\dots,-3,-2,-1,0\}$
#### $\underline{Indução:}$  Seja $P(n)$ uma função proposicional cujo universo é o conjunto dos inteiros positivos maiores que ou iguais a um dado inteiro $\underline{a}$ . Suponhamos que se consiga provar o seguinte:
	
- $P(A)$  é verdadeiro 
- se $r\geq a$ e $P(r)$ é verdadeiro $\to$ $P(r+1)$ também é verdadeiro $\to$ $P(r)$ é verdadeiro para todo $n\geq a$
- Ex.: Provar por indução que:
 $$
\begin{equation}
1+2+3+\dots+n = \frac{n(n+1)}{2};(n\geq_{1})
\end{equation}
$$ $$\begin{equation}
\text{Função proposicional }P(n)=\frac{n(n+1)}{2};a=1
\end{equation}$$
- $P(1)$ é verdadeiro
$$
1 = \frac{1(1+1)}{2}\implies 1=1
$$
#### $\underline{Hipótese:}$ se $\underline{r\geq 1}$ e $P(r)$ é verdadeiro
$$
1 + 2 + 3 + \dots + r = \frac{r(r+1)}{2}
$$
- Então, precisamos provar que é verdadeiro para $n=r+1$(Tese). 
$$ \text{1º Membro: }1+2+3+...+r+(r+1)= $$
$$ \text{2º Membro: } \frac{(r+1)(r+1+1)}{2}=\frac{(r+1)(r+2)}{2}$$
- Por hipótese
$$
\begin{align}
1+2+3+\dots+r+(r+1) = \frac{r(r+1)}{2} + (r+1) &= \frac{r(r+1)+2(r+1)}{2}\\
\underline{\text{1º membro: }} &= \frac{(r+1)(r+2)}{2}
\end{align}
$$
- Como o  $1º$ membro é igual ao segundo membro da função, conseguimos provar a nossa tese, ou seja, que é verdadeira para $n=r+1$. Dessa forma, provamos que a igualdade efetivamente vale para todo inteiro $n\geq_{1}$. a aula sobre $asdfas$
## Exemplo
Provar por indução que:
$$
\begin{equation}
a)\  1^{2}+2^{2}+3^{2}+\dots+n^{2}=\frac{n(n+1)(2n+1)}{6}; (\forall n\geq 1)
\end{equation}
$$
1º:$\underline{\text{Para n=1:}}$
$$
\begin{align}
P(1) = 1^{2} = \frac{1(1+1)(2*1+1)}{6}=\frac{2*3}{6} = 1
\end{align}
$$
Por hipótese, a igualdade é verdadeira para qualquer $n\geq r$, ou seja,
$$
\begin{align}
P(k) = 1^{2}+2^{2}+3^{2}+\dots+k^{2}&=\frac{k(k+1)(2k+1)}{6} \\
&=\frac{(k^{2}+k)(2k+1)}{6} \\
&=\frac{2k^{3}+3k^{2}+k}{6}
\end{align}
$$
Devemos demonstrar que a igualdade é verdadeira para $n=r+1$.(Tese)
Dessa forma, o 1º membro da igualdade é:
$$
\begin{align}
P(k+1)&=1^{2}+2^{2}+3^{2}+\dots+k^{2}+(k+1)^{2}\\
&=\frac{k(k+1)(2k+1)}{6}+(r+1)^{2} \\
&=\frac{k(k+1)(2k+1)+6(r+1)^{2}}{6} \\
&=\frac{(k+1)[k(2k+1)+6(K+1)]}{6}\\
&=\frac{(k+1)(2k^{2}+k+6k+6)}{6} \\
&=\frac{(k+1)(2k^{2}+7k+6)}{6}; (\text{1º membro})
\end{align}
$$
$\underline{\text{Conclusão:}}$ Como o 1º membro da igualdade é igual ao 2º membro, concluímos que a função proposicional também é verdadeira para $n=k+1$. Isso prova que a igualdade efetivamente vale para todo inteiro $n\geq 1$


$$
b)\ 1+3+5+\dots+(2n-1) = n^{2}
$$
$$
\begin{align}
 P(1) = 2*1-1 = 1^{2} \\ 2 - 1 = 1 \\ 1 = 1
\end{align}
$$
$$
\begin{equation}
\begin{split}
P(k) & =1+3+5+\dots+(2k-1) & = k^{2}\\
P(k+1)  & = 1+3+5+\dots+(2k - 1) + [2(k+1) - 1] & = (k+1)^{2} \\
P(k+1) & = [1+3+5+\dots+(2k-1)] + (2k + 1)  & = k^{2}+ 2k+1 \\
P(k+1) & = k^{2} + (2k + 1)  & = k^{2}+ 2k+1 
\end{split}
\end{equation}
$$

#### Questão 1(Elon Lages)
Sejam $a<b$ respectivamente as coordenadas dos pontos $A$ e $B$ sobre o eixo $E$.
Determine as coordenadas dos pontos $X_{1},\dots,X_{n-1}$ que dividem o segmento $AB$ em n partes iguais.
$$
\begin{align}
X_{1} = a+1*\frac{(b-a)}{n}\\
X_{2} = a+2*\frac{(b-a)}{n}\\
X_{k} = a+k*\frac{(b-a)}{n}\\
X_{n-1} = a+(n-1)*\frac{b-a}{n}\\
X_{i}= a+i\frac{(b-a)}{n}\leftrightarrow \{\forall i \in \mathbb{N} | 1\leq i\leq n-1\}
\end{align}
$$