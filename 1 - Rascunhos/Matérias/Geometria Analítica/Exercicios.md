Sejam $a<b$ respectivamente as coordenadas dos pontos $A$ e $B$ sobre o eixo E. Determine as coordenadas dos pontos $x_{1},\dots,x_{n-1}$ que dividem o segmento AB em n partes iguais.
$\text{resposta:}$
para dividir a reta em n partes iguais temos a formula:
$$
\begin{equation}
\frac{|a-b|}{n}
\end{equation}
$$
então podemos assumir que o valor de $X_{1}$ pode ser descrito como
$$
\begin{equation}
P(1) = a + \frac{b-a}{n}
\end{equation}
$$
logo se tentarmos generalizar teremos:
$$
\begin{align}
P(2) &= a+2(\frac{b-a}{n})\\
P(3) &= a+3(\frac{b-a}{n})\\
\dots\\
P(k) &= a+k(\frac{b-a}{n})
\end{align}
$$
então teremos o passo base e a hipótese:
$$
\begin{cases}
P(1) = a+\frac{b-a}{2}\\
P(k) = a + k\frac{(b-a)}{n}
\end{cases}
$$
Sabemos que P(k) representa a soma de todos os k - 1 valores anteriores de X, então podemos 