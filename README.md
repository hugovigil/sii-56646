# Sistemas Informáticos Industriales

Mi repo de **Sistemas Informáticos Industriales** 

- **Autor:** Hugo Vigil Velasco
- **Matrícula:** 56646

## Descripción

Es la practica 1 de la asignatura

Juego de tenis en C++ para dos jugadores en el mismo teclado, hecho con OpenGL y GLUT.
En esta práctica se prepara el entorno de desarrollo en Linux (Git, CMake y Make) y se
da movimiento a las raquetas y a la esfera.

## Controles

- Raqueta izquierda: `w` (arriba) y `s` (abajo)
- Raqueta derecha: `o` (arriba) y `l` (abajo)

## Dependencias

Las siguientes dependencias    

sudo apt install g++ git freeglut3-dev cmake mesa-common-dev libglu1-mesa-dev

## Compilación y ejecución

    cd workspace
    mkdir build
    cd build
    cmake ..
    make
    ./tenis


## Práctica 2: comunicación mediante FIFO

Se añade el programa logger, que crea una tubería con nombre (FIFO) y recibe del juego
un mensaje cada vez que un jugador marca un punto. 

El juego y el logger terminan cuando algún jugador alcanza 3 puntos.

Para ejecutarlo, abrir dos terminales en la carpeta workspace/build. 

En la primera se lanza ./logger y en la segunda ./tenis (el logger siempre primero).
