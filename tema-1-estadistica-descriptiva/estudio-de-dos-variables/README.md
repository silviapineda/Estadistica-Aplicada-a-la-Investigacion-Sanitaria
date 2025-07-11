---
cover: ../../.gitbook/assets/estadísticadescriptiva.webp
coverY: 0
---

# Estudio de dos variables

Entendemos que existe relación o dependencia entre dos variables cuando un cambio en el valor de una de ellas se asocia a un cambio en el de la otra. La situación contraria, es decir, la ausencia de relación, se denomina independencia.

## Relación entre dos variables cuantitativas

**Ejemplo**

1. **No hay relación** entre un valor mayor en la última cifra del DNI con un valor mayor en la concentración de colesterol en sangre
2. **Si hay relación** entre un valor mayor en el peso de un individuo con un valor mayor en la altura de ese mismo individuo

Para llevar a cabo el estudio de relación entre dos variables numéricas es preciso efectuar un análisis previo de las mismas por separado, según vimos en el capítulo anterior.&#x20;

Así pues, supongamos que contamos con $$n$$ individuos o unidades experimentales sobre los que se miden numéricamente dos caracteres, dando lugar a sendas variables cuantitativas $$X$$ e $$Y$$ . De la medición de dichos caracteres sobre las unidades experimentales resultarán $$n$$ pares de datos numéricos, que se denotarán así: $$(x_1;y_1),(x_2;y_2),...,(x_n;y_n)$$. La primera componente del par $$(x_i;y_i)$$, es decir, el valor $$x_i$$, corresponde a la medición de $$X$$  en la $$i-ésima$$ unidad experimental y la segunda corresponde a la variable $$Y$$.&#x20;

La relación entre dos variables puede ser directa o indirecta y la representaremos gráficamente mediante **diagramas de dispersión** y cuantificaremos numéricamente mediante **medidas de asociación**

### Diagrama de dispersión

Un diagrama de dispersión, también conocido como gráfico de dispersión o scatter plot en inglés, es una herramienta gráfica utilizada para mostrar la relación entre dos variables numéricas. En este diagrama, los datos se representan como puntos en un sistema de coordenadas cartesianas, donde cada punto representa una observación individual de las dos variables.

<figure><img src="../../.gitbook/assets/image (50).png" alt="" width="563"><figcaption></figcaption></figure>

### Relación Directa

Cuando aumentan los valores de una variable también aumentan los valores de la otra variable

**Ejemplo**

La siguiente tabla representa el peso, $$X$$ (kg) y la altura, $$Y$$, (cm) de 12 individuos

<figure><img src="../../.gitbook/assets/image (63).png" alt="" width="563"><figcaption></figcaption></figure>

Si representamos esos valores en un **diagrama de dispersión** vemos los siguiente:

<figure><img src="../../.gitbook/assets/image (64).png" alt="" width="432"><figcaption></figcaption></figure>

Estas dos variables (Peso y Altura) tienen una relación directa.

### Relación Indirecta

Cuando aumentan los valores de una variable disminuyen los valores de la otra variable

**Ejemplo**

Ahora tenemos n = 12 mediciones de las concentraciones de hormona paratiroidea ( g/ml) y de calcio en sangre (mg/100ml).

Si representamos los valores obtenidos en un diagrama de dispersión vemos lo siguiente:

<figure><img src="../../.gitbook/assets/image (49).png" alt="" width="563"><figcaption></figcaption></figure>

Cuando aumenta la concentración de hormona paratiroidea, disminuye la concentración de calcio.

### Medidas de asociación

Miden el grado de asociación o relación entre dos variables estadísticas observadas conjuntamente

#### Coeficiente de correlación de Pearson

Es una medida de la fuerza y dirección de la relación lineal entre dos variables numéricas X e Y. Su valor oscila entre -1 y 1, donde:

* 1 indica una correlación positiva perfecta.
* -1 indica una correlación negativa perfecta.
* 0 indica que no hay correlación lineal.

$$
r = \frac{\sum_{i=1}^{n} (x_i - \overline{x})(y_i - \overline{y})}{\sqrt{\sum_{i=1}^{n} (x_i - \overline{x})^2} \sqrt{\sum_{i=1}^{n} (y_i - \overline{y})^2}}
$$

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

## Relacion entre dos variables cualitativas

Teniendo dos variables cualitativas medidas en $$n$$ individuos, usaremos la tabla de contingencia o tablas cruzadas para estudiarlas y representarlas.&#x20;

### Tablas de contingencia

Es una tabla de frecuencias bidimensional o de doble entrada donde se indica las veces que se registra cada combinación de categorías.

Tenemos 500 individuos a los que clasificamos entre los que tuvieron una enfermedad respiratoria y los que no y se les preguntó si eran o no fumadores. Su tabla cruzada será la siguiente:

|            | Enfermedad Respiratoria | Sin Enfermedad Respiratoria | Total |
| ---------- | ----------------------- | --------------------------- | ----- |
| Fumador    | 150                     | 100                         | 250   |
| No fumador | 50                      | 200                         | 250   |
| Total      | 200                     | 300                         | 500   |

Esta tabla la podemos convertir en **porcentajes totales**:

| % totales  | Enfermedad Respiratoria | Sin Enfermedad Respiratoria | Total |
| ---------- | ----------------------- | --------------------------- | ----- |
| Fumador    | 150 (150/500 = 0.3)     | 100 (100/500=0.2)           | 250   |
| No fumador | 50 (50/500=0.1)         | 200(200/500=0.4)            | 250   |
| Total      | 200                     | 300                         | 500   |

&#x20;**porcentajes por filas**:

| % por filas | Enfermedad Respiratoria | Sin Enfermedad Respiratoria | Total |
| ----------- | ----------------------- | --------------------------- | ----- |
| Fumador     | 150 (150/250 = 0.6)     | 100 (100/250=0.4)           | 250   |
| No fumador  | 50 (50/250=0.2)         | 200(200/250=0.8)            | 250   |
| Total       | 200                     | 300                         | 500   |

o **porcentajes por columnas**:

| % por columnas | Enfermedad Respiratoria | Sin Enfermedad Respiratoria | Total |
| -------------- | ----------------------- | --------------------------- | ----- |
| Fumador        | 150 (150/200 = 0.75)    | 100 (100/300=0.3)           | 250   |
| No fumador     | 50 (50/200=0.25)        | 200(200/300=0.7)            | 250   |
| Total          | 200                     | 300                         | 500   |

<details>

<summary>¿Qué porcentaje de individuos fuman y tienen enfermedad respiratoria? </summary>

30%

</details>

<details>

<summary>¿Qué porcentaje de individuos no fuman y no tienen enfermedad respiratoria?</summary>

40%

</details>

<details>

<summary>¿Qué porcentaje de los que fuman tienen enfermedad respiratoria?</summary>

60%

</details>

<details>

<summary>¿Qué porcentaje de los que no fuman no tienen enfermedad respiratoria?</summary>

80%

</details>

<details>

<summary>¿Qué porcentaje de los que tienen enfermedad respiratoria fuman? </summary>

75%

</details>

<details>

<summary>¿Qué porcentaje de los que no tienen enfermedad respiratoria no fuman? </summary>

70%

</details>

Para poder cuantificar si hay o no asociación entre estas dos variables haremos una representación gráfica y usaremos la prueba de chi-cuadrado

### Representación gráfica diagrama de barras

{% tabs %}
{% tab title="Porcentajes por filas" %}
<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Porcentajes por columnas" %}
<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Prueba chi-cuadrado

La prueba de chi-cuadrado se utiliza para probar la independencia de dos variables entre sí, mediante la presentación de los datos en una tabla de contingencia (Lo veremos más adelante)
