# Notebook de Exploración en Espacios de Estados

Este proyecto implementa varios algoritmos de búsqueda no informada e informada para resolver problemas en espacios de estados, utilizando Python y Jupyter Notebook.

## Funcionalidades Implementadas

El notebook incluye implementaciones de:

1.  **Función de Expansión** (`expandir`).
2.  **Algoritmos de Búsqueda No Informada:**
    * Búsqueda en Profundidad (`profundidad`)
    * Búsqueda en Amplitud (`amplitud`)
3.  **Algoritmos de Búsqueda Informada:**
    * Escalada (`escalada`)
    * Primero el Mejor (`primero_el_mejor`) 
    * Branch & Bound (`branch_and_bound`)
    * A* (`a_estrella`)

## Problemas Aplicados

Las funciones desarrolladas se aplican a los siguientes problemas:

1.  **Trayecto más corto en el Metro de Madrid:** Encontrar el camino entre dos estaciones.
2.  **Problema de las Vasijas:** Encontrar la secuencia de operaciones para alcanzar un estado deseado, minimizando pasos o gasto de agua.
3.  **8-Puzzle:** Encontrar el camino con el menor número de pasos para pasar de un estado inicial desordenado a un estado objetivo (las fichas ordenadas, con el 0 representando la casilla vacía), utilizando como heurístico la distancia de cada pieza a su posición final.

## Requisitos

Para ejecutar el notebook, necesitarás tener instalado:

* **Python 3.x**
* **Jupyter Notebook** (o JupyterLab)
