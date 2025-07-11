---
cover: ../../.gitbook/assets/desktop_fcdfecd9-6366-44d5-a06e-d679e9d12920.jpg
coverY: 291.26824595469253
---

# Problema de contraste de hipótesis

Se entiende por contrastar una hipótesis comprobar la veracidad o falsedad de cierta afirmación o hipótesis referida a alguna característica de la población.

**Hipótesis nula (**$$H_0$$**)**: es la afirmación que se cuestiona. Se mantendrá como cierta a no ser que los datos evidencien lo contrario.

**Hipótesis alternativa (** $$H_1$$**):** es la afirmación que se aceptará como verdadera cuando se demuestre la falsedad de $$H_0$$.

En el ejemplo que veíamos en la introducción donde se relacionabas las variables longitud del fémur y peso de 40 fetos de 26 semanas

<figure><img src="../../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

Con la estadística descriptiva veíamos una correlación directa entre ambas variables (**r = 0.802**)

Para poder generalizar la información de esa muestra a toda la población, podríamos plantear el siguiente contraste de hipótesis:

$$
H_0 : \rho = 0 \\
H_1 : \rho \neq 0
$$

Lo que buscamos con los datos de una muestra es rechazar la $$H_0$$ para demostrar la veracidad de la alternativa.

* <mark style="color:red;">**¿Cómo debe plantearse la hipótesis nula (**</mark> $$H_0$$<mark style="color:red;">**)?**</mark> Debería recoger la afirmación que se pretende comprobar que es falsa.
* <mark style="color:red;">**¿Cómo debe plantearse la hipótesis alternativa (**</mark> $$H_1$$<mark style="color:red;">**)?**</mark> Debería recoger la afirmación que se desea probar fuera de toda duda.

<mark style="color:orange;">**Ejemplo**</mark>

**Objetivo del estudio**: Evaluar la efectividad de un analgésico A, en comparación con un analgésico B, tras seis meses de tratamiento.

**Hipótesis nula (**$$H_0$$**)**:  La efectividad del analgésico A es la misma que la del analgésico B

**Hipótesis alternativa (** $$H_1$$**):** La efectividad del analgésico A no es la misma que la del analgésico B

**Variable principal X:** la valoración dada por el paciente sobre una escala de dolor (de 0 a 10) a los seis meses de tratamiento.

La variable es cuantitativa, así que usaremos la media para plantear el contraste de hipótesis.

$$
H_0 : \mu_A = \mu_B \\
H_1 : \mu_A \neq \mu_B
$$

donde

$$
\mu_A \text{ es la valoración media en la escala de dolor con el analgésico A}  \\ \mu_B \text{ es la valoración media en la escala de dolor con el analgésico B}
$$

## Errores asociados y potencia

**El error tipo I**: ocurre cuando se rechaza la hipótesis nula ( $$H_0$$) cuando en realidad es verdadera. La probabilidad de cometer un error tipo I se denota con ( $$\alpha$$), que es el nivel de significancia del contraste.&#x20;

El riesgo (probabilidad) de que ocurra este error debe estar controlado y ser menor que un valor fijado, normalmente: $$\alpha = 0.05$$

<mark style="color:orange;">**Ejemplo**</mark>: Analgésico A y B no son igual de efectivos cuando si lo son

**El error tipo II:** ocurre cuando no se rechaza la hipótesis nula ( $$H_0$$) cuando realmente es falsa. La probabilidad de cometer un error tipo II se denota con ( $$\beta$$).

El riesgo (probabilidad) de que ocurra este error debe estar controlado: $$\beta = 0.2$$

<mark style="color:orange;">**Ejemplo**</mark>: Analgésico A y B son igual de efectivos cuando no lo son

<figure><img src="../../.gitbook/assets/image (134).png" alt="" width="491"><figcaption></figcaption></figure>

Para un número de datos fijo (n) , si disminuye $$\alpha$$ aumenta $$\beta$$. Para disminuir ambos, hay que aumentar el número de datos (n).&#x20;

La **potencia del contraste es (** $$1 - \beta$$**)**, y representa la probabilidad de rechazar correctamente la hipótesis nula cuando es falsa.&#x20;

<figure><img src="../../.gitbook/assets/image (135).png" alt="" width="563"><figcaption></figcaption></figure>

## El p valor

El p-valor es una medida utilizada en las pruebas de hipótesis para determinar la significancia de los resultados obtenidos.&#x20;

**Representa la probabilidad de obtener un resultado tan extremo o más extremo que el observado, bajo la suposición de que la hipótesis nula es verdadera.**&#x20;

Un p-valor bajo indica que es poco probable que el resultado observado haya ocurrido bajo la hipótesis nula, lo que puede llevar a su rechazo en favor de la hipótesis alternativa.

La interpretación del p-valor depende del nivel de significancia ($$\alpha$$) preestablecido, que es el umbral para decidir si un resultado es estadísticamente significativo.&#x20;

Si el p-valor es menor que $$\alpha$$, se rechaza la hipótesis nula. Sin embargo, si es mayor, no se puede rechazar la hipótesis nula, aunque no necesariamente sea una prueba de su veracidad.

* Si los datos son muy discrepantes con la hipótesis nula, sería poco probable obtener otros más discrepantes

<figure><img src="../../.gitbook/assets/image (136).png" alt="" width="375"><figcaption></figcaption></figure>



* Si los datos son poco discrepantes con la hipótesis nula, sería bastante probable obtener otros más discrepantes

<figure><img src="../../.gitbook/assets/image (137).png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (138).png" alt="" width="563"><figcaption></figcaption></figure>

Para poder realizar un contraste de hipótesis, además de tener una muestra necesitaremos un montón de técnicas estadísticas que iréis viendo una a una, como ejemplo en este tema vamos a ver el test de student.&#x20;

## El test de student como ejemplo

Se utiliza para determinar si existe una relación significativa entre:

**Variable cualitativa dicotómica** (sano o enfermo, tratado o no tratado, hombre o mujer)

**Variable cuantitativa** (glucemia, presión arterial, etc)

Este problema se traduce en un problema de comparación de medias poblacionales ( $$\mu_1$$ y $$\mu_2$$) de la variable cuantitativa correspondientes a cada una de las categorías de la variable cualitativa

$$
H_0 : \mu_1 = \mu_2 \\
H_1 : \mu_1 \neq \mu_2
$$



Seleccionaremos una muestra independiente aleatoria para cada categoría y usaremos el test de la t de student para muestras independientes.

## <mark style="color:orange;">**Ejemplo**</mark>

Se estudia la posible relación entre la edad de la primera menstruación (menarquia) y la enfermedad celíaca. Para ello se toma una muestra de

n1 = 78 mujeres sanas

n2 = 78 mujeres celíacas

Se anotó la edad en años de la menarquia y se obtuvo la media y desviación típica de la muestra en los dos grupos:

&#x20;$$\bar{x}_1 = 12.74$$  y  $$s_1 = 1.48$$

&#x20;$$\bar{x}_2 = 13.33$$ y $$s_2=1.90$$

<figure><img src="../../.gitbook/assets/image (139).png" alt=""><figcaption></figcaption></figure>

Podemos observar que las mujeres celiacas presentan una menarquia ligeramente mayor en media y mediana que las sanas, pero **¿esta diferencia es signficativa?**

Lo que debemos evaluar es si  $$\bar{x}_1 - \bar{x}_2 = 0$$ (no podemos asumir que sea exactamente 0 porque debemos asumir diferencias entre las muestras).

El problema por tanto es cuantificar qué estamos dispuestos a achacar al azar.

El contraste de hipótesis que nos planteamos sería:

$$
H_0 : \mu_1 = \mu_2 \\
H_1 : \mu_1 \neq \mu_2
$$

o lo que es lo mismo

$$
H_0 : \mu_1 -\mu_2 =0 \\
H_1 : \mu_1 - \mu2 \neq 0
$$

De la misma forma que venimos haciendo, la diferencia de medias $$\bar{x}_1 - \bar{x}_2$$ es una variable cuantitativa que podemos tipificar

$$
t_{\text{exp}} = \frac{\bar{x}_1 - \bar{x}_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}} \sim N(0, 1)
$$

El **p-valor** se define como la probabilidad, según una N(0,1), de obtener una distancia tipificada entre medias al menos tan grande como la observada por la muestra.

El p-valor es el área de las dos colas que determinan | $$f(x) = x * e^{2 pi i \xi x}$$$$t_{\text{exp}}$$|

<figure><img src="../../.gitbook/assets/image (140).png" alt=""><figcaption></figcaption></figure>

En este ejemplo  $$t_{\text{exp}}$$= -2.18 con un p-valor = 0.031

Como p-valor < 0.05 => Rechazamos $$H_0$$ y por tanto demostramos que la celiaquía se relaciona con la menarquia.

## Test biltateral o unilateral

Una **prueba bilateral** (o prueba de dos colas) es aquella en la que la hipótesis alternativa plantea que el parámetro de interés es diferente a un valor específico. Esto implica que estamos interesados en detectar tanto aumentos como disminuciones respecto al valor hipotético.

$$
H_0 : \mu_1 = \mu_2 \\
H_1 : \mu_1 \neq \mu_2
$$

<figure><img src="../../.gitbook/assets/image (21).png" alt="" width="554"><figcaption></figcaption></figure>

Una **prueba unilateral** (o prueba de una cola) es aquella en la que la hipótesis alternativa plantea que el parámetro es mayor o menor que un valor específico. Esto implica que solo estamos interesados en detectar desviaciones en una dirección particular (hacia arriba o hacia abajo) con respecto al valor hipotético.

$$
H_0 : \mu_1 = \mu_2 \\
H_1 : \mu_1 > \mu_2
$$

$$
H_0 : \mu_1 = \mu_2 \\
H_1 : \mu_1 <\mu_2
$$

<figure><img src="../../.gitbook/assets/image (116).png" alt="" width="506"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (117).png" alt="" width="563"><figcaption></figcaption></figure>

* La **prueba bilateral** la usaremos cuando no tenemos una suposición específica sobre la dirección del cambio o cuando nos interesan desviaciones en ambas direcciones.
* La **prueba unilateral** la usaremos cuando tenemos una expectativa o suposición clara sobre la dirección de la desviación, como esperar que el parámetro sea mayor o menor que un valor específico.

#### Diferencias en la Interpretación

1. La prueba bilateral es más conservadora en términos de significancia, ya que divide α en dos colas, lo cual puede requerir un efecto más grande para rechazar $$H_0$$​.
2. La prueba unilateral permite concentrar toda la significancia en una sola cola, por lo que puede ser más poderosa para detectar efectos en una dirección específica, pero requiere una justificación clara para su uso.

## Resumen

<figure><img src="../../.gitbook/assets/image (118).png" alt="" width="563"><figcaption></figcaption></figure>

## <mark style="color:orange;">**Ejemplo**</mark>

Disponemos de los resultados del volumen espiratorio máximo en el primer segundo (FEV1) de dos grupos de pacientes (10 asmáticos y 10 bronquíticos), medido en condiciones basales y una hora después de haber administrado un medicamento denominado bamifilina.

¿La acción de la bamifilina es la misma en los enfermos asmáticos que en los bronquíticos?

| Diagnóstico | Bamifilina |
| ----------- | ---------- |
| A           | 98         |
| A           | 56         |
| A           | 87         |
| A           | 75         |
| A           | 72         |
| A           | 88         |
| A           | 59         |
| A           | 90         |
| A           | 79         |
| A           | 90         |
| B           | 90         |
| B           | 50         |
| B           | 35         |
| B           | 77         |
| B           | 35         |
| B           | 42         |
| B           | 70         |
| B           | 38         |
| B           | 90         |
| B           | 82         |

### **Objetivo del estudio**

Estudiar si la acción de la bamifilina en pacientes enfermos asmáticos es la misma que en pacientes enfermos bronquíticos a través del volumen espiratorio.

### **Plantear la hipótesis**

$$
H_0 : \mu_A = \mu_ B\\
H_1 : \mu_A \neq \mu_B
$$

donde,

$$\mu_A$$ es la media del volumen espiratorio después de la administración de bamifilina en asmáticos y

$$\mu_B$$ es la media del volumen espiratorio después de la administración de bamifilina en broinquíticos&#x20;

### **Aplicamos el t. test para resolverlo**

<figure><img src="../../.gitbook/assets/image (119).png" alt="" width="353"><figcaption></figcaption></figure>



### Cálculo del p-valor

<figure><img src="../../.gitbook/assets/image (120).png" alt="" width="563"><figcaption></figcaption></figure>

Como p < 0.05 => Rechazamos la $$H_0$$ y por tanto concluimos que la acción de la bamifilina en enfermos asmáticos y bronquíticos es diferente.

### ¿Cómo es esta diferencia?

Miramos las medias y por tanto concluimos que los asmáticos tienen un volumen espiratorio medio (79.4) mayor que los bronquíticos (60.9) tras el uso de la bamifilina.

### SPSS

<figure><img src="../../.gitbook/assets/image (121).png" alt=""><figcaption></figcaption></figure>



## Relación entre el p-valor y los intérvalos de confianza

El contraste de hipótesis planteado en el ejemplo del estudio de la posible relación entre la edad de la primera menstruación (menarquia) y la enfermedad celíaca era el siguiente:

$$
H_0 : \mu_1 = \mu_2 \\
H_1 : \mu_1 \neq \mu_2
$$

o lo que es lo mismo

$$
H_0 : \mu_1 -\mu_2 =0 \\
H_1 : \mu_1 - \mu2 \neq 0
$$

done $$\mu_1$$es la media de la menarquia en mujeres sanas y $$\mu_2$$ es la media de la menarquia en mujeres celíacas.

El p-valor obtenido era 0.031

**¿Pertenece el 0 al intervalo de confianza para** $$\mu_1 - \mu_2$$**?**

<figure><img src="../../.gitbook/assets/image (122).png" alt="" width="375"><figcaption></figcaption></figure>

El IC al 95% para $$\mu_1 - \mu_2$$: (-0.59  ± 0.534)= (-1.12 , -0.06)

<figure><img src="../../.gitbook/assets/image (123).png" alt="" width="563"><figcaption></figcaption></figure>

La conclusión es que existen diferencias entre la menarquia para las mujeres sanas y mujeres celíacas.

**RECOMENDACIÓN**: acompañar siempre el p-valor con un intervalo de confianza

