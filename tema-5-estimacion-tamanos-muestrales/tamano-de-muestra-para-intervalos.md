# Tamaño de muestra para intervalos

## Estimación de porcentaje

<figure><img src="../.gitbook/assets/image (171).png" alt="" width="563"><figcaption></figcaption></figure>

Por tanto, se necesitan cuatro cosas:

1. **Nivel confianza** $$\alpha$$**:** Al igual que para el cálculo de los IC, solemos usar un $$\alpha=0.05$$
2. **Precisión deseada** (amplitud del IC): La precisión vendrá guiada por:
   1. &#x20;La importancia del resultado en tu estudio&#x20;
   2. Recursos disponibles y viabilidad de la recolección de datos
   3. Estudios previos en el área&#x20;

<mark style="color:orange;">**Ejemplo**</mark>: al estudiar la prevalencia de una enfermedad, un margen de error del 5% podría ser aceptable, pero al evaluar un tratamiento crítico, podría requerirse una precisión del 1-2%.&#x20;

Una mayor precisión implica un tamaño muestral más grande, lo que puede requerir más tiempo, dinero y esfuerzo. Un margen de error de **±5%** es común para estudios descriptivos generales, mientras que valores más pequeños (1−2%) se usan en investigaciones más críticas o con altos estándares de precisión.

3. **Valor del porcentaje a estimar (p)**: La proporción o porcentaje se coge de estudios previos, cuando es desconocida, simplemente se coge 0.5 ya que maximiza el término  $$p(1-p)$$.&#x20;

<figure><img src="../.gitbook/assets/image (8).png" alt="" width="563"><figcaption></figcaption></figure>

Elegir p = 0.5 es una decisión muy conservadora, siempre se intentará saber por estudios previos esta información.

4. **Porcentaje esperable de pérdidas:** Es común anticipar que no todos los participantes completarán el estudio, por lo que se calcula un tamaño muestral inicial ajustado para compensar estas pérdidas.



**Se necesitará más tamaño muestral cuanto:**&#x20;

* mayor sea el nivel de confianza deseado
* más se acerque el valor del porcentaje al 50%
* menor se fije el margen de error

### <mark style="color:orange;">**Ejemplo**</mark>

**Objetivo**

Se pretende estimar el porcentaje de recaídas a los seis meses en pacientes recuperados de un episodio severo de depresión

**Información**

Se quiere una muestra para estimar dicha proporción con una precisión del 3% y con un nivel de significación de 5%. Se sabe por estudios anteriores que la proporción _p_ es de aproximadamente un 50% y se asume un 1% de pacientes no evaluables.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

## Estimación de media

<figure><img src="../.gitbook/assets/image (11).png" alt="" width="563"><figcaption></figcaption></figure>

En este caso, la diferencia es que en vex de la proporción, necestimos la desviación típica:

1. **Nivel confianza** $$\alpha$$
2. **Precisión deseada**
3. **Desviación estándar:** Normalmente, usaremos valores de σ reportados en estudios similares realizados previamente en la misma población o contexto. En el caso de no disponer de esta información, podemos contemplar varias posibilidades:
   1. Si estás investigando un parámetro común en ciencias de la salud (como presión arterial, peso, etc.), es probable que existan valores de referencia. **Por ejemplo:** Si estudios previos muestran que la desviación estándar de la presión arterial sistólica es σ=12 mmHg, utiliza ese valor para el cálculo.
   2. También se puede realizar un **estudio piloto** con una muestra pequeña para obtener una estimación preliminar de σ.
   3. Si no hay estudios previos ni posibilidad de realizar un piloto, se puede hacer una **estimación conservadora**: Usa un rango esperado de valores para la población y asume que σ es aproximadamente **una cuarta parte del rango**. Ejemplo:  Si se espera que la presión arterial sistólica varíe entre 90 y 150 mmHg: $$\sigma \approx \frac{150 - 90}{4} = 15$$
   4. Algunas disciplinas o estudios específicos pueden tener guías que sugieren valores estándar para σ. Por ejemplo, en ensayos clínicos.
4. **Porcentaje esperable de pérdidas**

### <mark style="color:orange;">Ejemplo</mark>

**Objetivo**

Se pretende estimar la estatura media de las niñas de 10 a 12 años en las consultas de atención primaria en la C. A. de Madrid

**Información**

Se quiere estimar la estatura media con una precisión de 1 cm y con un nivel de significación de 5%. Además, por estudios previos se sabe que la desviación estándar de la altura es 5 cm.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

