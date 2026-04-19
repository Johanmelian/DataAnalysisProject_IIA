# DataAnalysisProject_IIA
Objetivo:
El objetivo de este ejercicio es aplicar técnicas de reducción de dimensionalidad y clasificadores probabilísticos para analizar un conjunto de datos, comparar los rendimientos de diferentes clasificadores y determinar cuál es más efectivo para predecir la calidad del vino en función de sus características.

Contexto:
El conjunto de datos "wine quality dataset" contiene información relacionada con variantes rojas y blancas del vino portugués "Vinho Verde". Los atributos incluyen la acidez, el azúcar residual, el alcohol, y otros, con el objetivo de predecir la calidad del vino.

Tareas:

    Preprocesamiento de Datos:
        Cargar el dataset "wine quality dataset".
        Realizar un análisis exploratorio inicial para entender las características de los datos, incluyendo estadísticas descriptivas y visualizaciones de las distribuciones de las características y la variable objetivo.
        Limpiar y preparar los datos para el análisis, lo que puede incluir la gestión de valores faltantes y la normalización de variables numéricas.

    Reducción de Dimensionalidad usando PCA:
        Aplicar PCA (Análisis de Componentes Principales) para reducir la dimensionalidad del conjunto de datos.
        Seleccionar el número de componentes principales necesarios para capturar una cantidad significativa de la variabilidad en los datos.
        Transformar los datos a este nuevo espacio de características reducido.

    Clasificación:
        Utilizar dos clasificadores probabilísticos para modelar y predecir la variable objetivo.
        Entrenar los modelos usando los datos transformados por PCA.

    Evaluación de Modelos:
        Evaluar el rendimiento de cada modelo clasificador utilizando métricas como la precisión, la matriz de confusión, ...
        Comparar los rendimientos de los dos clasificadores basándose en estas métricas.

Entregar el código y un informe con los resultados. El informe debe incluir un análisis previo de los datos incluyendo un análisis de la correlación de los datos y gráficas acompañadas de una explicación, también aplicar una técnica de reducción de dimensionalidad justificando su uso y ventajas, utilizar dos clasificadores y compararlos usando técnicas como cross validation y todas las métricas que sean necesarias. Además compara los resultados de los clasificadores usando y sin usar la técnica de reducción de dimensionalidad.
