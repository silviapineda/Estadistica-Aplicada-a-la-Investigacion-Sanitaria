# Resultados

El 60% de los individuos de una población están vacunados contra una cierta enfermedad. Durante una epidemia se sabe que el 20% la ha contraído y que 2 de cada 100 individuos están vacunados y son enfermos. ¿Cuál es la probabilidad de contraer la enfermedad si se está vacunado? ¿Y la de estar vacunado si se tiene la enfermedad?

1. Definir Sucesos

Suceso A: "Estar vacunado"

Suceso B: "Padecer la enfermedad"

2. ¿Qué hay que calcular?

P(A/B)&#x20;

P(B/A)

3. ¿Qué sabemos?

P(A) = 0.6

P(B) = 0.2

$$P(A{\cap}B)=0.02$$

4. Solución

$$P(A/B)=\frac{P(A{\cap}B)}{P(A)}=\frac{0.02}{0.6}=0.033$$

$$P(B/A)=\frac{P(A{\cap}B)}{P(B)}=\frac{0.02}{0.2}=0.1$$

La proporción de alcohólicos que existe en una población es del 10%, sin embargo es difícil que un médico diagnostique alcoholismo, pero si que diagnostiquen hepatopatías, lumbalgias, etc…que pueden hacer sospechar de alcoholismo subyacente. Se realizó un estudio que puso de manifiesto que el 85% de los individuos alcohólicos y el 7% de los no alcohólicos sufrían tales patologías. Se desea saber cuál es la probabilidad de que un individuo con esas patologías sea realmente alcohólico

Suceso A: Ser alcohólico

Suceso B: Tener patologías

Sabemos que:

$$P(A)=0.1$$

$$P(B/A)=0.85$$

$$P(B/A^c)=0.07$$

Quremos saber: P(A/B), es decir la probabilidad de ser alcohólico si conocemos patologías.

Aplicando el teorema de Bayes:

$$
P(A/B) = \frac{P(B/A) \cdot P(A)}{P(B)}
$$

y par calcular la P(B) hacemos uso de la probabilidad total:

$$
P(B) = P(B/A)\cdot P(A)+P(B/A^c)\cdot P(A^c)=0.85*0.1+0.07*(1-0.1)=0.148
$$

Sustituyendo arriba:

$$
P(A/B) = \frac{0.85 \cdot 0.1}{0.148}=0.574
$$



