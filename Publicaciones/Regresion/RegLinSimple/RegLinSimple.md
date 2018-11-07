
<hr>

<img src="https://raw.githubusercontent.com/fhernanb/fhernanb.github.io/master/imagenes/logounal.png" alt="logounal" width="200">

<hr>

Introducción
------------

En esta publicación se mostrará como usar las herramientas de R para ajustar un modelo de regresión lineal simple.

Modelo estadístico
------------------

El modelo estadístico en regresión lineal simple se puede escribir de dos formas como se muestra a continuación.

-   Modelo 1: en esta forma la variable respuesta *y* se expresa como una suma de *β*<sub>0</sub> + *β*<sub>1</sub>*x*<sub>*i*</sub> y un error aleatorio *e*<sub>*i*</sub> el cual tiene distribución *N*(0, *σ*<sup>2</sup>).
-   Modelo 2: en esta forma la variable respuesta *y* tiene distribución *N*(*β*<sub>0</sub> + *β*<sub>1</sub>*x*<sub>*i*</sub>, *σ*<sup>2</sup>).

En cualquiera de los dos casos anteriores el vector de parámetros del modelo es **θ** = (*β*<sub>0</sub>, *β*<sub>1</sub>, *σ*)<sup>⊤</sup>.

Datos para el ejemplo
=====================

Para el ejemplo vamos a utilizar los datos disponibles en el objeto `softdrink` del paquete `MPV` que acompaña al libro [Introduction to Linear Regression Analysis](https://www.amazon.com/Introduction-Regression-Analysis-Douglas-Montgomery/dp/0470542810/ref=sr_1_1?s=books&ie=UTF8&qid=1513908927&sr=1-1&refinements=p_27%3AMontgomery+%2F+Peck+%2F+Vining).

Los datos `softdrink` corresponden al tiempo (*y*) que un empleado demora para revisar y surtir una máquina dispensadora en función de la cantidad de cajas (*x*) que surte a la máquina, abajo una figura ilustrativa de la situación.

<hr>
<p align="center"> Fin </p>
