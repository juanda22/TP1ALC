# TP1ALC

Primer trabajo practico de la materia Algebra lineal computacional, este se enfoca en implementar el método de la potencia para encontrar el autovalor dominante de matrices grandes, y analizar su convergencia en distintos tipos de matrices.

El método de la potencia es un algoritmo iterativo utilizado para encontrar el autovalor dominante (de mayor módulo) de una matriz. Dado un vector inicial aleatorio $v_0$, se aplica repetidamente el producto:

$𝑣_𝑘+1=𝐴𝑣_𝑘/∥𝐴𝑣_𝑘∥$ 
en cada iteración $k$, donde se normaliza el vector resultante.

La estimación del autovalor dominante en la iteración $k$ se calcula con:

𝜆
𝑘
=
𝑣
𝑘
𝑇
𝐴
𝑣
𝑘
𝑣
𝑘
𝑇
𝑣
𝑘
λ 
k
​
 = 
v 
k
T
​
 v 
k
​
 
v 
k
T
​
 Av 
k
​
 
​

 
​
