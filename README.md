# Material — Ciencia de Datos

Material de apoyo en Jupyter Notebooks sobre **Machine Learning** (supervisado y no supervisado) y **Deep Learning**, orientado a un diplomado en Ciencia de Datos.

Autor: [Juan Felipe Contreras](https://www.linkedin.com/in/juanf-contreras/)

---

## Tabla de contenido

- [Descripción](#descripción)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Machine Learning supervisado](#machine-learning-supervisado)
- [Machine Learning no supervisado](#machine-learning-no-supervisado)
- [Deep Learning](#deep-learning)
- [Ejercicios prácticos de Deep Learning](#ejercicios-prácticos-de-deep-learning)
- [Cómo usar este material](#cómo-usar-este-material)
- [Requisitos](#requisitos)

---

## Descripción

Este repositorio reúne cuadernos didácticos que cubren desde los fundamentos del aprendizaje automático hasta redes neuronales profundas. El contenido está organizado de forma progresiva: primero modelos supervisados clásicos, luego técnicas no supervisadas (reducción de dimensión y clustering) y, finalmente, deep learning con TensorFlow/Keras.

---

## Estructura del repositorio

```text
Material-Ciencia-de-Datos/
├── Machine_Learning/
│   ├── 00_intro.ipynb … 10_Validaciones.ipynb   # Aprendizaje supervisado
│   ├── Unsupervised/                            # Reducción de dimensión y clustering
│   └── img/                                     # Imágenes de apoyo
└── Deep_Learning/
    ├── Cuadernos/                               # Redes neuronales, CNN y RNN
    ├── Ejercicios/                              # Talleres prácticos para estudiantes
    │   └── Soluciones/                          # Soluciones de referencia
    └── img/                                     # Imágenes de apoyo
```

---

## Machine Learning supervisado

Ruta: [`Machine_Learning/`](Machine_Learning/)

| # | Cuaderno | Tema |
|---|----------|------|
| 00 | [00_intro.ipynb](Machine_Learning/00_intro.ipynb) | Introducción al Machine Learning |
| 01 | [01_Regresión_Lineal.ipynb](Machine_Learning/01_Regresión_Lineal.ipynb) | Regresión lineal |
| 02 | [02_Regresión_Lineal_II.ipynb](Machine_Learning/02_Regresión_Lineal_II.ipynb) | Regresión lineal II |
| 03 | [03_Regresión_Lineal_III.ipynb](Machine_Learning/03_Regresión_Lineal_III.ipynb) | Regresión lineal III |
| 04 | [04_Regresión_Logística.ipynb](Machine_Learning/04_Regresión_Logística.ipynb) | Regresión logística |
| 05 | [05_Matriz_Confusión.ipynb](Machine_Learning/05_Matriz_Confusión.ipynb) | Matriz de confusión |
| 06 | [06_SVM.ipynb](Machine_Learning/06_SVM.ipynb) | Máquinas de soporte vectorial (SVM) |
| 07 | [07_KNN.ipynb](Machine_Learning/07_KNN.ipynb) | K vecinos más cercanos (KNN) |
| 08 | [08_árboles_decisión.ipynb](Machine_Learning/08_árboles_decisión.ipynb) | Árboles de decisión |
| 09 | [09_ensamble.ipynb](Machine_Learning/09_ensamble.ipynb) | Métodos de ensamble |
| 10 | [10_Validaciones.ipynb](Machine_Learning/10_Validaciones.ipynb) | Validación de modelos |

---

## Machine Learning no supervisado

Ruta: [`Machine_Learning/Unsupervised/`](Machine_Learning/Unsupervised/)

### Reducción de dimensión

| # | Cuaderno | Tema |
|---|----------|------|
| 00 | [00_intro_red_dim.ipynb](Machine_Learning/Unsupervised/00_intro_red_dim.ipynb) | Introducción a la reducción de dimensión |
| 01 | [01_ACP.ipynb](Machine_Learning/Unsupervised/01_ACP.ipynb) | Análisis de Componentes Principales (ACP) |
| 02 | [02_TSNE.ipynb](Machine_Learning/Unsupervised/02_TSNE.ipynb) | t-SNE |
| 03 | [03_UMAP.ipynb](Machine_Learning/Unsupervised/03_UMAP.ipynb) | UMAP |
| 04 | [04_TriMAP.ipynb](Machine_Learning/Unsupervised/04_TriMAP.ipynb) | TriMAP |
| 05 | [05_PaCMAP.ipynb](Machine_Learning/Unsupervised/05_PaCMAP.ipynb) | PaCMAP |

### Clustering

| # | Cuaderno | Tema |
|---|----------|------|
| 06 | [06_K_Medias.ipynb](Machine_Learning/Unsupervised/06_K_Medias.ipynb) | K-medias |
| 07 | [07_DBSCAN.ipynb](Machine_Learning/Unsupervised/07_DBSCAN.ipynb) | DBSCAN |
| 08 | [08_HDBSCAN.ipynb](Machine_Learning/Unsupervised/08_HDBSCAN.ipynb) | HDBSCAN |
| — | [Aplicaciones.ipynb](Machine_Learning/Unsupervised/Aplicaciones.ipynb) | Ejercicios prácticos de clustering y reducción de dimensión |

---

## Deep Learning

Ruta: [`Deep_Learning/Cuadernos/`](Deep_Learning/Cuadernos/)

| # | Cuaderno | Tema |
|---|----------|------|
| 00 | [00_Intro_Redes_Neuronales.ipynb](Deep_Learning/Cuadernos/00_Intro_Redes_Neuronales.ipynb) | Introducción a las redes neuronales artificiales |
| 01 | [01_Optimizadores.ipynb](Deep_Learning/Cuadernos/01_Optimizadores.ipynb) | Optimizadores |
| 02 | [02_Entrenamiento_Red_neuronal.ipynb](Deep_Learning/Cuadernos/02_Entrenamiento_Red_neuronal.ipynb) | Entrenamiento de una red neuronal con TensorFlow |
| 03 | [03_Curvas_entrenamiento.ipynb](Deep_Learning/Cuadernos/03_Curvas_entrenamiento.ipynb) | Curvas de entrenamiento |
| 04 | [04_Callbacks.ipynb](Deep_Learning/Cuadernos/04_Callbacks.ipynb) | Callbacks |
| 05 | [05_Convoluciones.ipynb](Deep_Learning/Cuadernos/05_Convoluciones.ipynb) | Introducción a las convoluciones |
| 06 | [06_CNN.ipynb](Deep_Learning/Cuadernos/06_CNN.ipynb) | Redes neuronales convolucionales (CNN) |
| 07 | [07_RNN.ipynb](Deep_Learning/Cuadernos/07_RNN.ipynb) | Redes neuronales recurrentes (RNN) |

---

## Ejercicios prácticos de Deep Learning

Ruta: [`Deep_Learning/Ejercicios/`](Deep_Learning/Ejercicios/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Fundamentos_Redes_Neuronales.ipynb](Deep_Learning/Ejercicios/01_Taller_Fundamentos_Redes_Neuronales.ipynb) | Taller práctico: activaciones, optimizadores, entrenamiento, curvas y callbacks |

### Soluciones

Ruta: [`Deep_Learning/Ejercicios/Soluciones/`](Deep_Learning/Ejercicios/Soluciones/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Fundamentos_Redes_Neuronales_Solucion.ipynb](Deep_Learning/Ejercicios/Soluciones/01_Taller_Fundamentos_Redes_Neuronales_Solucion.ipynb) | Solución de referencia del taller de fundamentos |

---

## Cómo usar este material

1. Clona el repositorio:
   ```bash
   git clone https://github.com/contreras-juan/Material-Ciencia-de-Datos.git
   cd Material-Ciencia-de-Datos
   ```
2. Abre los cuadernos con Jupyter Notebook, JupyterLab o VS Code/Cursor.
3. Se recomienda seguir el orden numérico dentro de cada carpeta.

---

## Requisitos

Entorno recomendado con Python 3 y las librerías habituales del stack de ciencia de datos, por ejemplo:

- `numpy`, `pandas`, `matplotlib`, `seaborn`
- `scikit-learn`
- `tensorflow` / `keras` (para la sección de Deep Learning)
- Librerías de reducción de dimensión según el cuaderno (`umap-learn`, etc.)

Puedes instalar Jupyter con:

```bash
pip install notebook
```
