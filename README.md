# Proyecto de regresión con datos inmobiliarios en Python
Proyecto de regresión en Python para estimar precios de viviendas a partir de datos inmobiliarios. Incluye análisis exploratorio de datos (EDA), modelos de regresión lineal y random forest, y evaluación con métricas como R², RMSE y MAE.

## Descripción del trabajo práctico
El objetivo del trabajo práctico es predecir el precio de venta de una vivienda a partir de sus características físicas y de ubicación (superficie, cantidad de ambientes, baños, vista al agua, calidad, etc.). Para eso se sigue un flujo completo de ciencia de datos:

- Carga y exploración inicial del dataset.  
- Análisis exploratorio (EDA), con medidas de tendencia central y dispersión, detección de outliers y visualizaciones.  
- Preparación de los datos (tratamiento de tipos, imputación de valores faltantes, escalado de variables numéricas y codificación de categóricas mediante pipelines).  
- Entrenamiento de una regresión lineal como modelo base.  
- Entrenamiento de un modelo más flexible basado en árboles (RandomForestRegressor) para capturar relaciones no lineales.  
- Evaluación y comparación de modelos usando R², RMSE y MAE, con interpretación de los resultados en términos de error promedio en el precio.

## Origen del dataset
Los datos utilizados provienen del dataset público **“House Data”** de Kaggle:
- https://www.kaggle.com/datasets/shree1992/housedata

Para facilitar la corrección del trabajo (tanto por docentes como por la IA  de Coderhouse), una copia del archivo CSV se subió directamente a este repositorio. De esta forma, el notebook puede leer el dataset desde la URL “raw” de GitHub sin necesidad de que la persona que corrija tenga que subir archivos manualmente a Google Colab.

3. El dataset se carga automáticamente desde la URL pública de este repositorio mediante `pandas.read_csv`, por lo que solo se requiere conexión a internet.
