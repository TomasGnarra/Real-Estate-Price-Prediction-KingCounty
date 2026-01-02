# Real-Estate-Price-Prediction-KingCounty
# 🏠 Predicción de Precios Inmobiliarios: King County Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=python&logoColor=white)

### 📋 Resumen Ejecutivo
Análisis exploratorio y modelado predictivo para estimar el valor de propiedades en King County (USA). El objetivo fue identificar las variables determinantes en el precio y generar un modelo de regresión robusto para tasación automática.

### 🛠️ Metodología Aplicada
1.  **EDA (Exploratory Data Analysis):**
    * Análisis univariado y bivariado para detectar outliers en precios y pies cuadrados.
    * Mapa de calor de correlaciones (Heatmap) para selección de features.
2.  **Ingeniería de Características:**
    * **PCA (Principal Component Analysis):** Reducción de dimensionalidad para optimizar el rendimiento del modelo y evitar la multicolinealidad.
    * Normalización de datos.
3.  **Modelado:**
    * Implementación de **Regresión Lineal Múltiple**.
    * División Train/Test para validación de resultados.

### 📉 Insights
* La variable `sqft_living` (pies cuadrados habitables) mostró la correlación positiva más fuerte con el precio.
* La reducción de dimensiones mediante PCA permitió mantener la varianza explicada simplificando la complejidad del modelo.
