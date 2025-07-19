# Arbol B+ en C++

Este proyecto implementa un Arbol B+ dinamico en C++ que permite insertar, eliminar, imprimir y visualizar las hojas encadenadas del arbol. El arbol es visualizado con Graphviz, generando una imagen en formato `.png`.

## Caracteristicas

- Insercion de claves enteras
- Eliminacion de claves manteniendo la estructura del arbol
- Visualizacion de hojas encadenadas
- Generacion automatica de imagen del arbol (`arbol.png`)
- Manejo de subflujos (redistribucion o fusion)
- Recalculo automatico de claves separadoras
- Orden configurable al inicio

## Requisitos

- Compilador C++ compatible con C++11 o superior
- Graphviz instalado (para `dot`)

## Uso

Compila el archivo:

```bash
g++ BPlussTree.cpp -o bpluss
./bpluss
```
## Menu de la aplicacion
1. Insertar
2. Eliminar
3. Imprimir
4. Mostrar arbol
5. Salir

