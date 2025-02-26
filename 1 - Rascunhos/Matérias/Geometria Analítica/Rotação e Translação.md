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

## Rotação e Translação
![[Imagem do WhatsApp de 2025-02-17 à(s) 09.46.35_c30b8cff.jpg]]
### $\to$ Translação
- São dados o segmento de reta orientado $AA'$ com $A=(a,b)$ e $A'=(a',b')$ e o ponto $C=(c,a)$ fora da reta $AA'$. 
- Queremos encontrar as coordenadas do ponto $C'$ de modo que o segmento $CC'$ seja o segmento orientado obtido quando se $\underline{translada}$ o segmento $AA'$ paralelamente até fazer $A$ coincidir com $C$. Assim, os segmentos $AA'$ e $CC'$ são os lados opostos de um $\underline{paralelogramo}$ cujos lados opostos são $AC$ e $A'C'$
- ![[Imagem do WhatsApp de 2025-02-17 à(s) 09.59.19_cd60fc0c.jpg]]
- Sabemos que as diagonais de um paralelogramo cortam-se mutuamente ao meio. Assim $AC'$ e $A'C$ tem o mesmo ponto médio:
$$
\begin{align}
C' &= (x,y) = ? \\ \\
\frac{a+x}{2} &= \frac{a'+c}{2} \\
\frac{b+y}{2} &= \frac{b'+d}{2} \\ \\
x &= a'+c -a \\
x &= (a'- a) + c \\ \\
y&=(b'+d)-b \\
y&=(b'-b)-d
\end{align}
$$

- se por exemplo, $C=(0,0)$, o ponto C está na origem O.
$$
\begin{cases}
x&=a'-a \\
y&=b'-b
\end{cases}
$$

- por fim dizemos que $AA'$ e $CC'$ são $\underline{equipolentes}$ se, e somente se, (o segmento $CC'$ é obtido a partir de $AA'$):
	- $\fbox{a'-a = c'-c}$ e $\fbox{b'-b=d'-d}$