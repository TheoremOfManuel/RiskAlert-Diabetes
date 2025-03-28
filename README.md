# RiskAlert-Diabetes
# 🩺 Predicción de Riesgo de Diabetes con Machine Learning

Este proyecto tiene como objetivo desarrollar un modelo de clasificación supervisada capaz de predecir el riesgo de una persona de padecer diabetes, utilizando variables acerca del estilo de vida de las personas.

## 📚 Descripción

El modelo fue entrenado con un conjunto de datos que incluye información categórica relacionada con el estilo de vida, estado de salud y características personales. Se aplicaron técnicas de preprocesamiento como limpieza de datos, manejo de valores atípicos, codificación de variables categóricas y balanceo de clases para asegurar un entrenamiento justo y representativo.

Se exploraron diferentes modelos de clasificación y se compararon con métricas clave para identificar el de mejor desempeño.

Fuente de los datos: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

## ⚙️ Modelos utilizados
- Regresión logísitca
- Árboles de Decisión
- Random Forest
- K-Nearest Neighbors (KNN)-
- XGboost
- LightGBM

## 📈 Métricas de evaluación

Se utilizaron las siguientes métricas para evaluar el desempeño de los modelos:

- Accuracy
- Precision (por clase)
- Recall (por clase)
- F1-score (por clase)
- Specificity (por clase)

El mejor modelo fue el Árbol de Decisión usando la base de datos que tiene hasta 3 desviaciones estandar y balanceada, con un **accuracy aproximado del 78%**, mostrando un buen balance entre sensibilidad y especificidad en todas las clases.


## 🛠️ Tecnologías y herramientas

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

## 🚀 Posibles mejoras futuras

- Ampliar el dataset con nuevas variables clínicas y demográficas
- Explorar modelos más avanzados como redes neuronales profundas
- Integrar el modelo en una aplicación web o dashboard interactivo
- Validación en entornos reales (clínicas, hospitales, EPS)


