# gelvez-post1-u4

## Descripción
Laboratorio 1 de la Unidad 4: Primer programa NASM con segmentos y salida DOS.

## Prerrequisitos
- DOSBox 0.74+
- NASM 2.14+
- ALINK

## Compilación y ejecución
1. nasm -f obj programa.asm -o programa.obj
2. alink programa.obj -oEXE -o programa.exe -entry main

Ejecutar programa.exe dentro de DOSBox.