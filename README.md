# Parcial-1-ciencia-de-datos
Informe de Regresión Lineal y Estadística Descriptiva
Este repositorio contiene dos análisis distintos aplicados a datasets clásicos en el mundo del Machine Learning y la Ciencia de Datos:

Regresión Lineal con Gradiente Descendente: Boston Housing Dataset
Análisis Descriptivo: Iris Dataset
1. Regresión Lineal con Gradiente Descendente: Boston Housing Dataset
El objetivo de este ejercicio es construir un modelo de regresión lineal simple que predice el valor medio de las viviendas en Boston (MEDV) basado en el número promedio de habitaciones por vivienda (RM). Para ajustar los parámetros del modelo (pendiente e intercepto), se implementa el algoritmo de gradiente descendente, optimizando la función de costo mediante múltiples iteraciones.

El análisis no solo explora la relación entre RM y MEDV, sino que también proporciona una introducción a la implementación práctica del gradiente descendente para ajustar modelos de regresión.

Aspectos clave:
Algoritmo: Gradiente descendente.
Tasa de aprendizaje: 0.01.
Número de iteraciones: 1000.
Visualización: Gráfica de regresión lineal sobre los datos de dispersión.
2. Análisis Descriptivo: Iris Dataset
Este ejercicio se enfoca en un análisis estadístico descriptivo del Iris Dataset, que contiene información sobre tres especies de flores (Setosa, Versicolor, y Virginica). El análisis incluye cálculos de media, mediana y desviación estándar de las características principales del dataset, como la longitud y el ancho de los sépalos y pétalos. Este tipo de análisis es útil para comprender la distribución y variabilidad de los datos antes de aplicar cualquier modelo predictivo.

Aspectos clave:
Características: sepal_length, sepal_width, petal_length, petal_width.
Estadísticas calculadas: Media, mediana, desviación estándar.
Interpretación: Descripción de la variabilidad y distribución de las características por especie.
Requisitos
Python 3.x
Librerías: pandas, numpy, matplotlib, sklearn, seaborn (para el análisis del Iris Dataset).
Ejecución
Cada análisis está organizado en archivos .ipynb que pueden ser ejecutados en cualquier entorno compatible con Jupyter Notebook. Los resultados de los gráficos y cálculos se encuentran detallados en los respectivos cuadernos.
