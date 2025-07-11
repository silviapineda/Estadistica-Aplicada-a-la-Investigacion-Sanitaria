---
cover: ../.gitbook/assets/set-simple-small-game-dice-260nw-2293982075.webp
coverY: -54.27205882352941
---

# Concepto de probabilidad

La probabilidad la definimos como el valor numérico que mide la posibilidad de que ocurra un evento o suceso.

La probabilidad de un evento se expresa como un número entre 0 y 1, donde 0 indica la imposibilidad del evento y 1 indica la certeza del evento.

* Si el suceso ocurre seguro -> Su probabilidad es 1
* Si el suceso No ocurre seguro -> Su probabilidad es 0
* Si el suceso puede que ocurra o que no -> Su probabilidad está entre 0 y 1

## Ejemplos

<table><thead><tr><th width="465">Sucesos</th><th>Probabilidad</th></tr></thead><tbody><tr><td>Obtener un nº mayor que 6 al lanzar un dado</td><td>0</td></tr><tr><td>Extraer un basto en una baraja</td><td>1/4 = 0.25</td></tr><tr><td>Caer con la punta hacia arriba al lanzar una chincheta</td><td>¿?</td></tr><tr><td>Que exista alguna complicación al realizar una transfusión de sangre</td><td>¿?</td></tr><tr><td>Que una infección remita con un antibiótico</td><td>¿?</td></tr></tbody></table>



## Conceptos Clave de la probabilidad

### Experimento aleatorio

Es un proceso o acción que se puede repetir indefinidamente bajo condiciones uniformes y cuyo resultado no puede predecirse con certeza antes de realizar el experimento.

**Ejemplo 1:** Lanzar un dado

### Espacio muestral $$\Omega$$

El conjunto de todos los resultados posibles de un experimento aleatorio.

**Ejemplo**: Al lanzar un dado, el espacio muestral es {1, 2, 3, 4, 5, 6}.

### Suceso o Evento

Un subconjunto del espacio muestral. Es uno o más resultados posibles.

**Ejemplo**: Al lanzar un dado, el evento A puede ser obtener un número par, es decir, A = {2, 4, 6}.

<details>

<summary>Describe el experimento aleatorio, espacio muestral y un posible suceso de lanzar dos monedas</summary>

**Experimento aleatorio**: lanzar dos monedas

**Espacio muestral**: {CX,CC,XC,XX}

**Suceso**: A: No salir ninguna cara = {XX}&#x20;

&#x20;               B: Salir por lo menos una cara = {CX, XX, XC}

</details>

<details>

<summary>Descibre el experimento aleatorio, espacio muestral y un posible suceso de una mujer portadora de hemofilia que tiene tres hijos</summary>

**Experimento aleatorio**: Determinación de los 3 hijos respecto a la enfermedad

**Espacio muestral**: {HHH, HHnH, HnHH, nHHH, nHnHH, nHHnH, HnHnH, nHnHnH}

**Sucesos**: A: Dos hijos son hemofílicos = {HHnH, HnHH, nHHH}.&#x20;

&#x20;                B: El mayor es hemofílico = {HnHnH, HnHH, HHnH, HHH}

</details>

## Conjuntos

Si consideramos el espacio muestral como el **conjunto universal**, es decir, incluye todos los posibles resultados de un experimento aleatorio y un **suceso**, como un subconjunto del espacio muestral que representa un grupo de resultados específicos. Podemos definir:

**Conjunto vacío** $$\emptyset$$**:** conjunto que no contiene ningún elemento

**Conjunto universal** $$\Omega$$: conjunto que contiene a todos los elementos

**Conjunto complementario de**  $$A (A^c)$$**:** conjunto que contiene a todos los elementos que no tiene A

**B incluido en A** $$(B \subseteq A)$$**:** Todos los elementos de B están en A

**Conjuntos disjuntos o incompatibles**: no tienen ningún elemento en común

**La unión de A y B** $$(A \cup B)$$**:** conjunto formado por los elementos que están en A o están en B

**La intersección de A y B** $$(A \cap B)$$: conjunto que contiene a todos los elementos que están en A y también en B

### Ejemplo

**Experimento aleatotorio**: Observación del número de hijos hemofílicos de los tres hijos nacidos de una mujer hemofílica

&#x20; <mark style="color:orange;">**SUCESO A**</mark>: “Más de uno hemofílico” =  {2,3}

&#x20; <mark style="color:green;">**SUCESO B**</mark><mark style="color:purple;">**:**</mark> “Menos de tres hemofílicos”= {0,1,2}

&#x20; <mark style="color:red;">**SUCESO C:**</mark> “Uno o menos”= {0,1}

**Conjunto universal**: {0,1,2,3}

**Complementario de** $$A (A^c)$$**:** {0,1} = “1 ó menos” = C

$$A \cup B$$: {0,1,2,3} = “Más de 1 ó menos de 3”

$$A \cap B:$${2}=“Más de 1 y menos de 3”

$$A \cap C$$: $$\emptyset$$

<figure><img src="../.gitbook/assets/image (24).png" alt="" width="318"><figcaption></figcaption></figure>

C está incluido en B $$(C \subseteq B)$$

La unión de B y C $$(B \cup C)$$ es B

La unión de A y B es $$\Omega$$

La intersección de A y B $$(A \cap B)$$es {2}

A y C son disjuntos

C es el complementaiuo de A

### Propiedades de los conjuntos

Considera la probabilidad de un suceso como la medida del conjunto cumpliendo ciertas propiedades denominados axiomas.

<mark style="color:orange;">**AXIOMA 1**</mark><mark style="color:orange;">:</mark> $$P(A) \geq 0$$&#x20;

La probabilidad de un suceso siempre es no negativa (Un conjunto no puede medir negativo: o mide algo o no mide nada)

<mark style="color:orange;">**AXIOMA 2**</mark>: $$P(\Omega)=1$$

La probabilidad del suceso seguro es 1 (la escala de medida de conjunto está entre 0 y 1)

<mark style="color:orange;">**AXIOMA 3**</mark>: $$P(A_1 \cup A_2 \cup A_3 \cup ...)=P(A_1)+P(A_2)+P(A_3)+...$$

$$
A_i \cap A_j = \emptyset
$$

La probabilidad de la unión de sucesos disjuntos es la suma de las probabilidades de los sucesos (Lo que mide la unión de conjuntos se calcula sumando lo que mide cada uno, siempre que no tengan nada en común)

### Propiedades de la probabilidad:

Las propiedades fundamentales de la probabilidad que nos van a permitir hacer cálculo de probabilidades son las siguientes:

#### 1. No Negatividad

Para cualquier suceso A, la probabilidad de A es siempre mayor o igual a cero.&#x20;

$$
P(A)\geq 0
$$

#### 2. Normalización

La probabilidad del conjunto universal es igual a 1 y la probabilidad del conjunto vacío es igual a 0.&#x20;

$$
P(\Omega)=1
$$

$$
P(\emptyset)=0
$$

#### 3. Contención

Si $$A \subseteq B$$, entonces la probabilidad de A es menor o igual a la probabilidad de B.

$$
P(A) \leq P(B)
$$

#### 3. Aditividad

Para dos sucesos A y B, la probabilidad de la unión de A y B es igual a la suma de sus probabilidades menos su intersección:

$$
P(A \cup B) = P(A) + P(B)-P(A \cap B)
$$

excepto si estos dos sucesos son mutuamente excluyentes (es decir, $$A \cap B = \emptyset$$), que la probabilidad de la unión de A y B es igual a la suma de las probabilidades de A y B.&#x20;

$$
P(A \cup B) = P(A) + P(B)
$$

#### 5. Complementariedad

La probabilidad de que un suceso A no ocurra es igual a uno menos la probabilidad de que A ocurra.&#x20;

$$
P(A^c) = 1 - P(A)
$$

Donde $$A^c$$ es el complemento de A.

#### 6. Regla del Producto (Probabilidad Condicional)

Para dos sucesos A y B, la probabilidad de $$A \cap B$$(la intersección de A y B) es igual a la probabilidad de A multiplicada por la probabilidad de B dado A.

$$
P(A \cap B) = P(A) \cdot P(B|A)
$$

Donde $$P(B|A)$$es la probabilidad de B dado que A ha ocurrido.

#### 7. Independencia

Dos eventos A y B son independientes si y solo si la probabilidad de $$A \cap B$$ es igual al producto de las probabilidades de A y B.

$$
P(A \cap B) = P(A) \cdot P(B)
$$

### Ejemplo

Un 15% de los pacientes atendidos en un servicio clínico de digestivo son hipertensos, un 30% son fumadores y un 10% son hipertensos y fumadores.

Elegido un paciente al azar, ¿cuál es la probabilidad de que sea hipertenso o sea fumador?

Suceso A: "El paciente es hipertenso"  $$P(A)=0.15$$

Suceso B: "El paciente es fumador" $$P(B) = 0.30$$

La interacción entre ser hipertenso y fumador es: $$P(A\cap B) = 0.10$$

Hay que calcular la probabilidad de que sea hipertenso o fumador por tanto, nos piden la unión de los dos sucesos A y B:&#x20;

$$
P(A\cup B)
$$

$$
P(A \cup B) = P(A) + P(B)-P(A \cap B)=0.15+0.30-0.10=0.35
$$
