# Foreword in English

The following code is in Spanish because it's part of a practice I did at University, so it's full of comments.
It has an educative purpose.

# Introducción

* La práctica se va a implementar en Java 2 Estándar Edition (J2SE).
* El alumno deberá implementar una interfaz gráfica en Swing que permita interactuar con el juego a partir de las clases y la lógica definida. No es necesario hacer  uso de hilos para implementar la práctica.
* La clase principal que abre la aplicación deberá llamarse "Tetris.class".

# Mecánica del juego

Distintos tetriminos, figuras geométricas compuestas por cuatro bloques cuadrados unidos de forma ortogonal, caen de la parte superior de la pantalla. El jugador no puede impedir esta caída pero puede decidir la rotación de la pieza (0°, 90°, 180°, 270°) y en qué lugar debe caer. Cuando una línea horizontal se completa, esa línea desaparece y todas las piezas que están por encima descienden una posición, liberando espacio de juego y por tanto facilitando la tarea de situar nuevas piezas. La caída de las piezas se acelera progresivamente. El juego acaba cuando las piezas se amontonan hasta salir del área de juego.

* La pantalla está formada por 25 líneas (contadas desde la parte inferior a la parte superior).
* Puesto que las piezas caen de la zona superior, y aparecen inicialmente en el formato que se muestra en la figura, el área de juego efectivo son 23 líneas (restando dos líneas por la colocación inicial de las piezas).
* El ancho de la pantalla será de 12 casillas.
* Una pieza nueva no aparece hasta que no ha caído otra.
* No se produce aceleración en la caída de piezas a lo largo del juego. Éstas caerán una velocidad de 1 fila por segundo, de tal manera que una pieza tarda 23 segundos en caer desde la parte superior a la inferior, si no se producen rotaciones.
* Como máximo el juego deja hacer cuatro rotaciones por segundo.
* Las piezas se desplazarán a derecha e izquierda con los cursores, y rotarán sólo en un sentido (en el de las agujas del reloj), mediante la flecha superior de los cursores.
* No se habilitará la opción de dejar caer la pieza como ocurre en el juego original
* No se establecerá sistema de puntuaciones
* No se establecerán niveles diferentes en el juego.
* Las piezas siempre aparecen por la parte central del tablero.