---
cover: ../.gitbook/assets/images.png
coverY: 0
---

# Edición de ficheros de datos

Para ilustrar esta parte vamos a utilizar el fichero <mark style="color:orange;">**primerodatos.sav**</mark>

{% file src="../.gitbook/assets/primerosdatos.sav" %}

En este fichero tenemos informacion de 11 individuos que acudieron a una óptica y se guardaron 5 variables &#x20;

<figure><img src="../.gitbook/assets/image (32).png" alt="" width="563"><figcaption></figcaption></figure>

Por edición de ficheros de datos se entiende modificar en algún sentido el fichero de datos existente. Estas modificaciones pueden consistir en suprimir alguna observación, suprimir alguna variable, añadir una nueva variable a partir de las ya existentes en el fichero, ordenar los datos por orden alfabético, recodificar variables, etc.&#x20;

La mayoría de estas operaciones pueden llevarse a cabo seleccionando en la Barra de Menús, las opciones **DATOS** o **TRANSFORMAR**. A continuación, mostramos cómo se realizan las modificaciones más frecuentes e importantes.

## Crear una variable a partir de otra

Vamos a crear una nueva variable que se llame <mark style="color:purple;">`edadlentesdias`</mark> cque guarde la edad que iniciaron con lentes en días, para ello deberíamos multiplicar la variable <mark style="color:purple;">`edadlentes`</mark> \* 365

En la barra de menus **TRANSFORMAR->Calcular variable...**

<figure><img src="../.gitbook/assets/image (33).png" alt="" width="563"><figcaption></figcaption></figure>



## Recodificar variables

Supongamos que queremos crear una nueva variable a partir de otra, de manera que sus valores sean codificaciones de los valores de esta última. Por ejemplo, vamos a crear una variable que llamaremos <mark style="color:purple;">`casado`</mark>, que tome el valor 1 si la persona está casada y 0 si no lo es. Entonces, esta variable es una codificación de la variable ya existente <mark style="color:purple;">`e_civil`</mark>.

en la Barra de Menús **TRANSFORMAR->Recodificar en distintas variables…**

<figure><img src="../.gitbook/assets/image (34).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (35).png" alt="" width="563"><figcaption></figcaption></figure>

En muchas ocasiones es muy útil dar **etiquetas** a los valores de las variables, que expliquen qué categoría está representando cada valor.&#x20;

Por ejemplo, vamos a especificar etiquetas a los valores de la nueva variable <mark style="color:purple;">`casado`</mark> indicando que el valor 1 representa a los casados y el 0 a los no casados.&#x20;

Para ello en la ventana de **Vista de Variables**, pinchamos en el campo _**Valores**_ de la variable <mark style="color:purple;">`casado`</mark> apareciendo la siguiente ventana, donde vamos metiendo en el campo **Valor**: el valor de la variable (por ejemplo, 1) y en el campo **Etiqueta de valor**, la etiqueta que se quiere dar a este valor (en nuestro caso Casado). Pulsando en Añadir, repetimos la operación con el resto de los valores y de las etiquetas.

<figure><img src="../.gitbook/assets/image (36).png" alt="" width="563"><figcaption></figcaption></figure>



## Seleccionar sólo algunas observaciones (filas)

Es frecuente que en cierto análisis tengamos la necesidad de trabajar no con todos los datos sino sólo con algunos, que cumplan cierta condición. Para ello, previamente a realizar el análisis se debe proceder a seleccionar aquellos casos de interés.&#x20;

**Ejemplo**: supongamos que sólo queremos trabajar con aquellos individuos que no estén casados.

En la Barra de Menús **DATOS->Seleccionar casos**.

<figure><img src="../.gitbook/assets/image (39).png" alt="" width="563"><figcaption></figcaption></figure>

Después de indicar la condición y de pinchar en Continuar, en el Editor de Datos aparecerán tachados en el margen izquierda aquellas filas que no cumplen la condición especificada y, por tanto, aquellos datos que no se utilizarán en un posterior análisis (así podremos comprobar si nuestra selección corresponde con la que queríamos hacer).&#x20;

Observar que el programa ha creado una variable automáticamente con el nombre de <mark style="color:purple;">`filter_$`</mark> que toma el valor 0 si el dato no ha sido seleccionado y 1 si sí lo ha sido.

{% hint style="info" %}
**Importante** quitar la opción si se quiere seguir trabajando con el fichero completo.
{% endhint %}
