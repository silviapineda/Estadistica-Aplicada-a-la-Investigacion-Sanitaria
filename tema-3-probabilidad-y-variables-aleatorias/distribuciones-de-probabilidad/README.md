---
cover: ../../.gitbook/assets/set-simple-small-game-dice-260nw-2293982075.webp
coverY: 0
---

# Distribuciones de probabilidad

Vamos a estudiar como a través de las variables aleatorias, es posible convertir cualquier resultado en un número, de manera que va a ser más sencillo estudiar los experimentos.

## Variable aleatoria (X):&#x20;

Es el resultado de un evento aleatorio, es decir de un experimento.

* **Discretas**: Solo toma ciertos valores
* **Continuas**: Puede tomar cualquier valor

| Experimento aleatorio                              | Resultados posibles        | Variable aleatoria (X)               | Posibles valores                           |
| -------------------------------------------------- | -------------------------- | ------------------------------------ | ------------------------------------------ |
| Medir estatura de los estudiantes al azar          | 1.50m-2.20m                | Estatura                             | Cualquier valor continuo 1.82m, 1.54m, etc |
| Contar el Nº de hermanos de individuos al azar     | 0-15                       | Nº hermanos                          | Cualquier valor discreto 0,1,2,3,4,etc     |
| Medir las preferencias de pacientes de un hospital | Médico A,         Médico B | 0-Médico A,               1-Médico B | Cualquier valor 0 o 1                      |
| Medir si dichos pacientes tienen hipertensión      | Si-No                      | 0- Si, 1-No                          | Cualquier valor 0 o 1                      |

¿Cuánto suma la la probabilidad de que la variable aleatoria **X: Hipertensión** tome el valor 0 más la probabilidad de que tome el valor 1?

¿Cuánto suma la probabilidad de que la variable aleatoria X: “Preferencia" tome el valor 0 más la probabilidad de que tome el valor 1?

¿Cuánto suma la probabilidad de que la variable aleatoria X: “Nº hermanos" sea igual a 0, más la probabilidad de que sea 1, más que sea 2, …?

¿Cuánto suma la probabilidad de que la variable aleatoria X: “Estatura” sea igual a 1.5m, mas que sea 1.6m, mas 1.7, …?

**En todos estos casos se distribuye la cantidad 1, entre todos los posibles valores que puede tomar la variable aleatoria**

Dependiendo de qué cantidad se atribuye a cada valor de la variable aleatoria, se está definiendo la **DISTRIBUCIÓN (de probabilidad) DE LA VARIABLE ALEATORIA**

## Distribución de probabilidad

La **distribución de probabilidad** describe cómo se distribuyen las probabilidades de los diferentes resultados en un experimento aleatorio. En términos simples, nos dice qué tan probable es cada resultado. Existen dos tipos principales de distribuciones de probabilidad

**Distribuciones de probabilidad discreta**: Ej. Binomial

**Distribuciones de probabilidad continua**: Ej. Normal

La distribución de probabilidad está definida sobre el conjunto de todos los sucesos y cada uno de los sucesos es el rango de valores de la variable aleatoria.

### Distribución de probabilidad discreta

Se aplica cuando las variables aleatorias toman un número finito o contable de valores.

La **función de probabilidad** es una función que asigna una probabilidad a cada valor posible de la variable.

#### Distribución binomial \~ $$Bin (n,p)$$

Describe el número de éxitos en una serie de ensayos independientes. Cada ensayo tiene dos posibles resultados: éxito o fracaso. Esta distribución es muy útil para modelar situaciones donde se realizan varios intentos de un experimento que solo tiene dos resultados posibles (como "sí" o "no", "verdadero" o "falso").

$$n$$ es el número de repeticiones del ensayo

$$p$$ la probabilidad de éxito

#### Función de masa de probabilidad binomial

La probabilidad de obtener exactamente $$x_i$$ éxitos en $$n$$ ensayos se calcula con la siguiente fórmula:

$$
P(X = x_i) = \binom{n}{x_i} p^{x_i} (1 - p)^{n - x_i}
$$

Donde:

* $$P(X=x_i)$$ es la probabilidad de obtener exactamente $$x_i$$ éxitos.
* $$\binom{n}{x_i}$$ es el coeficiente binomial, que se calcula como $$\frac{n!}{x_i!(n-x_i)!}$$.
* $$p$$ es la probabilidad de éxito en un solo ensayo.
* $$(1-p)$$ es la probabilidad de fracaso.
* $$n$$ es el número total de ensayos.
* $$x_i$$ es el número de éxitos deseado.

#### Función de distribución

Es la función acumulada que representa que una variable aleatoria tenga un valor menor o igual que cierto valor

$$
F(X)=P(X\leq{x_i})
$$

<mark style="color:orange;">**Ejemplo**</mark>

En una población donde la $$P(niño)=P(niña)=p$$, estudiamos la variable aleatoria&#x20;

X: Número de niños nacidos de entre los 10 primeros nacimientos&#x20;

&#x20;$$Bin(n,p) - Bin(10,0.5)$$

| Variable aleatoria X |  Función de masa de probabilidad | Función de distribución |
| -------------------- | -------------------------------- | ----------------------- |
| $$X$$: Nº de niños   | $$P_i=P(X=x_i)$$                 | $$F(x_i)$$              |
| $$x_1=0$$            | $$p_1=0.0009$$                   | 0.0009                  |
| $$x_2=1$$            | $$p_2=0.009$$                    | 0.0107                  |
| $$x_3=2$$            | $$p_3=0.043$$                    | 0.0546                  |
| $$x_4=3$$            | $$p_4=0.117$$                    | 0.1718                  |
| $$x_5=4$$            | $$p_5=0.205$$                    | 0.3769                  |
| $$x_6=5$$            | $$p_6=0.246$$                    | 0.623                   |
| $$x_7=6$$            | $$p_7=0.205$$                    | 0.8281                  |
| $$x_8=7$$            | $$p_8=0.117$$                    | 0.9453                  |
| $$x_9=8$$            | $$p_9=0.043$$                    | 0.9892                  |
| $$x_{10}=9$$         | $$p_{10}=0.009$$                 | 0.9990                  |
| $$x_{11}=10$$        | $$p_{11}=0.0009$$                | 1                       |

$$
P(X = 3) = \binom{10}{3} 0.5^{3} (1 - 0.5)^{10-3}=0.117
$$

Si la representamos gráficamente obtenemos lo siguiente:

<figure><img src="../../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>



<details>

<summary>¿Cuál es la probabilidad de que nazcan menos de 6 niños entre los 10 primeros nacimientos?</summary>

0.623

</details>

### Distribución de probabilidad continua

Se aplica cuando las variables pueden tomar un número infinito de valores dentro de un rango continuo.

La **función de probabilidad** es una función que asigna una probabilidad a cada valor posible de la variable

#### Distribución normal \~ $$N(\mu,\sigma)$$

&#x20;$$\mu$$ es la media&#x20;

&#x20;$$\sigma$$ es la desviación típica

La **distribución normal**, también conocida como **distribución de Gauss**, es una de las distribuciones de probabilidad más importantes en estadística y probabilidad, ya que muchos fenómenos naturales, sociales y físicos tienden a seguir este patrón. Se caracteriza por una curva en forma de campana y simétrica alrededor de su media.&#x20;

Altura, peso, notas de un examen, salario de una población determinada, temperatura corporal, presión arterial, tiempo de gestación.&#x20;

[https://www.youtube.com/watch?v=phY8Z9-TXCY](https://www.youtube.com/watch?v=phY8Z9-TXCY)

#### Función de densidad de probabilidad

La **función de densidad** de una variable aleatoria X que sigue una distribución normal con media $$\mu$$ y desviación estándar $$\sigma$$ está dada por la fórmula:

$$
f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{-\frac{(x - \mu)^2}{2\sigma^2}}
$$

Donde:

* $$\mu$$ es la media de la distribución.
* $$\sigma$$ es la desviación estándar.

<mark style="color:orange;">**Ejemplo**</mark>

Consideremos la variable aleaotoria X: Altura de un individuo hombre

Supongamos que tenemos 100 hombres y que su media es 170cm y la desviación típica es 12cm y los  vamos colocando en una gráfica, obtendremos algo así:

<figure><img src="../../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

Esta es la función de densidad de la varible aleatoria X: Altura de un individuo hombre&#x20;

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (89).png" alt="" data-size="original"></td><td>Esta sería la función de densidad</td><td></td></tr><tr><td><img src="../../.gitbook/assets/image (88).png" alt="" data-size="original"></td><td>La suma de todos los posibles valores es 1</td><td></td></tr><tr><td><img src="../../.gitbook/assets/image (90).png" alt="" data-size="original"></td><td>Esta sería la probabilidad de encontrar hombres con alturas entre 170 y 180</td><td></td></tr><tr><td><img src="../../.gitbook/assets/image (91).png" alt="" data-size="original"></td><td>Es más probable encontrar hombres que midan 170 a hombres que midan 160</td><td></td></tr><tr><td><img src="../../.gitbook/assets/image (92).png" alt="" data-size="original"></td><td></td><td>Es más probable encontrar hombres con una estatura entre 170 y 180 que mujeres</td></tr><tr><td><img src="../../.gitbook/assets/image (93).png" alt="" data-size="original"></td><td>Esta sería la Función de distribución <span class="math">F(x)</span></td><td></td></tr></tbody></table>

A modo de resumen:

<figure><img src="../../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

La distribución normal es **simétrica** en torno a su media y sigue la **regla empírica** de 68-95-99.7

* Aproximadamente el 68% de los datos se encuentran dentro de una desviación estándar de la media $$\mu \pm \sigma$$
* El 95% de los datos está dentro de dos desviaciones estándar $$\mu \pm 2\sigma$$&#x20;
* El 99.7% está dentro de tres desviaciones estándar $$\mu \pm 3\sigma$$&#x20;



<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td>Entre la media y una desviación típica tenemos siempre la misma probabilidad: aprox. 68%</td><td><img src="../../.gitbook/assets/image (95).png" alt="" data-size="original"></td><td></td></tr><tr><td>Entre la media y dos desviaciones típicas tenemos siempre la misma probabilidad: aprox. 95%</td><td><img src="../../.gitbook/assets/image (98).png" alt="" data-size="original"></td><td></td></tr><tr><td>Entre la media y dos desviaciones típicas tenemos siempre la misma probabilidad: aprox. 99%</td><td><img src="../../.gitbook/assets/image (99).png" alt="" data-size="original"></td><td></td></tr></tbody></table>



## Cáculo de probabilidades de la distribución normal

### Distribución Normal Estándar

Una distribución normal con media $$\mu=0$$  y  desviación estándar  $$\sigma = 1$$ se denomina **distribución normal estándar** y se denota como $$Z \sim N(0,1)$$.

La función de densidad de la N(0,1) es

<figure><img src="../../.gitbook/assets/image (159).png" alt="" width="411"><figcaption></figcaption></figure>

y para calcular sus probabilidades simplemente tenemos que hacer la integral sobre su función de destribución.

<mark style="color:orange;">**Ejemplo**</mark>

Para calcular la $$P(0 \leq Z \leq 1.35) = \int_{0}^{1.35} \frac{1}{\sqrt{2 \pi}} e^{-\frac{z^2}{2}} \, dz=0.411$$

<figure><img src="../../.gitbook/assets/image (161).png" alt="" width="363"><figcaption></figcaption></figure>

Para calcular la $$P(Z \leq 1) = \int_{-\infty}^{1} \frac{1}{\sqrt{2 \pi}} e^{-\frac{z^2}{2}} \, dz=0.841$$

<figure><img src="../../.gitbook/assets/image (163).png" alt="" width="383"><figcaption></figcaption></figure>

Todas las posibles probabilidades de una $$N(0,1)$$ se pueden consultar en unas tablas que llamamos tablas de la distribución normal.&#x20;

**Tablas**:&#x20;

[https://www.um.es/documents/877924/4876701/Tabla+de+la+distribuci%C3%B3n+normal.pdf/c812f3b4-7780-46e0-abfa-8c7cd452e407](https://www.um.es/documents/877924/4876701/Tabla+de+la+distribuci%C3%B3n+normal.pdf/c812f3b4-7780-46e0-abfa-8c7cd452e407)

Tenemos que tener en cuenta que la tabla sólo nos da el área que queda por debajo de un número positivo.

¿Cómo busco en la tabla $$P(Z \leq 0.34)$$ ?

<figure><img src="../../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

### Tipificación

Sería imposible tener una tabla para cada posible distribución normal, solamente la tenemos para la distribución normal estándar, es decir, para la $$N(0,1)$$.

Necesitaremos, pues, ser capaces de transformar las variables $$X \sim N( \mu, \sigma)$$ en variables estándar$$Z \sim N(0,1)$$. Este proceso de llevar cualquier distribución normal a una N( 0 , 1 ) se llama "**tipificación de la variable**".

Para tipificar X (o sea, transformarla en Z), el primer paso es "centrar" la variable; es decir, hacer que la media µ sea 0. El siguiente paso es conseguir que la desviación típica σ sea 1. \


Es decir, **restar la media y dividir por la desviación típica**



<mark style="color:orange;">**Ejemplo**</mark>

<figure><img src="../../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

A partir de ahora nos centramos en la distribución normal  N( 0 , 1 ) y vamos a ver cómo calcular probabilidades en ella. Para distinguir, siempre que hagamos referencia a una variable  N(0,1), vamos a expresarla con la letra Z.

<figure><img src="../../.gitbook/assets/image (77).png" alt=""><figcaption></figcaption></figure>

Con esto lo que hemos hecho es simplemente tipificar la variable transformando la probabilidad pedida en una relacionada con la normal N ( 0 , 1 ).

Como el valor de la tabla siempre es para calcular el área por debajo de un número positivo, tendremos que tener en cuenta lo siguiente:

1. $$P(Z \leq z)$$
2. $$P(Z>z)=1-P(Z \leq z)$$
3. $$P(Z> -z)=P(Z \leq z)$$
4. $$P(Z \leq -z)=P(Z>z)=1-P(Z \leq z)$$
5. $$P(z_1<Z \leq z_2)=P(Z \leq z_2)-P(Z \leq z_1)$$
