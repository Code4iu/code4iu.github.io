---
title: Inicio del Blog
pubished: true
---

Este será un Blog dirigido a la progrmación en `c/c++` ademas de incluir una seccion de `LaTeX`.

Los ejercicios estaran escritos como a continuacion se presentan:

> Ejecutar el siguiente código fuente (Declarando _valor_logico_  como entero y
> luego declarándolo como _float_):

```c
#include <stdio.h>
#include <stdlib.h>

//int valor_logico;
float valor_logico;
int main()
{
    printf("-------------------------------------------------------------------------- \n");
    printf("                               EJERCICIO 1\n");
    printf("          Correrer el codigo y despues modificar el tipo de variable\n\n");
    printf("Valores logicos de las siguientes expresiones\n");
    valor_logico=(3>5);
    printf(" (3>5) es %d\n",valor_logico);
    valor_logico=(5>3);
    printf(" (5>3) es %d\n",valor_logico);
    valor_logico=(15>3*5);
    printf(" (15>3*5) es %d\n",valor_logico);
    valor_logico=!(5==3);
    printf("!(5==3) es %d\n",valor_logico);


    printf("\n--------------------------------HERGOD-------------------------------------\n");
    return 0;
}

```
