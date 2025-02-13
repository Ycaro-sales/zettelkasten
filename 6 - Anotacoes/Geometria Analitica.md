## Coordenadas na reta e no plano: Cap 1 e 2 - Elon LAges

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
### Rotação
- Quando se toma no plano um sistema de coordenadas $OXY$, chama-se sentido $\underline{positivo}$ da rotação ($\underline{anti-horário}$) ao sentido de rotação de $90^º$ que leva o semieixo positivo de $OY$
![[Imagem do WhatsApp de 2025-02-10 à(s) 10.48.21_3230aa48.jpg]]
- Dado um ponto $P=(x,y)$ submetemos os segmento de reta $OP$ a rotação de $90º$ no sentido positivo em torno da origem, obtemos assim no segmento $OQ$. Quais as coordenadas do ponto $Q$?
- A rotação de $+90º$ leva o ponto $(x,0)$ no ponto $(0,x)$ logo transforma o retângulo que tem diagonal $OQ$ e dois lados sobre os eixos no retângulo $OQ$ 
$$\implies Q = (-y,x)$$
- $OQ' -$rotação de $-º90$(sentido horário) do segmento $OP$ e assim $\underline{Q'=(y,x)}$
- Ex.: O vértice do ângulo reto do triângulo retângulo isósceles $OAB$ é a origem. Sabendo que $A=(3,5)$. quais as coordenadas do vértice B?
	- Para descobrir o valor de B podemos rotacionar em $90º$ no sentido horário($Q=(-y,x)$) e anti-horário($Q'=(y,-x)$)

- Dados os pontos $A = (a,b)$ e $A'=(a',b')$. Quais são as coordenadas do ponto médio $M=(x,y)$ do segmento de reta $AA'$
- ![[Imagem do WhatsApp de 2025-02-12 à(s) 09.39.20_0ba2d68d.jpg]]
- Suponhamos que $a\neq a'$ e $b\neq b'$, ou seja, o segmento $AA'$ não é vertical $(\parallel{OY})$, nem horizontal($\parallel OX$)
- Considerando os pontos $P=(x,b)$ e $Q=(a',y)$, vemos que $APM$ e $MQA'$ são triângulos retângulos cujas hipotenusas têm o mesmo comprimento, uma que M é o ponto médio de $AA'$.
- os ângulos $\alpha$ e $\beta$ são congruentes pois os lados $AP$ e $MQ$ são paralelos. Logo, os triângulos $APM \equiv MQA'$ são congruentes.
- Resultando que os lados $AP$ e $MQ$ têm o mesmo comprimento.
- se $A_{0}=(a,0)$ e $A'_{0}=(a',0)$ e $M_{0}=(x,0)$
- se $M=(x,y)$
 $$
 \begin{equation}
\begin{cases}
x=\frac{a+a'}{2} \\
y=\frac{b+b'}{2}
\end{cases}
\end{equation}
$$
- Agora, de forma mais geral, veremos como determinar as coordenadas do ponto $X_{t}$que $\underline{divide}$ o segmento $AA'$
- Dados os pontos $A = (a,b)$, $A'=(a',b')$, $0\leq t\leq_{1}$ $$
\begin{align}
X_{t} &=(x_{t},y_{t})\\
x_{t}&=\ ?\\
y_{t}&=\ ?
\end{align}
$$$$t=\frac{d(A,x_{t})}{d(A,A')}$$
- considerando $a\neq a'$ e $b\neq b'$.
- Os triângulos $APX_{t}$ e $AQA'$ com pontos $P=(x_{t},b)$ e $Q=(a',b')$ são semelhantes(o ângulo agudo é comum) e a razão de semelhança é:
$$
\begin{equation}
\frac{d(A,X_{t})}{d(A,A')} = \frac{d(A,P)}{d(A,Q)} = t
\end{equation}
$$

$$
\begin{equation}
t=\frac{d(A,P)}{d(A,Q)} = \frac{|a-x_{t}|}{|a-a'|} = \frac{x_{t}-a}{a'-a}
\end{equation}
$$
$$
\begin{align}
x_{t} &= t(a'-a)+a\\
x_{t} &= ta'-ta+a=ta'+a(1-t)\\
x_{t} &= ta'+a(1-t) \\
\text{de forma análoga: } \\
y_{t} &= tb'+b(1-t)
\end{align}
$$
$$se\ t=\frac{1}{2} \to x_{t}=\frac{1}{2}a'+\frac{1}{2}a=\frac{a'+a}{2}$$
- Ex.: Dados os pontos $A=(a,2)$ e $A'=(3,5)$ e $B=(2,4)$ e $B'=(3,2)$
![[Imagem do WhatsApp de 2025-02-12 à(s) 10.36.41_b01ebe56.jpg]]
- Ás coordenadas de um ponto $X_{s}$ que divide o segmento $AA'$:
$$
\begin{align}
X_{s}&=(x_{s},y_{s})\text{(S é um parâmetro do segmento AA')} \\
X_{s}&=S*3 + 1(1-S) \\
\to X_{s}&=3S+1-S = \underline{2S+1}\\ \\
Y_{s}&=S*5+2(1-S)\\
\to Y_{s}&=5S+2-2S=\underline{3S+2}\\
\end{align}
$$
- Segmento $BB'$
$$
\begin{align}
X_{t} &= (x_{t},y_{t}) \text{(t é o parâmetro do segmento BB')}\\ \\
x_{t} &= t*3+2(1-t))\\
y_{t} &= t*2 + 4(1-t)\\ \\
\to x_{t}&=3t+2-2t=t+2 \\
\to y_{t}&=2t+4-4t=-2t+4\\ \\
\text{No ponto de interseção:}\\ \\
	\begin{cases}
	X_{s} &= x_{t} \\
	y_{s} &=y_{t}
	\end{cases}
\end{align}
$$
- Se $x_{s}=X_{t}\implies 2s+1=t+2\implies 2s-t=1$
- Se $Y_{s}=Y_{t}\implies 3s+2=-2t+4\implies 3s+2t=2$
$$
\begin{cases}
2s-t=1\\
3s+2t=2
\end{cases}
$$
- 