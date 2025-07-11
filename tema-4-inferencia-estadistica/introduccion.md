---
cover: ../.gitbook/assets/desktop_fcdfecd9-6366-44d5-a06e-d679e9d12920.jpg
coverY: 254.84799999999998
---

# Introducción

## Inferencia estadística

La **inferencia estadística** es una rama de la estadística que permite hacer generalizaciones o deducciones sobre una población a partir de una muestra representativa. A diferencia de la estadística descriptiva, que se limita a describir y resumir datos, la inferencia estadística busca llegar a conclusiones sobre datos no observados.

<figure><img src="../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>



<mark style="color:orange;">**Ejemplo**</mark>

En este diagrama de dispersión vemos las variables longitud del fémur y peso de 40 fetos de 26 semanas

<figure><img src="../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

Con la estadística descriptiva hemos visto una correlación directa entre ambas variables (**r = 0.802**)

¿En qué medida lo observado en la muestra puede generalizarse a la población?

Debemos decidir si la correlación observada en la muestra es clara, es decir, **significativa**, o si por el contrario es el azar y para ello determinaremos un margen de error.

Las técnica estadísticas inferenciales consiguen extrapolar los resultados obtenidos de la muestra, a toda la población, cuantificando el error de precisión.

**Problema**: el hecho de que en una muestra concreta apreciemos una correlación, no debe hacernos descartar que si la reemplazamos por otra, nuestra conclusión sea otra (variabilidad entre muestras).

## Principales conceptos en inferencia estadística

### **Población y muestra**:

**Población**: el conjunto completo de todos los elementos que queremos estudiar. Ejemplo: todos los estudiantes de una universidad.

**Muestra**: un subconjunto de la población. Ejemplo: un grupo aleatorio de 200 estudiantes seleccionados de la universidad.

### **Parámetro y estadístico**:

**Parámetro**: un valor numérico que describe una característica de la población, como la media (μ) o la desviación estándar (σ).

**Estadístico**: un valor calculado a partir de una muestra, como la media muestral ( $$\bar{x}$$) o la desviación estándar muestral (s).

Todos los parámetros estudiados hasta ahora (media, varianza, desviación típica, etc) los hemos estudiado a partir de una **muestra** de tamaño **n** que pueden estudiarse teóricamente a partir de todos los valores de la población.

Decimos teóricamente, porque en la práctica no los podemos calcular. Por tanto, distinguiremos los parámetros poblacionales y muestrales:

<figure><img src="../.gitbook/assets/image (153).png" alt="" width="563"><figcaption></figcaption></figure>

### **Estimación**:

* **Estimación puntual**: calcular un solo valor para estimar un parámetro de la población. Por ejemplo, usar la media muestral para estimar la media poblacional.
* **Estimación por intervalos (intervalo de confianza)**: proporciona un rango de valores en los que es probable que se encuentre el parámetro poblacional. Ejemplo: un intervalo de confianza del 95% para la media poblacional.
* **Contraste de hipótesis**:
  * Este proceso consiste en formular una **hipótesis nula** ( $$H_0$$​) y una **hipótesis alternativa** ( $$H_1$$​), y luego usar datos muestrales para decidir si se rechaza o no la hipótesis nula.
  * Se basa en conceptos como el **nivel de significancia** ( $$\alpha$$) y el **p-valor**.

## Objetivos más frecuentes en una investigación clínica

### Problemas de estimación mediante intervalo de confianza

* Evaluar un porcentaje o proporción: **P**&#x20;
  * donde la variable principal X es cualitativa o categórica
* Evaluar una media: $$\mu$$
  * donde la variable principal X es cuantitativa

### Problemas de contraste de hipótesis

* Comparar dos proporciones (P1=P2)&#x20;
  * Variable principal X cualitativa medida en dos subpoblaciones   (hombres y mujeres)
* Comparar dos medias ( $$\mu_1 = \mu_2$$)  &#x20;
  * Variable principal X cuantitativa medida en dos subpoblaciones (hombres y mujeres)
