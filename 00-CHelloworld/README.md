Info compilador
gcc (MinGW-W64 x86_64-ucrt-posix-seh, built by Brecht Sanders, r5) 13.2.0
Copyright (C) 2023 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

Compilado con -std=gnu17
Standard C utilizado por defecto según https://gcc.gnu.org/onlinedocs/gcc-13.2.0/gcc/Standards.html
"The default, if no C language dialect options are given, is -std=gnu17."

Pasos para realizar el TP0, se realizó la descarga del compilador gcc utilizando el proyecto MinGW-W64
Se extrajo el compilador en el disco C:\ para luego generar una variable de entorno
Para realizar la compilación se utilizó:
1-gcc hello.c -o hello.exe
2-hello.exe > output.txt

Observación: Por defecto el compilador utiliza standard gnu17, esta opción puede modificarse para utilizar otro standard al momento de compilación

Un ejemplo seria: gcc hello.c -std=c2x -o stdC2x.exe