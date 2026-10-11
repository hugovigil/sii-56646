# Sistemas Informáticos Industriales - Práctica 1

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
