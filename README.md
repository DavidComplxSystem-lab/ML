# 🏦 Predicción de Otorgamiento de Crédito (German Credit Data)

## 📋 Descripción del Proyecto
Este proyecto implementa un modelo de **Machine Learning** para la evaluación de riesgo crediticio (Credit Scoring). El objetivo es automatizar la fase de análisis cuantitativo en el proceso de otorgamiento de crédito, clasificando a los solicitantes en "Buen Crédito" o "Mal Crédito" basándose en su historial y características demográficas.

Se utiliza el conjunto de datos **German Credit Data** del repositorio UCI Machine Learning.

## 🎯 Contexto de Negocio
De acuerdo con las mejores prácticas internacionales (Comité de Basilea) y normativas locales (CNBV), el proceso de crédito consta de fases críticas. Este notebook se enfoca en las etapas de:
1. **Evaluación:** Verificación de capacidad de pago.
2. **Scoring:** Modelado estadístico para medir la probabilidad de incumplimiento (PD).

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Análisis de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Modelado:** Scikit-learn (Clasificación)

## 📊 Estructura del Análisis
El notebook `Otorgamiento_crédito_GermanCreditData_.ipynb` sigue este flujo:
1. **Carga de Datos:** Ingesta del dataset German Credit.
2. **Preprocesamiento:** Limpieza de datos, codificación de variables categóricas y manejo de valores nulos.
3. **Análisis Exploratorio (EDA):** Identificación de patrones en variables como edad, monto del crédito y propósito.
4. **Modelado:** Entrenamiento de algoritmos de clasificación (ej. Regresión Logística / Árboles de Decisión).
5. **Evaluación:** Medición del desempeño del modelo mediante Matriz de Confusión y Curva ROC.

## 🚀 Cómo usar este repositorio
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/DavidComplxSystem-lab/ML.git](https://github.com/DavidComplxSystem-lab/ML.git)
