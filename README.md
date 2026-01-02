# Tarea: Curso de Algoritmia

Este repositorio contiene un *Jupyter Notebook* con la implementación en Python de algoritmos fundamentales de ordenamiento, búsqueda y estructuras de datos. El código incluye trazas de ejecución para visualizar el comportamiento paso a paso de cada algoritmo.

## 📋 Contenido

El archivo `Tarea - Algorítmia.ipynb` aborda los siguientes temas:

### 1. Algoritmos de Ordenamiento (Sorting)
* **Heapsort:** Implementación de `max_heapify`, `build_max_heap` y lógica de montículos.
* **Quicksort:** Versiones estándar y **aleatorizada (Randomized)** para optimizar el rendimiento.
* **Ordenamiento Lineal:**
    * *Counting Sort*
    * *Radix Sort*
    * *Bucket Sort*

### 2. Estadísticas de Orden
* Búsqueda del elemento mínimo.
* **Randomized Select:** Algoritmo para encontrar el *i-ésimo* elemento más pequeño en tiempo lineal esperado.

### 3. Estructuras de Datos
* **Listas Enlazadas Dobles:** Operaciones de inserción, búsqueda y eliminación.
* **Pilas (Stacks):** Operaciones `push` y `pop` con manejo de desbordamiento.
* **Colas (Queues):** Implementación circular con punteros `head` y `tail`.

### 4. Árboles Binarios de Búsqueda (BST)
Implementación completa orientada a objetos (`class Node`, `class Tree`) incluyendo:
* Recorridos (`Inorder Tree Walk`).
* Búsqueda (`Tree Search` recursivo e iterativo).
* Mínimo, Máximo y Sucesor.
* Inserción y Eliminación (`Tree Delete` manejando los 3 casos y `Transplant`).

## 🛠️ Requisitos

* Python 3.x
* Jupyter Notebook o JupyterLab

## 🚀 Instrucciones de uso

1. Descarga el archivo `.ipynb`.
2. Abre una terminal o consola en la carpeta del archivo.
3. Ejecuta el entorno de Jupyter:
   ```bash
   jupyter notebook "Tarea - Algorítmia.ipynb"

