📊 Comparación de Modelos de Clasificación
Predicción de Churn – Machine Learning Supervisado
📌 Descripción del Proyecto

Este proyecto desarrolla y compara tres modelos de clasificación supervisada para predecir el abandono de clientes (Churn) en un dataset de telecomunicaciones.

El objetivo es evaluar el desempeño de distintos enfoques y seleccionar el modelo más adecuado en función de métricas de clasificación, con foco en ROC AUC como métrica principal.

🎯 Objetivo

Construir y comparar modelos de Machine Learning capaces de predecir la probabilidad de abandono de clientes, aplicando un pipeline completo que incluye:

Análisis exploratorio de datos (EDA)

Preprocesamiento

Codificación de variables categóricas

Escalado de variables

Entrenamiento y validación

Evaluación comparativa

📂 Estructura del Repositorio

ML_Modelos_de_Clasificacion_Comparacion.ipynb → Notebook principal

sweetviz_analize_rep.html → Reporte exploratorio generado con Sweetviz

dataset_clasificacion.zip → Contiene:

train.csv

test.csv

sample_submission.csv

🔎 Análisis Exploratorio

Se realizó un análisis exploratorio que incluyó:

Identificación de variables numéricas y categóricas

Exploración estadística de variables

Análisis de la variable objetivo

Generación de reporte automático con Sweetviz

⚙️ Preprocesamiento

El pipeline implementado incluye:

Separación en entrenamiento y validación mediante train_test_split

Codificación de variables categóricas con:

get_dummies

OneHotEncoder

Escalado de variables numéricas con StandardScaler

Implementación de Pipeline para estructurar el flujo de modelado

🤖 Modelos Implementados

Se entrenaron y compararon los siguientes modelos:

🔹 Regresión Logística

Modelo lineal base utilizado como referencia.

🔹 k-Nearest Neighbors (k-NN)

Modelo basado en distancia entre observaciones.

🔹 Naive Bayes

Modelo probabilístico basado en el teorema de Bayes con supuesto de independencia condicional.

📊 Métricas de Evaluación

Se utilizaron las siguientes métricas:

ROC AUC (métrica principal)

Accuracy

F1-Score

Classification Report

Matriz de Confusión

Validación cruzada (cross_val_score)

El modelo con mejor desempeño fue utilizado para generar el archivo de predicción final.

▶️ Cómo Ejecutar el Proyecto
1️⃣ Preparación del Dataset

Descargar o clonar el repositorio.

Descomprimir dataset_clasificacion.zip.

Asegurarse de que los archivos:

train.csv

test.csv

sample_submission.csv

estén en la misma carpeta que el notebook.

⚠️ El notebook espera encontrar los archivos CSV en el mismo directorio.

2️⃣ Requisitos

Python 3

Librerías:

pandas

numpy

matplotlib

seaborn

scikit-learn

sweetviz

🚀 Competencias Demostradas

Construcción de pipeline completo de clasificación supervisada

Implementación y comparación de múltiples modelos

Evaluación rigurosa mediante métricas de desempeño

Uso de validación cruzada

Preparación de archivo de submission

👤 Autor

Ing. César Renato Ramírez
Ciencia de Datos | Machine Learning | Modelado Predictivo
