# PPS-Unidad1Actividad2-Angel

Actividad 2 de la Unidad 1 de Puesta en Producción Segura.
Tabajaremos con lenguaje de programación Python y con Jupyter notebook.

Objetivos:
* [Instalar Jupiter](#Instalacion-Jupyter)
* [Aprender a utilizar Jupyter](#Uso-Jupyter)
* [Conocer los elementos y sentencias de Python](#Python) 

---
## Instalacion Jupyter

En [este enlace](https://hub.docker.com/r/dockeruc/eclipse) podemos encontrar información para crear un contenedor docker con un entorno IDE Eclipse.
Es necesario leer bien las instrucciones y tener en cuenta las operaciones que vamos a realizar, a continuación muestro los pasos de un entorno Linux.

1. Instalamos, si no las tenemos, el paquete de python en su versión 3 y ``pip`` que es un gestor de paquetes escritos en python.
~~~
sudo apt-get update
sudo apt install python3
sudo apt install pip
~~~

2. Instalamos Jupyter

~~~
sudo apt install jupyterlab
~~~

## Uso-Jupyter
Para lanzar o ejecutar Jupyter vamos a ejecutar el siguiente comando, el comando abrirá jupyter-lab en un navegador.
~~~
jupyter-lab
~~~

Puedes encontrar más información sobre los primeros pasos de [Jupyter notebook en este vídeo](https://youtu.be/6Vr9ZUntCyE).


## Python

A continuación, listo varios enlaces para aprender python:

> [https://docs.python.org/3.10/contents.html](https://docs.python.org/3.10/contents.html)

> [https://uniwebsidad.com/libros/python/capitulo-2/elementos-del-lenguaje](https://uniwebsidad.com/libros/python/capitulo-2/elementos-del-lenguaje)

> [https://protegermipc.net/2019/05/22/libro-python-basico-para-hackers-y-pentester](https://protegermipc.net/2019/05/22/libro-python-basico-para-hackers-y-pentester)

En el siguiente enlace tienes el Cheatsheet sobre markdown para que lo utilices al documentar tu notebook de Jupyter: [https://www.markdownguide.org/cheat-sheet/](https://www.markdownguide.org/cheat-sheet/). Recuerda que también tienes para ello una sección en el menú de ayuda de Jupyter.

Objetivos: 
> Crea un notebook en Jupyter documentando la creación de un módulo en python que nos defina funciones a la que pasamos dos números enteros y nos devuelve el resultado. Las funciones tendrán los siguientes nombres y calcularán:

  * suma: Suma de dos números.
  * resta; Resta de dos números
  * multiplicacion: Multiplicación de dos números.
  * division: División de dos números.
  * isNumber: Indica si el argumento introducido es un número o no.
  * mayorCero: indica si el número pasado es mayor que cero.

Una vez creadas las funciones:

> Crea en el mismo ``notebook`` programa en Python con nombre mi_modulo.py que nos pida dos números y nos muestre un menú solicitándonos el tipo de operación que queremos realizar: entre suma, resta, multiplicación y división, realice la operación y muestre los resultados. El programa deberá llamar a las funciones que hemos realizado anteriormente.






> Ángel Pérez Blanco
