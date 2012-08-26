# Foreword in English

The following code is in Spanish because it's part of a practice I did at University, so it's full of comments.
It has an educative purpose.

# Introducci�n

* La pr�ctica se va a implementar en Java 2 Est�ndar Edition (J2SE).
* El alumno deber� implementar una interfaz gr�fica en Swing que permita interactuar con el juego a partir de las clases y la l�gica definida. No es necesario hacer  uso de hilos para implementar la pr�ctica.
* La clase principal que abre la aplicaci�n deber� llamarse "Tetris.class".

# Mec�nica del juego

Distintos tetriminos, figuras geom�tricas compuestas por cuatro bloques cuadrados unidos de forma ortogonal, caen de la parte superior de la pantalla. El jugador no puede impedir esta ca�da pero puede decidir la rotaci�n de la pieza (0�, 90�, 180�, 270�) y en qu� lugar debe caer. Cuando una l�nea horizontal se completa, esa l�nea desaparece y todas las piezas que est�n por encima descienden una posici�n, liberando espacio de juego y por tanto facilitando la tarea de situar nuevas piezas. La ca�da de las piezas se acelera progresivamente. El juego acaba cuando las piezas se amontonan hasta salir del �rea de juego.

* La pantalla est� formada por 25 l�neas (contadas desde la parte inferior a la parte superior).
* Puesto que las piezas caen de la zona superior, y aparecen inicialmente en el formato que se muestra en la figura, el �rea de juego efectivo son 23 l�neas (restando dos l�neas por la colocaci�n inicial de las piezas).
* El ancho de la pantalla ser� de 12 casillas.
* Una pieza nueva no aparece hasta que no ha ca�do otra.
* No se produce aceleraci�n en la ca�da de piezas a lo largo del juego. �stas caer�n una velocidad de 1 fila por segundo, de tal manera que una pieza tarda 23 segundos en caer desde la parte superior a la inferior, si no se producen rotaciones.
* Como m�ximo el juego deja hacer cuatro rotaciones por segundo.
* Las piezas se desplazar�n a derecha e izquierda con los cursores, y rotar�n s�lo en un sentido (en el de las agujas del reloj), mediante la flecha superior de los cursores.
* No se habilitar� la opci�n de dejar caer la pieza como ocurre en el juego original
* No se establecer� sistema de puntuaciones
* No se establecer�n niveles diferentes en el juego.
* Las piezas siempre aparecen por la parte central del tablero.