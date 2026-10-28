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
- [Proyecto final](#proyecto-final)
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
│   ├── Supervised/                              # Aprendizaje supervisado
│   │   ├── 00_intro.ipynb … 12_Desbalanceo_Clases.ipynb
│   │   └── Ejercicios/                          # Talleres prácticos (con Soluciones/)
│   ├── Unsupervised/                            # Reducción de dimensión y clustering
│   └── img/                                     # Imágenes de apoyo
└── Deep_Learning/
    ├── Cuadernos/                               # Redes neuronales, CNN, RNN, visión, destilación
    ├── Ejercicios/                              # Talleres prácticos para estudiantes
    │   └── Soluciones/                          # Soluciones de referencia
    ├── Proyecto_Final.docx                      # Especificación y grilla del proyecto de cierre
    └── img/                                     # Imágenes de apoyo
```

---

## Machine Learning supervisado

Ruta: [`Machine_Learning/Supervised/`](Machine_Learning/Supervised/)

| # | Cuaderno | Tema |
|---|----------|------|
| 00 | [00_intro.ipynb](Machine_Learning/Supervised/00_intro.ipynb) | Introducción al Machine Learning |
| 01 | [01_Regresión_Lineal.ipynb](Machine_Learning/Supervised/01_Regresión_Lineal.ipynb) | Regresión lineal |
| 02 | [02_Regresión_Lineal_II.ipynb](Machine_Learning/Supervised/02_Regresión_Lineal_II.ipynb) | Regresión lineal II |
| 03 | [03_Regresión_Lineal_III.ipynb](Machine_Learning/Supervised/03_Regresión_Lineal_III.ipynb) | Regresión lineal III |
| 04 | [04_Regresión_Logística.ipynb](Machine_Learning/Supervised/04_Regresión_Logística.ipynb) | Regresión logística |
| 05 | [05_Matriz_Confusión.ipynb](Machine_Learning/Supervised/05_Matriz_Confusión.ipynb) | Matriz de confusión |
| 06 | [06_SVM.ipynb](Machine_Learning/Supervised/06_SVM.ipynb) | Máquinas de soporte vectorial (SVM) |
| 07 | [07_KNN.ipynb](Machine_Learning/Supervised/07_KNN.ipynb) | K vecinos más cercanos (KNN) |
| 08 | [08_árboles_decisión.ipynb](Machine_Learning/Supervised/08_árboles_decisión.ipynb) | Árboles de decisión |
| 09 | [09_ensamble.ipynb](Machine_Learning/Supervised/09_ensamble.ipynb) | Métodos de ensamble |
| 10 | [10_Validaciones.ipynb](Machine_Learning/Supervised/10_Validaciones.ipynb) | Validación de modelos |
| 11 | [11_SHAP.ipynb](Machine_Learning/Supervised/11_SHAP.ipynb) | Interpretabilidad con valores SHAP |
| 12 | [12_Desbalanceo_Clases.ipynb](Machine_Learning/Supervised/12_Desbalanceo_Clases.ipynb) | Desbalanceo de clases: métricas, remuestreo, pesos, umbral y simulaciones por modelo |

### Ejercicios prácticos de Machine Learning

Ruta: [`Machine_Learning/Supervised/Ejercicios/`](Machine_Learning/Supervised/Ejercicios/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Regresion_Clasificacion.ipynb](Machine_Learning/Supervised/Ejercicios/01_Taller_Regresion_Clasificacion.ipynb) | Taller práctico: regresión lineal, logística, KNN, SVM y árboles; entrenamiento, evaluación e interpretación con datos públicos (costos médicos y diabetes Pima) |

Soluciones en [`Machine_Learning/Supervised/Ejercicios/Soluciones/`](Machine_Learning/Supervised/Ejercicios/Soluciones/):

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Regresion_Clasificacion_Solucion.ipynb](Machine_Learning/Supervised/Ejercicios/Soluciones/01_Taller_Regresion_Clasificacion_Solucion.ipynb) | Solución de referencia del taller de regresión y clasificación |
| 02 | [12_Desbalanceo_Clases_Solucion.ipynb](Machine_Learning/Supervised/Ejercicios/Soluciones/12_Desbalanceo_Clases_Solucion.ipynb) | Solución de los ejercicios del cuaderno de desbalanceo de clases |

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
| 08 | [8_FT_TL.ipynb](Deep_Learning/Cuadernos/8_FT_TL.ipynb) | Fine-tuning y transfer learning |
| 09 | [9_Autoencoders.ipynb](Deep_Learning/Cuadernos/9_Autoencoders.ipynb) | Autoencoders |
| 10 | [10_Visión_Computadora.ipynb](Deep_Learning/Cuadernos/10_Visión_Computadora.ipynb) | Visión por computadora |
| 11 | [11_Destilación_Conocimiento.ipynb](Deep_Learning/Cuadernos/11_Destilación_Conocimiento.ipynb) | Destilación de conocimiento |

---

## Ejercicios prácticos de Deep Learning

Ruta: [`Deep_Learning/Ejercicios/`](Deep_Learning/Ejercicios/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Fundamentos_Redes_Neuronales.ipynb](Deep_Learning/Ejercicios/01_Taller_Fundamentos_Redes_Neuronales.ipynb) | Taller práctico: activaciones, optimizadores, entrenamiento, curvas y callbacks |
| 02 | [02_Taller_Convoluciones_y_CNN.ipynb](Deep_Learning/Ejercicios/02_Taller_Convoluciones_y_CNN.ipynb) | Taller práctico: convoluciones, filtros, pooling y CNN |
| 03 | [03_Taller_RNN_LSTM.ipynb](Deep_Learning/Ejercicios/03_Taller_RNN_LSTM.ipynb) | Taller práctico: RNN, LSTM, multipaso y comparación GRU |
| 04 | [04_Taller_Autoencoders.ipynb](Deep_Learning/Ejercicios/04_Taller_Autoencoders.ipynb) | Taller práctico: autoencoders, denoising y anomalías |

### Soluciones

Ruta: [`Deep_Learning/Ejercicios/Soluciones/`](Deep_Learning/Ejercicios/Soluciones/)

| # | Cuaderno | Tema |
|---|----------|------|
| 01 | [01_Taller_Fundamentos_Redes_Neuronales_Solucion.ipynb](Deep_Learning/Ejercicios/Soluciones/01_Taller_Fundamentos_Redes_Neuronales_Solucion.ipynb) | Solución de referencia del taller de fundamentos |
| 02 | [02_Taller_Convoluciones_y_CNN_Solucion.ipynb](Deep_Learning/Ejercicios/Soluciones/02_Taller_Convoluciones_y_CNN_Solucion.ipynb) | Solución de referencia del taller de convoluciones y CNN |
| 03 | [03_Taller_RNN_LSTM_Solucion.ipynb](Deep_Learning/Ejercicios/Soluciones/03_Taller_RNN_LSTM_Solucion.ipynb) | Solución de referencia del taller de RNN/LSTM |
| 04 | [04_Taller_Autoencoders_Solucion.ipynb](Deep_Learning/Ejercicios/Soluciones/04_Taller_Autoencoders_Solucion.ipynb) | Solución de referencia del taller de autoencoders |

---

## Proyecto final

Ruta: [`Deep_Learning/Proyecto_Final.docx`](Deep_Learning/Proyecto_Final.docx)

Trabajo de cierre del módulo de Deep Learning: el equipo elige un **dataset nuevo** (no el de las notas ni de los talleres), formula un problema, entrena y evalúa un modelo en Keras anclado a uno o más conceptos del módulo, y lo presenta.

El documento incluye alcance, datasets prohibidos, entregables (notebook y exposición) y una **grilla sobre 5.0** (problema, datos, baseline, modelo, evaluación, reproducibilidad y presentación).

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
