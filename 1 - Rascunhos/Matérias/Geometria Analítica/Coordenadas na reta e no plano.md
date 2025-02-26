>Referência: Capitulos 1 e 2 do Elon Lages

$$ AB = D(a,b) = |a-b| $$

Dados os pontos A e B quaisquer, o comprimento do segmento de reta AB
$$
\text{Chama-se distância entre os pontos A e B } 
ou \bar{AB}
$$
Algumas convenções:
$$
d(A,A) = 0 
$$
$$
Se, A \neq B \to d(A,B) > 0
$$
$$
d(A,C) + d(C,B) = d(A,B) \leftrightarrow  C \in \bar{AB}
$$
$$
d(A,B) = d(B,A)
$$

### Reta Orientada:
- quando definimos um sentido de percurso chamado positivo; o inverso é o negativo
- Numa reta orientada na qual se fixou um ponto O, chamado a origem.
- À origem O do eixo E corresponde ao número zero 
- $d(0,X) = |x-0| = x \to$ comprimento do segmento de reta 0X
- Se x e y são respectivamente as coordenadas dos pontos $X, Y$ do eixo $E$ então $x < y \leftrightarrow$ X está a esquerda de Y
- $d(X,Y) = |x-y|$
- se $d(A,X) \leq d(A,B) \to$  podemos definir  $$
 \begin{equation}
t =\frac{d(A,X)}{d(A,B)}
\end{equation}
 $$
- $$\text{Se }X = B \to t = \frac{d(A,X)}{d(A,B)} = \frac{d(A,B)}{d(A,B)} = 1$$
Se para cada $t \in [0,1] \to$ Chamamos de $x_{t}$ o módulo do segmento de reta $\bar{AB}$ tal que $$
\begin{align}
t = \frac{d(A,X_{t})}{d(A,B)} = \frac{|a - x_{t}|}{|a - b|}
\end{align}
$$
## Coordenadas no plano

$$
\begin{align}
A \to \mathbb{R} \\ (x,y)\\ (u,v)
\end{align}
$$
### Definições
- dados $(x,y)$ e $(x',y')$ em $\mathbb{R}^{2}$ 
$$
\begin{equation}
(x,y) = (x',y')\leftrightarrow  
\begin{cases}
x & = x'\\ y & = y'
\end{cases} 
\end{equation}
$$
- A cada ponto P do plano $\pi$ fazemos corresponder um par ordenado $(x,y) \in \mathbb{R}$ ou seja, há uma correspondência biunívoca.
$$ \pi \to \mathbb{R}^{2} $$
- Plano é formado por eixos:
$$
\begin{align}
OX&-\text{eixo das abcissas}\\
OY&-\text{eixo das ordenadas}
\end{align}
$$
Obs1: Se $P$ estiver sobre o eixo $OX \to$ o par ordenado será $(x,0)$
Obs2: Se $P$ estiver sobre o eixo $OY \to$ o par ordenado será $(0,Y)$
Obs3: Se $P$ estiver sobre a origem, o par ordenado será $(0,0)$

### Bissetriz
![[Pasted image 20250210102836.png]]
- O primeiro e o terceiro quadrante formam 2 ângulos retos, opostos pelo vértice. Os pontos $P=(x,y)$ da bissetriz comum desses 2 ângulos são equidistantes dos lados, logo têm abcissa e ordenada iguais. Esta reta $\Delta$ chama-se a diagonal do plano $\pi$
- Analogamente, ponto $Q=(x,y)$ pertencente à bissetriz $\Delta'$ comum ao 2º e 4º Q $\leftrightarrow$ $$
\begin{cases} 
x = -y \\
y=-x
\end{cases}
$$
