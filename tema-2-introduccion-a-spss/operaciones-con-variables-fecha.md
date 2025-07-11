---
cover: ../.gitbook/assets/images.png
coverY: 0
---

# Operaciones con variables Fecha

Para ilustrar esta parte seguimos trabajando con el fichero <mark style="color:orange;">**primerodatos.sav**</mark>

Las variables con formato **Fecha**, realmente almacenan internamente el número de segundos transcurridos desde una determinada fecha, pero las visualizamos como una fecha porque le hemos dado un formato fecha.&#x20;

Aquí presentamos algunos formatos.

a) Si la fecha es un día, es una variable fecha. (por ejemplo 15.12.03), pero realmente la variable internamente está guardando el número de segundos transcurridos desde el 14 de octubre de 1582 a las 00:00 horas, hasta el 15.12.03 a las 00:00 horas.

b) Si la fecha es una hora, es una variable tiempo (por ejemplo, 13:20:13), pero  realmente la variable internamente está guardando el número de segundos transcurridos desde las 00:00 horas.

Esto hace que podamos hacer operaciones con ellas, como si fueran variables numéricas.&#x20;

En SPSS existe un asistente para hacer operaciones con variables fecha y hora al que se accede en la barra de herramientas **TRANSFORMAR-> Asistente para fecha y hora.**

## Cálculo del tiempo transcurrido entre dos fechas.

Queremos calcular el número de meses entre la primera visita y la segunda visita.&#x20;

**TRANSFORMAR-> Asistente para fecha y hora->**

**“Calcular con fecha y hora”**

**"Calcule el número de unidades de tiempo entre dos fechas"**

<figure><img src="../.gitbook/assets/image (40).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (41).png" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (42).png" alt="" width="563"><figcaption></figcaption></figure>

## Cálculo de la edad.

Es muy frecuente y recomendable tener almacenada la fecha de nacimiento como una variable fecha, y partir de ellas, en cualquier momento poder obtener la edad que el individuo tiene en ese momento.&#x20;

Los pasos que hay que seguir son los mismos que los del apartado anterior, pues hay que calcular el tiempo transcurrido (en años) entre la fecha actual (que el SPSS la tiene guardada en una variable que se llama <mark style="color:purple;">`$TIME`</mark>) y la variable que guarda la fecha de nacimiento.

<figure><img src="../.gitbook/assets/image (43).png" alt="" width="563"><figcaption></figcaption></figure>
