# 📚 Operaciones con Listas Enlazadas en C

Este programa implementa una **lista enlazada simple** en lenguaje
**C**, permitiendo realizar diversas operaciones como inserción,
eliminación, impresión y ordenamiento de elementos.

El sistema funciona mediante un **menú interactivo en consola**, donde
el usuario puede gestionar dinámicamente los nodos de la lista.

------------------------------------------------------------------------

## 🧠 Descripción

La estructura principal utilizada es un **nodo**, el cual contiene:

-   Un dato de tipo `char`
-   Un apuntador al siguiente nodo

El programa permite manipular la lista enlazada mediante diferentes
operaciones seleccionadas por el usuario.

------------------------------------------------------------------------

## ⚙️ Funcionalidades

Las operaciones disponibles son:

### ➕ Inserción

1.  Insertar al frente
2.  Insertar al final
3.  Insertar en una posición intermedia

### ➖ Eliminación

4.  Eliminar al frente
5.  Eliminar al final
6.  Eliminar en una posición intermedia

### 🔄 Ordenamiento

7.  Ordenar en forma ascendente
8.  Ordenar en forma descendente

### 👁️ Visualización

9.  Imprimir la lista completa

### 🚪 Salida

0.  Salir del programa

------------------------------------------------------------------------

## 🏗️ Estructura del Proyecto

    listas_operaciones.c

------------------------------------------------------------------------

## 🧾 Estructura del Nodo

``` c
typedef struct nodo
{
    char dato;
    struct nodo *siguiente;
} NODO;
```

------------------------------------------------------------------------

## 💻 Requisitos

-   Compilador de C (GCC recomendado)
-   Sistema operativo Windows / Linux
-   Consola o terminal

------------------------------------------------------------------------

## ▶️ Compilación

Usando **GCC**:

``` bash
gcc listas_operaciones.c -o listas_operaciones
```

------------------------------------------------------------------------

## ▶️ Ejecución

En Windows:

``` bash
listas_operaciones.exe
```

En Linux:

``` bash
./listas_operaciones
```

------------------------------------------------------------------------

## 🖥️ Ejemplo de Uso

El programa mostrará un menú como el siguiente:

    OPERACIONES CON LISTAS ENCADENADAS

    1. Insertar frente
    2. Insertar final
    3. Insertar en medio
    4. Borrar frente
    5. Borrar final
    6. Borrar en medio
    7. Ordenar ascendente
    8. Ordenar descendente
    9. Imprimir lista
    0. Salir

------------------------------------------------------------------------

## 🎯 Objetivo Académico

Este programa fue desarrollado con fines educativos para:

-   Comprender listas enlazadas
-   Practicar el uso de punteros
-   Implementar estructuras dinámicas
-   Manipular memoria dinámica (`malloc` y `free`)

------------------------------------------------------------------------

## 📖 Conceptos Aplicados

-   Estructuras (`struct`)
-   Punteros
-   Memoria dinámica
-   Listas enlazadas simples
-   Funciones
-   Menú interactivo

------------------------------------------------------------------------

## 👨‍💻 Autores

-   Jose Santiago Castro Reyes 2148314
-   Sebastian Calderon Carrillo 2087472

------------------------------------------------------------------------

## 📜 Licencia

Uso libre para fines educativos.
