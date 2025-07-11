---
cover: ../../.gitbook/assets/set-simple-small-game-dice-260nw-2293982075.webp
coverY: 0
---

# Cálculo de probabilidades

El cálculo de probabilidades es una rama de la estadística que estudia la posibilidad de que ocurra un determinado evento. Se utiliza para predecir resultados en situaciones donde existe incertidumbre. La probabilidad de un evento se mide como un número entre 0 y 1, donde 0 significa que el evento es imposible, y 1 significa que el evento es seguro.

Para poder entender cómo se miden estas probabilidades y cómo afectan a la toma de decisiones, es importante familiarizarse con conceptos fundamentales como la **Regla de Laplace**, la **probabilidad condicionada**, el **Teorema de Bayes**, y la **probabilidad total**. Estos conceptos son la base de muchas aplicaciones, desde juegos de azar hasta la inferencia estadística, la inteligencia artificial y la toma de decisiones bajo incertidumbre.



## Regla de Laplace

Es la forma más básica de calcular probabilidades cuando todos los resultados posibles son igualmente probables.

La probabilidad de cualquier suceso A se calculará a través del cociente entre el nº de elementos que tiene el suceso (**casos favorables**) y el nº total de elementos del experimento (**casos posibles**).

$$
P(A) = \frac{\text{Número de casos favorables}}{\text{Número total de casos posibles}}
$$

**Ejemplo**

Si lanzamos un dado, la probabilidad de obtener un número par sería:

$$
P(\text{número par}) = \frac{3}{6} = 0.5
$$

Los casos favorables son {2,4,6}

Los casos posibles son {1,2,3,4,5,6}

**Ejercicio**

<details>

<summary>Una mujer portadora de hemofilia tiene 3 hijos. ¿Cuál es la probabilidad de que dos y sólo dos sean hemofílicos? ¿Y de que no tenga ninguno hemofílico?</summary>

Espacio muestral: $$\Omega=(\text{HHH,nHHH,HnHH,HHnH,nHnHH,nHHnH,HnHnH,nHnHnH})$$

Cada elemento tiene probabilidad 1/8 de ocurrir

Suceso A: “Dos hijos son hemofílicos”= (HHnH,HnHH,nHHH)

$$P(A) = \frac{3}{8} = 0.375$$

Suceso B: “Ninguno hemofílico”=(nHnHnH)

$$P(B) = \frac{1}{8} = 0.125$$



</details>

## Probabilidad condicionada

Describe cómo calcular la probabilidad de un evento dado que ya ha ocurrido otro evento. Es útil cuando sabemos información adicional que puede influir en el resultado.

La **Probabilidad Condicionada** se refiere a la probabilidad de que ocurra un evento A, dado que ya ha ocurrido otro evento B. Se calcula de la siguiente forma:

$$
P(A/B) = \frac{P(A \cap B)}{P(B)}​
$$

Esta fórmula supone que P(B)>0

**Ejemplo**

La prevalencia de depresión en España es del 10%.

Suceso A: "Tener depresión".   P(A)=0.1

Al escoger una persona al azar, la probabilidad de que padezca depresión, si se sabe que es mujer es del 20%

Suceso B: "Ser mujer"

La probabilidad de A condicionada a B es: $$P(A/B) = 0.2$$

**Ejercicio**

<details>

<summary>El porcentaje de mujeres que sobreviven a la extirpación y tratamiento de un cáncer de ovario es de un 60% a los dos años y de un 48% a los seis. ¿Cuál es la probabilidad de que una mujer que ha sobrevivido dos años, sobreviva seis?</summary>

Suceso A: "Sobrevivir a los 2 años"      P(A) = 0.6

Suceso B: "Sobrevivir a los 6 años"      P(B) = 0.48

Hay que calcular la probabilidad de sobrevivir 6 años si ya se han sobrevivido 2: P (B/A)

$$P(B/A) = \frac{P(A \cap B)}{P(A)}​=\frac{P(B)}{P(A)}=\frac{0.48}{0.60}​=0.8​$$

</details>

La probabilidad condicionada cumple las mismas propiedades que la probabilidad

### Propiedades de la probabilidad:

Las propiedades fundamentales de la probabilidad que nos van a permitir hacer cálculo de probabilidades son las siguientes:

#### 1. No Negatividad

$$
P(A/B)\geq 0
$$

#### 2. Normalización

$$
P(\Omega)=1
$$

$$
P(\emptyset)=0
$$

#### 3. Contención

Si $$A \subseteq B$$, entonces la probabilidad de A es menor o igual a la probabilidad de B.

$$
P(A/C) \leq P(B/C)
$$

#### 3. Aditividad

$$
P(A\cup B/C) = P(A/C) + P(B/C)-P(A \cap B/C)
$$



$$
P(A \cup B/C) = P(A/C) + P(B/C)
$$

#### 5. Complementariedad



$$
P(A^c/B) = 1 - P(A/B)
$$

$$
P(A \cap B/C) = P(A/C) \cdot P(B/C)
$$

{% hint style="info" %}
No confundir P(A/B) con P(B/A)

Suceso A: "soy un perro"

Suceso B: "tengo 4 patas"

P(A/B)=1    =>   Si soy un perro tengo 4 patas

P(B/A)=?    =>   Si tengo 4 patas no tengo por qué ser un perro&#x20;
{% endhint %}



<details>

<summary>El 95% de los adictos a la cocaína confiesa haber consumido también cannabis. Elegida una persona al azar y sean los sucesos A: "consume cannabis" y B:"consume cocaína". ¿Cuál es P(A/B)? ¿ y la P(B/A)?</summary>

La P(A/B) es la probabilidad de que sabiendo que consume cocaína consuma también cannabis: 0.95

La P(B/A) probabilidad de que, habiendo consumido cannabis, consuma también cocaína: ¿?

</details>



## Regla de la probabilidad total

La **Probabilidad Total** se usa cuando un evento puede ocurrir a través de varias vías mutuamente excluyentes. Se expresa como:

$$
P(B) = \sum_{i} P(B/A_i) \cdot P(A_i)
$$

Donde $$A_1, A_2, \dots, A_n$$​ son eventos mutuamente excluyentes que cubren todo el espacio muestral (una partición del espacio muestral). Esto permite calcular la probabilidad de un evento B cuando no tenemos una sola causa directa, sino varias posibles causas.

**Ejemplo**

Se quiere calcular el porcentaje de personas con depresión en cierta población, y se sabe que el 5% de los hombres lo son y también el 12% de las mujeres. Además, el 48% de la población son hombres y el resto mujeres.

Suceso A1: "Ser hombre"

Suceso A2: ·Ser mujer"

{A1,A2} son una partición de $$\Omega$$ y son mutuamente excluyentes

Queremos calcular la probabilidad de tener depresión

Suceso B: "Tener depresión"

P(A1) = 0.48

P(A2) = 1-0.48 = 0.52

$$
𝑃(𝐵)=𝑃(𝐵/ 𝐴_1)∗P(𝐴_1 )+𝑃(𝐵/ 𝐴_2)∗P(𝐴_2 ) = 0.05 * 0.48 + 0.12*0.52 = 0.0864
$$

El porcentaje de personas con depresión en dicha población es del 8.64%

## Teorema de Bayes (probabilidad condicionada)

El **Teorema de Bayes** se usa para actualizar la probabilidad de un evento basado en nueva información. Relaciona la probabilidad condicional P(A/B) con la P(B/A) y se expresa de la siguiente forma:

$$
P(A/B) = \frac{P(B/A) \cdot P(A)}{P(B)}
$$

donde la P(B) se calcula con la regla de la probabilidad total y por tanto queda:

$$
P(A/B) = \frac{P(B/A) \cdot P(A)}{P(B/A)\cdot P(A)+P(B/A^c)\cdot P(A^c)}
$$

Este teorema es fundamental en situaciones donde queremos ajustar nuestras creencias sobre un evento dado que hemos observado algún otro evento relacionado.

#### Ejemplo:

Supongamos que estamos estudiando la probabilidad de que un paciente tenga **diabetes tipo 2** (suceso A) si presenta **sed constante** (suceso B), un síntoma común asociado con esta enfermedad.&#x20;

&#x20;Sabemos lo siguiente:

La probabilidad de tener diabetes tipo 2 en la población adulta es del 10%. $$P(A)=0.10$$

La probabilidd de tener sed constante en personas con diabetes es del 70%. $$P(B/A)=0.70$$

La probabilidad de tner sed constante en personas sin diabetes es del 20%. $$P(B/A^c)=0.20$$

Queremos conocer la probabilidad de que el paciente tenga diabetes dada la presencia de sed constante, es decir, $$P(A/B)$$.

#### Aplicación del Teorema de Bayes:

El Teorema de Bayes establece que:

$$
P(A/B) = \frac{P(B/A) \cdot P(A)}{P(B)}
$$

y para calcular la P(B) usamos la regla de la probabilidad total:

$$
P(B/A)\cdot P(A)+P(B/A^c)\cdot P(A^c)=0.70*0.10+0.20*(1-0.10)=0.25
$$

Ahora, sustituimos en la fórmula de Bayes:



$$
P(A/B) = \frac{P(B/A) \cdot P(A)}{P(B)}=P(A/B) = \frac{0.70 \cdot 0.10}{0.25}=0.28
$$

La **probabilidad de que un paciente tenga diabetes tipo 2 si presenta sed constante** es del **28%**.&#x20;

Esto muestra cómo el conocimiento de un síntoma puede cambiar nuestra percepción del riesgo de una enfermedad.
