# Proyecto de Simulación de Grafos Aleatorios y Procesos Estocásticos

Este proyecto se centra en la simulación de **grafos aleatorios** utilizando el **modelo Erdös-Rényi**, así como en la exploración de procesos estocásticos relacionados. A través de la implementación de este modelo, es posible generar grafos de acuerdo con una probabilidad \(p\), permitiendo estudiar diversas propiedades y comportamientos de redes aleatorias.

## ¿Qué son los grafos aleatorios?

Un **grafo aleatorio** es una estructura compuesta por nodos (vértices) y conexiones entre ellos (aristas), donde las conexiones se generan de manera aleatoria según ciertos parámetros. En el caso del **modelo Erdös-Rényi**:

- Se empieza con un conjunto de \(N\) vértices.
- Cada par de vértices se conecta con una arista de acuerdo con una probabilidad \(p\). Esto significa que cada posible arista se incluye en el grafo con una probabilidad \(p\), de manera independiente de las demás aristas.

El resultado es una red donde la densidad de conexiones depende de \(p\), lo que permite estudiar el comportamiento de redes bajo distintas condiciones.

## Especificaciones Técnicas

### Modelo Erdös-Rényi

El **modelo Erdös-Rényi** genera un grafo aleatorio al considerar un conjunto de \(N\) vértices y conectar cada par de vértices con una probabilidad \(p\). La matriz de adyacencia \(M\) de tamaño \(N \times N\) se utiliza para representar este grafo, donde:

- \(M_{ij} = 1\) si existe una arista entre los vértices \(i\) y \(j\).
- \(M_{ij} = 0\) si no existe una conexión.
- La diagonal de la matriz siempre tiene valores 0, es decir, no hay conexiones auto-referenciales (\(M_{ii} = 0\)).

### Objetivo del Proyecto

Este proyecto te permitirá generar y visualizar grafos aleatorios, explorar su estructura y analizar las propiedades que emergen a medida que cambian los parámetros del modelo, como el número de vértices \(N\) y la probabilidad de conexión \(p\). Entre las propiedades que pueden ser interesantes de analizar se incluyen:

- **Conectividad:** Qué tan probable es que el grafo sea conexo, es decir, que exista un camino entre cualquier par de vértices.
- **Densidad de aristas:** Proporción de conexiones reales en comparación con el número total de posibles conexiones.
- **Distribución de grados:** Cómo se distribuye el número de conexiones entre los diferentes vértices.


## Requisitos

Para ejecutar este proyecto, necesitarás lo siguiente:

- **Python 3.x**: El lenguaje de programación principal utilizado en el proyecto.
- **Numpy**: Una biblioteca de Python para manejar matrices y realizar cálculos numéricos.

Para instalar las dependencias, puedes usar el siguiente comando en tu terminal:


pip install numpy networkx

```bash
pip install numpy

