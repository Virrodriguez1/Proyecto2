cmake_minimum_required(VERSION 3.24)
project(Proyecto_2)

set(CMAKE_CXX_STANDARD 14)

include_directories(Proyecto2)

add_executable(Proyecto_2
        Proyecto2/ArbolBinario.h
        Proyecto2/Articulo.h
        Proyecto2/Cola.h
        Proyecto2/Lista.h
        Proyecto2/main.cpp
        Proyecto2/Nodo.h
        Proyecto2/NodoArbol.h
        Proyecto2/Pila.h
        Proyecto2/utilidades.cpp
        Proyecto2/Utilidades.h)
