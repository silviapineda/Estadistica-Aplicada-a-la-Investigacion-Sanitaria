---
cover: ../../.gitbook/assets/desktop_fcdfecd9-6366-44d5-a06e-d679e9d12920.jpg
coverY: 218.1653333333333
---

# Problema de estimación mediante     intervalo de confianza

## Variables cuantitativas

<mark style="color:orange;">**Ejemplo**</mark>

Evaluar el nivel medio ( $$\mu$$) de glucosa en pacientes celiacos después de cinco años de dieta sin gluten

**Variable aleatoria X** = nivel de glucosa en sangre (mg/dl)

**Estimador puntual**: media muestral $$\bar{x}$$

Para calcular el nivel medio de glucosa en sangre tomaremos una muestra de t**amaño&#x20;**_**n**_**, con media** $$\bar{x}$$ **y varianza** $$s^2$$

**Sabemos que**: media muestral ( $$\bar{x} = 81.5$$) y que el tamaño de la muestra (n) = 100 individuos



<figure><img src="../../.gitbook/assets/image (147).png" alt="" width="563"><figcaption></figcaption></figure>



**Problema**: hay una estimación diferente dependiendo de la muestra que salga elegida. Es necesario dar, junto a la estimación, un valor de la variación o dispersión de todas las posibles estimaciones, que dé idea de su exactitud, esto lo hacemos a través del **Error Estándar del estimador (SE)**

**Error Estándar del estimador (SE)**

$$
SE=\frac{s}{\sqrt{n}}
$$

El error estándar mide la dispersión del estimador. Da idea de lo “buena” que es la estimación.

<figure><img src="../../.gitbook/assets/image (149).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (150).png" alt="" width="563"><figcaption></figcaption></figure>

**El error estándar depende de:**

* La desviación típica de la muestra
* El número de pacientes en la muestra (tamaño de la muestra). Mayor tamaño, menor error estándar

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

La estimación y el error estándar se conjugan construyendo un **INTERVALO DE CONFIANZA** para 𝝁

### Intervalo de confianza

Un **intervalo de confianza** es un rango de valores, construido a partir de la muestra, donde con una gran seguridad, el valor verdadero de la población se encuentra en él.

Se dice que el intervalo (a,b) es un intervalo de confianza para 𝝁 con un nivel de confianza $$1-\alpha$$ ( $$\alpha = 0.05, \alpha=0.01$$) si,

$$
P\left\{ \mu \in (a, b) \right\} \geq 1 - \alpha, \quad \alpha = 0.05, \; \alpha = 0.01
$$

X es una variable aleatoria con una media (𝝁) y una varianza (σ2)

A partir de una muestra de tamaño n, la media $$\bar{x}$$̅ de la muestra es una variable numérica que puede seguir una distribución N(𝝁, σ2/n) ,cuando n es suficientemente grande.

Es decir, dada una población con media μ y varianza σ2, la media de una muestra aleatoria de tamaño n extraída de esta población es una variable aleatoria. Cuando el tamaño de la muestra n es **suficientemente grande**, la media muestral  $$\bar{x}$$̅  sigue una distribución aproximadamente normal, independientemente de la distribución original de los datos de la población. Este resultado proviene del **Teorema Central del Límite (TCL)**.

#### Teorema Central del Límite (TCL)

El Teorema Central del Límite establece que, si tomamos muestras repetidas de tamaño n de una población y calculamos la media de cada muestra, las medias muestrales $$\bar{x}$$̅  se distribuyen aproximadamente de manera normal, con una media μ (la misma que la media de la población) y una varianza igual a σ2/n (donde σ2 es la varianza de la población).

**Si tipificamos** $$\bar{x}$$

$$
\frac{\bar{x} - \mu}{\sigma / \sqrt{n}} \sim N(0, 1)
$$

En consecuencia, para un 95% o 99% de las posibles muestras de tamaño n, se verifica que:

$$
\left| \frac{\bar{x} - \mu}{\sigma / \sqrt{n}} \right| \leq Z_{\alpha / 2}
$$

siendo $$Z_{\alpha / 2} = 1.96$$ para ($$\alpha=0.05$$ )y $$Z_{\alpha / 2} = 2.58$$ ( $$\alpha=0.01)$$



Y por tanto,

$$
\left| \bar{x} - \mu \right| \leq 1.96 \cdot \frac{\sigma}{\sqrt{n}}
$$

La expresión del **INTERVALO DE CONFIANZA (95%)** para la media 𝝁:

$$
(Estimación-Z_{\alpha / 2}·SE, Estimación+ Z_{\alpha / 2} ·SE)
$$

$$
\left( \bar{x} - 1.96 \cdot \frac{s}{\sqrt{n}}, \; \bar{x} + 1.96 \cdot \frac{s}{\sqrt{n}} \right)
$$



#### Distribución N(0,1) y cuantil $$Z_{\alpha/2}$$

<figure><img src="../../.gitbook/assets/image (154).png" alt="" width="563"><figcaption></figcaption></figure>

$$Z_{\alpha/2}$$ es el valor que delimita dos colas con el 5 % de los datos más extremos en la distribución N(0, 1)

El nivel de confianza ($$1-\alpha$$) es una probabilidad que representa la seguridad de que el intervalo construido contenga a $$\mu$$, ya que $$\mu$$ está en el $$(1-\alpha)$$% de los intervalos que pudieran construirse.

<figure><img src="../../.gitbook/assets/image (155).png" alt="" width="563"><figcaption></figcaption></figure>

<mark style="color:orange;">**Ejemplo**</mark>

<figure><img src="../../.gitbook/assets/image (156).png" alt="" width="563"><figcaption></figcaption></figure>

<mark style="color:orange;">**¿Mi intervalo\[75.6 y 87.4 mg/dl ] contiene a 𝝁?**</mark>

No lo sabemos seguro, pero sí con una seguridad del 95%

**CONCLUSIÓN**

**Con una seguridad del 95%, el nivel medio de glucosa en sangre de los individuos celiacos después de cinco años de dieta sin gluten está entre un 75.6 y 87.4 mg/dl**

Para un tamaño de muestra fijo, la amplitud del intervalo de confianza va a ser mayor…

&#x20; \- Cuanto mayor sea el error estándar del estimador

&#x20; \- Cuanto mayor sea la confianza que se fije.&#x20;

<mark style="color:orange;">**Ejemplo**</mark>

Se pretende estimar la media $$\mu$$ de la variable aleatoria X : estatura de las mujeres entre 16 y 50 años que pertenecen a una amplia población. Para ello se cogió una muestra aleatoria de n = 40 mujeres, las cuales aportaron una media de 162.3 cm y una desviación típica de 5.2 cm. Calcular el IC (95%):

<figure><img src="../../.gitbook/assets/image (157).png" alt="" width="563"><figcaption></figcaption></figure>

## Variables cualitativas

<mark style="color:orange;">**Ejemplo**</mark>

Objetivo: Calcular el porcentaje de recaídas a los seis meses en pacientes recuperados de un episodio severo de depresión

**Evaluar un porcentaje P o una proporción**

**Variable aleatoria** X: recaidas

<figure><img src="../../.gitbook/assets/image (124).png" alt="" width="139"><figcaption></figcaption></figure>

**Estimador puntual**: proporción muestral _p_&#x20;

Se evalúa ese porcentaje con la proporción de pacientes de la muestra que presentan recaída

<figure><img src="../../.gitbook/assets/image (142).png" alt="" width="563"><figcaption></figcaption></figure>

**Problema**: hay una estimación diferente dependiendo de la muestra que salga elegida. Es necesario dar, junto a la estimación, un valor de la variación o dispersión de todas las posibles estimaciones, que dé idea de su exactitud, esto lo hacemos a través del **Error Estándar del estimador (SE)**

**Error Estándar del estimador (SE)**

$$
SE=\sqrt{\frac{p(1-p)}{n}}
$$

El error estándar mide la dispersión del estimador. Da idea de lo “buena” que es la estimación.

<figure><img src="../../.gitbook/assets/image (149).png" alt="" width="563"><figcaption></figcaption></figure>

**El error estándar depende de:**

* El porcentaje en la población
* El número de pacientes en la muestra (tamaño de la muestra). Mayor tamaño, menor error estándar

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

La estimación y el error estándar se conjugan para construir un **INTERVALO DE CONFIANZA para P**

<figure><img src="../../.gitbook/assets/image (143).png" alt="" width="563"><figcaption></figcaption></figure>

**¿Mi intervalo \[49.5%-55.3%] contiene a P?**

No lo sabemos seguro, pero sí con una seguridad del 95%

**CONCLUSIÓN**

**Con una seguridad del 95%, el % de personas que presentan recaída a los seis meses, está entre un 49.5% y un 55.3%**

Para un tamaño de muestra fijo, la amplitud del intervalo de confianza va a ser mayor…

&#x20; \- Cuanto mayor sea el error estándar del estimador

&#x20; \- Cuanto mayor sea la confianza que se fije.&#x20;

<figure><img src="../../.gitbook/assets/image (144).png" alt="" width="563"><figcaption></figcaption></figure>
