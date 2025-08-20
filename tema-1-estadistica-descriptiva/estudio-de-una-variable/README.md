---
cover: ../../.gitbook/assets/estadísticadescriptiva.webp
coverY: 0
---

# Estudio de una variable

La Estadística Descriptiva se dedica a la **descripción de un conjunto de&#x20;**_**n**_**&#x20;observaciones** representados en _**p**_**&#x20;variables**, entendiendo por descripción la **clasificación**, **representación gráfica** y **resumen** de los mismos. En un contexto más general esas **n** observaciones constituirán una **muestra** de tamaño _n_ extraída de una **población** con _**p**_**&#x20;variables**, y la descripción de dicha muestra habrá de completarse posteriormente con una inferencia o generalización al total de la población.

En todo caso distinguiremos entre la clasificación de los datos en tablas, la representación gráfica y el cálculo de parámetros que resuman la información. A su vez, distinguiremos entre variables cualitativas y cuantitativas.

La muestra n de la población en estudio y sus p variables las vamos a representar siempre en una tabla de la siguiente forma, con las n observacionbes por filas y p variables en columnas

#### Tabla de Datos de Satisfacción de Pacientes en un Hospital

<table data-full-width="true"><thead><tr><th width="127">ID Paciente</th><th width="87">Género</th><th width="72">Edad</th><th width="118">Estado Civil</th><th width="93">Tiempo de Espera (min)</th><th width="87">Grado Satisfacción (1-10)</th><th width="101">Número de Visitas </th><th>Estado de Salud (bueno/regular/malo)</th></tr></thead><tbody><tr><td>1</td><td>F</td><td>45</td><td>Casado</td><td>30,12</td><td>8</td><td>5</td><td>Bueno</td></tr><tr><td>2</td><td>M</td><td>60</td><td>Soltero</td><td>45,14</td><td>7</td><td>2</td><td>Regular</td></tr><tr><td>3</td><td>F</td><td>34</td><td>Divorciado</td><td>20,02</td><td>9</td><td>3</td><td>Bueno</td></tr><tr><td>4</td><td>M</td><td>50</td><td>Casado</td><td>50,03</td><td>6</td><td>4</td><td>Malo</td></tr><tr><td>5</td><td>F</td><td>28</td><td>Soltero</td><td>15,00</td><td>10</td><td>1</td><td>Bueno</td></tr><tr><td>6</td><td>M</td><td>70</td><td>Viudo</td><td>60,25</td><td>5</td><td>6</td><td>Regular</td></tr><tr><td>7</td><td>F</td><td>55</td><td>Casado</td><td>35,50</td><td>7</td><td>3</td><td>Bueno</td></tr><tr><td>8</td><td>M</td><td>40</td><td>Soltero</td><td>25,45</td><td>8</td><td>4</td><td>Bueno</td></tr><tr><td>9</td><td>F</td><td>65</td><td>Viudo</td><td>40,23</td><td>6</td><td>2</td><td>Malo</td></tr><tr><td>10</td><td>M</td><td>30</td><td>Casado</td><td>20,18</td><td>9</td><td>5</td><td>Bueno</td></tr></tbody></table>

n = 10 pacientes

p = 8 variales

V.Cuantitativas:

V.Cualitativas:&#x20;



## Pasos para el estudio de una variable:

1. Determinar el tipo de variable (Cuantitativa vs. Cualitativa)
2. Obtener tablas de frecuencias en caso de las cualitativas o cuantiativas discretas
3. Resumir los datos mediante medidas numéricas en caso de las cuantitativas
4. Representación gráfica

## Tablas de Frecuencias

Las variables cualitativas las vamos a resumir en tablas de frecuencias

Donde se ordenan y estructuran los valores de una **variable x** de forma resumida

**Frecuencia Absoluta de x:** nº de veces que se repite x

**Frecuencia Relativa de x:** proporción de veces que se repite x

**Frecuencia Absoluta Acumulada de x:** nº de observaciones menores o iguales que x

**Frecuencia Relativa Acumulada de x:** proporción de valores menores o iguales que x

<table data-full-width="false"><thead><tr><th width="218">Valores de la variable</th><th width="197">Frecuecias Absolutas</th><th>Frecuencias relativas</th><th>Frecuencias Absolutas acumuladas</th><th>Frecuencias Absolutas acumuladas</th></tr></thead><tbody><tr><td><span class="math">x_i</span></td><td><span class="math">f_i</span></td><td><span class="math">p_i</span></td><td><span class="math">F_i</span></td><td><span class="math">P_i</span></td></tr><tr><td></td><td></td><td></td><td></td><td></td></tr></tbody></table>

#### Ejemplo

En un estudio sobre el grupo sanguíneo realizado con n=6313 individuos se obtuvo la siguiente tabla de frecuencias

**Variable estadística x:** Grupo Sanguíneo (O, A, B, AB) con $$k = 4$$ categorías

<table data-full-width="false"><thead><tr><th width="172">Valores de la variable</th><th width="152">Frecuecias Absolutas</th><th width="184">Frecuencias relativas</th><th>Frecuencias Absolutas acumuladas</th><th>Frecuencias Absolutas acumuladas</th></tr></thead><tbody><tr><td><span class="math">x_i</span></td><td><span class="math">f_i</span></td><td><span class="math">p_i</span></td><td><span class="math">F_i</span></td><td><span class="math">P_i</span></td></tr><tr><td>O</td><td>2892</td><td>2892/6313 = 0.458</td><td>2892</td><td>0.458</td></tr><tr><td>A</td><td>2625</td><td>1625/6313 = 0.416</td><td>5517</td><td>0.874</td></tr><tr><td>B</td><td>570</td><td>570/6313 = 0.09</td><td>6087</td><td>0.964</td></tr><tr><td>AB</td><td>226</td><td>226/6313 = 0.036</td><td>6313</td><td>1</td></tr><tr><td>TOTAL</td><td>6313</td><td>1</td><td>6313</td><td>1</td></tr></tbody></table>



$$
\sum_{i=1}^kf_i =n
$$

$$
\sum_{i=1}^{k} p_i=1
$$



<details>

<summary>¿Qué conclusiones sacarías al ver esta tabla?</summary>

Pues que la gran mayoría de esta muestra tiene grupo sanguíneo O ó A con un 46% y 42% respectivamente y que los grupos B y AB son minoritarios, siendo el AB el más minoritario.

</details>

Las variables **cuantitativas discretas** las prodremos, en la mayoría de los casos, resumir en tablas de frecuencias.

**Ejemplo**

Las edades en un grupo de n = 25 estudiantes universitarios son:&#x20;

23, 21, 18, 19, 20, 18, 23, 21, 18, 20, 19, 22, 18, 19, 19, 18, 23, 22, 19, 22, 21, 18, 24, 24, 20

<table data-full-width="false"><thead><tr><th width="172">Valores de la variable</th><th width="152">Frecuecias Absolutas</th><th width="184">Frecuencias relativas</th><th>Frecuencias Absolutas acumuladas</th><th>Frecuencias Absolutas acumuladas</th></tr></thead><tbody><tr><td><span class="math">x_i</span></td><td><span class="math">f_i</span></td><td><span class="math">p_i</span></td><td><span class="math">F_i</span></td><td><span class="math">P_i</span></td></tr><tr><td>18</td><td>6</td><td>0.24</td><td>6</td><td>0.24</td></tr><tr><td>19</td><td>5</td><td>0.20</td><td>11</td><td>0.44</td></tr><tr><td>20</td><td>3</td><td>0.12</td><td>14</td><td>0.56</td></tr><tr><td>21</td><td>3</td><td>0.12</td><td>17</td><td>0.68</td></tr><tr><td>22</td><td>3</td><td>0.12</td><td>20</td><td>0.80</td></tr><tr><td>23</td><td>3</td><td>0.12</td><td>23</td><td>0.92</td></tr><tr><td>24</td><td>2</td><td>0.08</td><td>25</td><td>1</td></tr><tr><td>Total</td><td>25</td><td>1</td><td>25</td><td>1</td></tr></tbody></table>

Contesta a las siguientes preguntas:



<details>

<summary>¿Cuántos individuos tienen 21 años?</summary>

3

</details>

<details>

<summary>¿Qué porcentaje de individuos tiene más de 19 años?</summary>

1-0.44=0.56

</details>

**¿Qué pasa cuando tenemos una variable cuantitativa continua?**

Imagina que anotamos las puntuaciones obtenidas por  100 pacientes en un test psicológico en una escala continua del 0 al 100.&#x20;

$$
x_i: 11,42,58,25,48,18,45,35,59,29,35,2,37,68,70,31,44,84,64,82,26,42,51,29,59,92,56,5,52,8,1,12,21,6,32,15,67,47,61,47,43,33,48,47,43,69,49,21,9,15,11,22,29,14,31,46,19,49,51,71,52,32,51,44,58,60,43,65,73,62,3,17,39,22,40,65,30,31,16,80,41,59,60,41,51,10,63,41,74,81,20,36,59,38,40,43,18,60,71,44
$$

¿Tiene sentido hacer una tabla de frecuencias? ¿Nos resume la información? ¿Qué podemos hacer?

<table data-full-width="false"><thead><tr><th width="172">Valores de la variable</th><th width="152">Frecuecias Absolutas</th><th width="184">Frecuencias relativas</th><th>Frecuencias Absolutas acumuladas</th><th>Frecuencias Absolutas acumuladas</th></tr></thead><tbody><tr><td><span class="math">x_i</span></td><td><span class="math">f_i</span></td><td><span class="math">p_i</span></td><td><span class="math">F_i</span></td><td><span class="math">P_i</span></td></tr><tr><td>[0,10]</td><td>8</td><td>0.08</td><td>8</td><td>0.08</td></tr><tr><td>(10,20]</td><td>12</td><td>0.12</td><td>20</td><td>0.20</td></tr><tr><td>(20,30]</td><td>10</td><td>0.1</td><td>30</td><td>0.30</td></tr><tr><td>(30,40]</td><td>14</td><td>0.14</td><td>44</td><td>0.44</td></tr><tr><td>(40,50]</td><td>21</td><td>0.21</td><td>65</td><td>0.65</td></tr><tr><td>(50,60]</td><td>16</td><td>0.16</td><td>81</td><td>0.81</td></tr><tr><td>(60,70]</td><td>10</td><td>0.10</td><td>91</td><td>0.91</td></tr><tr><td>(70,80]</td><td>5</td><td>0.05</td><td>96</td><td>0.96</td></tr><tr><td>(80,90]</td><td>3</td><td>0.03</td><td>99</td><td>0.99</td></tr><tr><td>(90,100]</td><td>1</td><td>0.01</td><td>100</td><td>1</td></tr><tr><td>Total</td><td>100</td><td>1</td><td></td><td></td></tr></tbody></table>



<details>

<summary>¿Qué % ha obtenido una puntuación mayor que 70?</summary>

9%

</details>

<details>

<summary>¿Cuántos han obtenido como máximo 50 puntos?</summary>

65

</details>

> <mark style="color:red;">**Ahora es tu turno**</mark>

{% content-ref url="ejercicio-1-una-variable/" %}
[ejercicio-1-una-variable](ejercicio-1-una-variable/)
{% endcontent-ref %}

## Características numéricas

Nos referimos a las medidas con las que se pretende resumir y condensar la información contenida en un conjunto de datos

Las características numéricas las mediremos siempre en **Variables Cuantitativas**

### Medidas de centralización y posición&#x20;

Son los valores que resumen el conjunto de los datos de forma que reflejan el centro de la distribución de la tabla de frecuencias

#### **Media**

Es el valor medio. Es la suma de todos los valores dividida por el número total de valores.

$$
\bar{x} = \frac{\sum_{i=1}^n x_i}{n}
$$

<details>

<summary>Ejemplo: A los enfermeros de un centro de salud se les pregunta por el nº de hijos que tienen. Sus respuestas son: 0,1,2,0,1,1,0,0,2,2,3.  ¿Cuál es su media?</summary>

$$n=11$$

$$\sum_{i=1}^n x_i=0+1+2+0+1+1+0+0+2+2+3=12$$

$$\bar{x}=\frac{12}{11}= 1.09$$ hijos



</details>

La media es una medida útil y ampliamente aplicada de la tendencia central, pero debe ser utilizada con precaución en conjuntos de datos que contienen valores atípicos o están distribuidos de manera asimétrica

#### **Mediana**

Es el valor del medio. Divide la distribución de frecuencias en dos partes.

Para calcularla:

1. Ordenar los datos en orden creciente
2. Según el número de observaciones (n):
   * Si n es impar: La mediana es el valor que ocupa la posición central
   * Si n es par: La mediana es el promedio de los dos valores central

**Ejemplos:**

1. **Conjunto de datos con un número impar de observaciones:**
   * Datos: 3, 1, 4, 2, 5 (n=5)
   * Ordenados: 1, 2, 3, 4, 5
   * Mediana:  3 (el tercer valor)&#x20;
2. **Conjunto de datos con un número par de observaciones:**
   * Datos: 7, 2, 4, 6 (n=4)
   * Ordenados: 2, 4, 6, 7
   * Mediana: (4 + 6) / 2 = 5

&#x20;                   &#x20;

<details>

<summary>Ejemplo: A los enfermeros de un centro de salud se les pregunta por el nº de hijos que tienen. Sus respuestas son: 0,1,2,0,1,1,0,0,2,2,3.  ¿Cuál es su mediana?</summary>

$$n=11$$

Ordenados: 0,0,0,0,1,1,1,2,2,2,3

Mediana: Posición 6 = 1 hijo



</details>

La mediana es especialmente útil en distribuciones asimétricas o cuando se quiere una medida de tendencia central que no sea afectada por valores extremadamente altos o bajos.                &#x20;

#### **Moda**

Es el valor que presenta máxima frecuencia y se puede calcular para variables cualitativas. Es más, es un valor que suele usarse en el análisis de variables cualitativas.

**Ejemplos:**

1. **Unimodal:**
   * Datos: 2, 3, 4, 4, 5, 6
   * Moda: 4 (aparece dos veces, más que cualquier otro valor)
2. **Bimodal:**
   * Datos: 1, 2, 3, 3, 4, 4, 5
   * Modas: 3 y 4 (ambos aparecen dos veces)
3. **Multimodal:**
   * Datos: 2, 2, 3, 3, 4, 4, 5, 5
   * Modas: 2, 3, 4, y 5 (todos aparecen dos veces)
4.  **Sin moda:**

    * Datos: 1, 2, 3, 4, 5
    * Moda: No hay moda (todos los valores aparecen solo una vez)



<details>

<summary>Ejemplo: A los enfermeros de un centro de salud se les pregunta por el nº de hijos que tienen. Sus respuestas son: 0,1,2,0,1,1,0,0,2,2,3.  ¿Cuál es su moda?</summary>

![](<../../.gitbook/assets/image (59).png>)

La moda es 0 hijos

</details>

La moda es útil en análisis de datos cualitativos o categóricos, donde se busca identificar la categoría o valor más frecuente.

#### **Cuantiles**

Los cuantiles son valores que dividen un conjunto de datos en partes iguales según la distribución de los datos. Los cuantiles son útiles para comprender la distribución y la dispersión de los datos. Existen diferentes tipos de cuantiles, cada uno con un número específico de divisiones:

1. **Cuartiles:** Dividen el conjunto de datos en cuatro partes iguales.
   * **Primer cuartil (Q1):** Divide el 25% inferior de los datos del 75% superior.
   * **Mediana (Q2):** Divide el 50% inferior del 50% superior. Es el segundo cuartil.
   * **Tercer cuartil (Q3):** Divide el 75% inferior del 25% superior.
2. **Deciles:** Dividen el conjunto de datos en diez partes iguales.
   * **Primer decil (D1):** Divide el 10% inferior del 90% superior.
   * **Segundo decil (D2):** Divide el 20% inferior del 80% superior.
   * Y así sucesivamente hasta el noveno decil (D9), que divide el 90% inferior del 10% superior.
3. **Percentiles:** Dividen el conjunto de datos en cien partes iguales.
   * **Percentil 1 (P1):** Divide el 1% inferior del 99% superior.
   * **Percentil 2 (P2):** Divide el 2% inferior del 98% superior.
   * Y así sucesivamente hasta el percentil 99 (P99), que divide el 99% inferior del 1% superior.

**Ejemplo de cálculo de cuartiles:**

Supongamos que tenemos el siguiente conjunto de datos ordenados: 2, 4, 6, 8, 10, 12, 14, 16, 18, 20.

1. **Primer cuartil (Q1):**
   * Posición: (n+1)/4=(10+1)/4=2.75(n+1)/4 = (10+1)/4 = 2.75(n+1)/4=(10+1)/4=2.75
   * Valor: Entre el segundo y el tercer valor: 4+0.75×(6−4)=5.54 + 0.75 \times (6 - 4) = 5.54+0.75×(6−4)=5.5
2. **Mediana (Q2):**
   * Posición: (n+1)/2=(10+1)/2=5.5(n+1)/2 = (10+1)/2 = 5.5(n+1)/2=(10+1)/2=5.5
   * Valor: Entre el quinto y el sexto valor: 10+0.5×(12−10)=1110 + 0.5 \times (12 - 10) = 1110+0.5×(12−10)=11
3. **Tercer cuartil (Q3):**
   * Posición: 3(n+1)/4=3×(10+1)/4=8.253(n+1)/4 = 3 \times (10+1)/4 = 8.253(n+1)/4=3×(10+1)/4=8.25
   * Valor: Entre el octavo y el noveno valor: 16+0.25×(18−16)=16.516 + 0.25 \times (18 - 16) = 16.516+0.25×(18−16)=16.5

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

### Medidas de dispersión

Medidas que nos inidican como de lejos o cerca están las observaciones del valor central que hemos calculado, es decir cuánto se alejan de la media o mediana. Nos indican el grado de dispersión de la distribución de frecuencias

#### Recorrido o Rango

Indica la diferencia entre el valor máximo y el valor mínimo en un conjunto de datos

<details>

<summary>Ejemplo: A los enfermeros de un centro de salud se les pregunta por el nº de hijos que tienen. Sus respuestas son: 0,1,2,0,1,1,0,0,2,2,3.  ¿Cuál es su Recorrido?</summary>

Valor máximo = 3

Valor mínimo = 0

Recorrido= 3-0 = 3

</details>

El recorrido es útil cuando se necesita una medida rápida y simple de la dispersión, pero para análisis más detallados y robustos, se utilizan otras medidas de dispersión como la desviación estándar, la varianza o el rango intercuartílico.

#### Rango Intercuatílico (IQR)

Mide la amplitud del 50% central de un conjunto de datos. Se calcula como la diferencia entre el tercer cuartil (Q3) y el primer cuartil (Q1), proporcionando una medida robusta de la variabilidad de los datos al no ser afectada por valores atípicos o extremos

IQR=Q3−Q1

<details>

<summary>Ejemplo: A los enfermeros de un centro de salud se les pregunta por el nº de hijos que tienen. Sus respuestas son: 0,1,2,0,1,1,0,0,2,2,3.  ¿Cuál es su IQR?</summary>

Ordenados: 0,0,0,0,1,1,1,2,2,2,3

Q1 = 0

Q3 = 2

IQR=2-0=2

</details>

#### Varianza&#x20;

Cuantifica cuánto varían los datos entre sí y con respecto a la media del conjunto. Una varianza alta indica que los datos están más dispersos alrededor de la media, mientras que una varianza baja indica que los datos están más agrupados cerca de la media.

$$
s^2 = \frac{\sum_{i=1}^{n} (x_i - \overline{x})^2}{n - 1}
$$

* $$x_i$$​ representa cada valor individual en el conjunto de datos.
* $$\overline{x}$$ es la media de la muestra.
* $$n$$ es el tamaño de la muestra.

**Ejemplo:**

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

* **Varianza alta:** Indica una alta dispersión de los datos respecto a la media.
* **Varianza baja:** Indica que los datos están agrupados cerca de la media.

#### Desviación típica

Es la raíz cuadrada de la varianza y se calcula de la siguiente manera:

$$
s = \sqrt{s^2} =\sqrt{\frac{\sum_{i=1}^{n} (x_i - \overline{x})^2}{n - 1}}
$$

La desviación estándar se interpreta en las mismas unidades que los datos originales, lo que la hace más intuitiva que la varianza. Indica la dispersión promedio de los datos respecto a la media.

<details>

<summary>Ejemplo: A los enfermeros de un centro de salud se les pregunta por el nº de hijos que tienen. Sus respuestas son: 0,1,2,0,1,1,0,0,2,2,3.  ¿Cuál es su varianza y desviación típica?</summary>

$$\overline{x}=1.09$$

desviaciones a la media: $$(0-1.09)^2 = 1.188$$ $$(1-1.09)^2=0.008, (2-1.09)^2=0.8281, (0-1.09)^2 = 1.188,(1-1.09)^2=0.008,(1-1.09)^2=0.008,(0-1.09)^2 = 1.188,(0-1.09)^2 = 1.188,(2-1.09)^2=0.8281,(2-1.09)^2=0.8281,(3-1.09)^2=3.6481$$

Sumar desviaciones: $$1.188+0.008+0.8281+1.188+0.008+0.008+1.188+1.188+0.8281+0.8281+3.6481=10.9084$$

Calcular varianza: $$S^2=\frac{ 10.9084} {11-1}=1.09$$

Calcular desviación típica: $$S=\sqrt{S^2}=\sqrt{1.09}=1.04$$

</details>

#### Coeficiente de variación

Es una medida de dispersión **relativa** que se utiliza para comparar la variabilidad de conjuntos de datos con diferentes unidades o escalas. Se expresa como un porcentaje y se calcula como el cociente entre la desviación estándar y la media, multiplicado por 100:

$$
CV = \left( \frac{s}{\bar{x}} \right) \times 100
$$

Un CV bajo indica que la variabilidad de los datos es baja en relación con su media, mientras que un CV alto indica que la variabilidad es alta en relación con su media.

**Ejemplo**

El peso medio de una población de pacientes de entre 18 y 25 años es de 68,2 kilos con una desviación típica de 3,3 kilos.

El peso medio de una población de bebés menores de seis meses es de 6,5 kilos con una desviación típica de 3,3 kilos

¿En qué población se observa mayor dispersión?

<table><thead><tr><th width="118"></th><th width="141">Media</th><th width="186">Desviación típica</th><th>Coeficiente de Variación</th></tr></thead><tbody><tr><td>Jóvenes</td><td>68.2</td><td>3.3</td><td>4.8%</td></tr><tr><td>Bebés</td><td>6.5</td><td>3.3</td><td>50%</td></tr></tbody></table>

La población de bebés es más dispersa y por tanto más heterogénea ya que el coeficiente de variación es mayor

> <mark style="color:red;">**Ahora es tu turno**</mark>

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

## Gráficos

### V. Cualitativas

**Diagrama de sectores**

Un gráfico de sectores, también conocido como gráfico circular o pie chart en inglés, es una representación visual de datos que muestra la proporción de cada categoría dentro de un conjunto de datos en forma de un círculo dividido en sectores. Cada sector representa una categoría y su tamaño angular es proporcional a la frecuencia o proporción de esa categoría en relación con el total.

<figure><img src="../../.gitbook/assets/image (55).png" alt="" width="563"><figcaption></figcaption></figure>

#### Diagrama de barras

Utiliza barras rectangulares para mostrar la frecuencia, la magnitud o la proporción de diferentes categorías. Cada barra representa una categoría específica y su longitud es proporcional a la cantidad o frecuencia que representa.

También pueden ser útiles para representar variables cuantitativas discretas (Número de hijos)

<figure><img src="../../.gitbook/assets/image (56).png" alt="" width="563"><figcaption></figcaption></figure>

### V. Cuantitativas

#### **Histograma**

Un histograma es una representación gráfica de la distribución de frecuencia de un conjunto de datos numéricos continuos. Consiste en un gráfico de barras donde la base de cada barra representa un intervalo de valores, y la altura de la barra indica la frecuencia o la densidad de datos dentro de ese intervalo.

Los histogramas son especialmente útiles para visualizar la forma y la dispersión de los datos, así como para identificar patrones o tendencias en la distribución de los mismos

<figure><img src="../../.gitbook/assets/image (54).png" alt="" width="563"><figcaption></figcaption></figure>

**Diagrama de cajas**

Un diagrama de cajas, también conocido como boxplot en inglés, es una representación gráfica que proporciona un resumen de varias características importantes de un conjunto de datos numéricos.

El diagrama de cajas muestra la distribución de los datos a lo largo de un eje vertical, dividiendo el conjunto de datos en cuartiles y proporcionando información sobre la dispersión y la simetría de la distribución.

<figure><img src="../../.gitbook/assets/image (57).png" alt="" width="492"><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (58).png" alt="" width="563"><figcaption></figcaption></figure>
