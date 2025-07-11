---
cover: ../../.gitbook/assets/set-simple-small-game-dice-260nw-2293982075.webp
coverY: 0
---

# Aplicación al diagnóstico clínico

## Prueba diagnóstica

**Diagnóstico clínico**: consiste en decidir qué enfermedad sufre un paciente a partir de una serie de síntomas o a partir de una serie de resultados de unas pruebas clínicas.

Una **prueba diagnóstica** es un procedimiento médico o clínico utilizado para determinar si una persona tiene una enfermedad, condición o trastorno específico. Estas pruebas son esenciales en la práctica médica, ya que proporcionan información objetiva que ayuda a confirmar o descartar un diagnóstico basado en los síntomas, antecedentes médicos y exámenes físicos.

Una buena prueba diagnóstica es la que ofrece resultados **positivos en enfermos** y **negativos en sanos.**

Las condiciones que deben ser exigidas a una prueba diagnóstico son:

1. **Validez**
2. **Seguridad**

La siguiente tabla refleja los resultados posibles de una prueba diagnóstica:&#x20;

<table><thead><tr><th width="248"></th><th>Con enfermedad</th><th>Sin enfermedad</th></tr></thead><tbody><tr><td>Prueba +</td><td><mark style="background-color:green;">Verdadero positivo (VP)</mark></td><td><mark style="background-color:red;">Falso positivo (FP)</mark></td></tr><tr><td>Prueba -</td><td><mark style="background-color:red;">Falso negativo (FN)</mark></td><td><mark style="background-color:green;">Verdadero negativo (VN)</mark></td></tr></tbody></table>

Las pruebas diagnósticas las evaluamos a partir de una prueba de referencia o "gold standard" que es la mejor prueba disponible para diagnosticar una enfermedad o condición. Es considerada el criterio más preciso, confiable y definitivo para determinar si una persona tiene o no una enfermedad. Todas las demás pruebas diagnósticas se comparan con este estándar para evaluar su validez y seguridad

### Validez de una prueba diagnóstica

La **validez** de una prueba diagnóstica se refiere a su capacidad para distinguir de manera precisa entre aquellos que tienen una enfermedad y aquellos que no la tienen. Los dos conceptos clave que se utilizan para evaluar la validez de una prueba diagnóstica son la **sensibilidad** y la **especificidad**.

#### Sensibilidad

La sensibilidad es la capacidad de una prueba diagnóstica para detectar correctamente a las personas que **tienen** la enfermedad. Es decir, mide la proporción de verdaderos positivos (VP) entre todos los que tienen la enfermedad.

$$
Sensibilidad=\frac{VP}{VP+FN}
$$

**Una alta sensibilidad indica que la prueba es efectiva para detectar la enfermedad, minimizando los falsos negativos.**

#### Especificidad

La especificidad es la capacidad de una prueba diagnóstica para identificar correctamente a las personas que **no tienen** la enfermedad. Mide la proporción de verdaderos negativos (VN) entre todos los que no tienen la enfermedad.

$$
Especificidad=\frac{VN}{VN+FP}
$$

**Una alta especificidad indica que la prueba es buena para descartar la enfermedad, minimizando los falsos positivos.**

#### Ejemplo:

Supongamos una prueba para detectar una enfermedad como el COVID-19. Si la prueba tiene una alta **sensibilidad**, significará que la mayoría de las personas infectadas serán correctamente detectadas (pocos falsos negativos). Si tiene una alta **especificidad**, la prueba correctamente descartará a la mayoría de las personas no infectadas (pocos falsos positivos).

#### Balance entre sensibilidad y especificidad:

* En algunas situaciones, es preferible una prueba con alta **sensibilidad**, como en enfermedades graves donde es crucial no dejar pasar ningún caso (ej. cáncer, infecciones altamente contagiosas).
* En otras, es más importante una alta **especificidad**, como en diagnósticos donde un falso positivo puede tener consecuencias psicológicas, económicas o médicas graves (ej. VIH, test de embarazo).

Idealmente, se busca un equilibrio adecuado entre ambos indicadores dependiendo del contexto clínico y del objetivo de la prueba.

### Cálculo de probabilidades (Sensibilidad y Especificidad)

Suceso E: "El paciente padece la enfermedad"

Suceso +: "La prueba da positiva"

$$P(FN) = P(-/E)$$&#x20;

$$P(FP) = P(+/E^c)$$&#x20;

&#x20;$$P(VP)=P(+/E): Sensibilidad$$

&#x20;$$P(VN) = P(-/E^c): Especificidad$$

<mark style="color:orange;">**Ejemplo**</mark>

Para estudiar la eficacia de una nueva prueba para el diagnóstico de un tipo particular de cáncer de mama que lo padece el 1% de las mujeres de edad avanzada, se aplicó el test a:

* un grupo de mujeres con dicho tipo de cáncer de mama
* otro grupo de mujeres sanas

obteniéndose que en el 85% de las primeras y en el 3% de las segundas el test dio positivo.

¿Cuáles son la sensibilidad y la especificidad del test?

1. **Definir los sucesos**

E: "Padecer cáncer"

+: "El test da positivo"

2. **¿Qué hay que calcular?**

Sensibilidad: $$P(+/E)$$&#x20;

Especificidad: $$P(-/E^c)$$

3. **¿Qué sabemos?**

&#x20;$$P(+/E)=0.85$$

&#x20;$$P(+/E^c)=0.03$$

4. **¿Qué nos falta?**

&#x20;$$P(-/E^c)=1-P(+/E^c)=1-0.03=0.97$$

El test detecta el 85% de los cánceres presentes y descarta el 97% de los casos en los que el cáncer no se ha desarrollado.

La especificidad y la sensibilidad son características de las pruebas diagnósticas con las que se evalúan la calidad de estas pruebas. Ahora se quiere medir su **capacidad de predicción**.&#x20;

### Seguridad de una prueba diagnóstica

La **seguridad** de una prueba diagnóstica se refiere a la confianza que se puede tener en los resultados obtenidos por la prueba, es decir, la probabilidad de que los resultados reflejen correctamente la condición de salud del paciente. Esta seguridad se puede evaluar a través de dos medidas complementarias a la sensibilidad y especificidad: los **valores predictivos**. Estos nos indican cuán útiles son los resultados positivos y negativos de la prueba en la práctica clínica.

#### Valor predictivo positivo (VPP)

El **valor predictivo positivo** es la probabilidad de que una persona realmente tenga la enfermedad si el resultado de la prueba es positivo.

$$
VPP=\frac{VP}{VP+FP}
$$

Un VPP alto significa que si la prueba es positiva, es muy probable que la persona esté realmente enferma.

#### Valor predictivo negativo (VPN)

El **valor predictivo nagativo** es la probabilidad de que una persona no tenga la enfermedad si el resultado de la prueba es negativo.

$$
VPN=\frac{VN}{VN+FN}
$$

Un VPN alto indica que si la prueba es negativa, es muy probable que la persona no tenga la enfermedad.

#### Ejemplo:

Imaginemos una prueba con alta sensibilidad para detectar el VIH. Si se realiza en una población con alta prevalencia de la enfermedad, un resultado positivo tendrá un alto **VPP** (es muy probable que la persona esté infectada). En cambio, en una población con baja prevalencia de VIH, un resultado positivo puede tener un menor **VPP**, lo que significa que hay más probabilidades de falsos positivos.

#### Consideraciones sobre la seguridad:

* **Pruebas muy sensibles**: Son preferidas cuando es crítico no dejar escapar ningún caso de la enfermedad, pero pueden generar más falsos positivos, disminuyendo el VPP en poblaciones con baja prevalencia.
* **Pruebas muy específicas**: Son útiles cuando se busca evitar falsos positivos, pero en poblaciones con baja prevalencia podrían generar más falsos negativos.

En resumen, la seguridad de una prueba diagnóstica está relacionada con cuán confiables son sus resultados en un entorno clínico específico, y depende tanto de la prueba en sí como del contexto en el que se utiliza.

### Cálculo de probabilidades (VPP y VPN)

Suceso E: "El paciente padece la enfermedad"

Suceso +: "La prueba da positiva"

&#x20;$$P(VPP)=P(E/+)$$

&#x20;$$P(VPN)=P(E^c/-)$$

Estos valores se pueden obtener a partir de la sensibilidad y la especificidad conocida la prevalencia de la enfermedad a través del [Teorema de Bayes](../calculo-de-probabilidades/#teorema-de-bayes-probabilidad-condicionada).

$$
VPP=P(E/+)=\frac{P(+/E)*P(E)}{P(+/E)*P(E)+P(+/E^c)*P(E^c)}
$$

$$
VPN=P(E^c/-)=\frac{P(-/E^c)*P(E^c)}{P(-/E^c)*P(E^c)+P(-/E)*P(E)}
$$

<mark style="color:orange;">**Ejemplo**</mark>

La prueba de la mamografía para detectar tumores de mama tiene una **sensibilidad del 85%** y una **especificidad del 97%.** La probabilidad de que si una mamografía detecta un tumor, realmente éste exista (valor predictivo positivo) dependerá de la prevalencia del cáncer de mama en la población.

La **prevalencia** es la proporción de individuos de un grupo o población que presentan una característica o evento determinado (enfermedad) en un momento determinado.

La **prevalencia** del cáncer de este tipo de cáncer de mama en mujeres es del **1%**

**Definir sucesos**

E: "Padecer cáncer de mama"

+:"El test es positivos"

**¿Qué sabemos?**

&#x20;$$Prevalencia = P(E)=0.01$$

&#x20;$$Sensibilidad=P(+/E)=0.85$$

&#x20;$$Especificidad = P(-/E^c)=0.97$$

**¿Qué hay que calcular?**

&#x20; $$VPP=P(E/+)=\frac{P(+/E)*P(E)}{P(+/E)*P(E)+P(+/E^c)*P(E^c)}=\frac{0.85*0.01}{0.85*0.01+(1-0.97)*(1-0.01)}=0.2225$$

$$VPN=P(E^c/-)=\frac{P(-/E^c)*P(E^c)}{P(-/E^c)*P(E^c)+P(-/E)*P(E)}=\frac{0.97*(1-0.01)}{0.97*(1-0.01)+(1-0.85)*0.01}=0.9984$$$$0$$

El VPP nos indica que el 77.75% de diagnósticos positivos son erróneos y el VPN nos indica que el 0.16% de diagnósticos negativos son erróneos.

En este contexto es importante asegurarse de que, si se le dice a una paciente que está sana, realmente lo esté: **alto valor predictivo negativo**. Sin embargo, no es tan preocupante pronosticar que padece el cáncer y luego que no sea cierto (**diagnóstico positivo erróneos**): el médico en este caso no informará a la paciente de que su test dio positivo sino que le realizará un estudio más profundo para confirmarlo.

Por tanto, **este test es útil para descartar cáncer pero no para confirmarlo**.

