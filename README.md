# Bank Customer Churn Prediction

Este proyecto busca predecir si un cliente abandonará un banco utilizando técnicas de Machine Learning. El abandono de clientes es un reto clave para el sector bancario, y comprender los factores que lo impulsan permite crear estrategias efectivas de retención.

## 📊 Dataset

El conjunto de datos utilizado proviene de [Kaggle](https://www.kaggle.com/code/kmalit/bank-customer-churn-prediction/data). Contiene información demográfica y financiera de los clientes.

## 🎯 Objetivos

- Realizar un análisis exploratorio para entender el comportamiento de los clientes.
- Preprocesar los datos de forma adecuada para entrenar modelos.
- Probar diferentes algoritmos de clasificación para predecir el abandono.
- Evaluar el desempeño de los modelos con métricas apropiadas.
- Extraer insights accionables sobre los factores de abandono.

## 📁 Estructura del repositorio
```bash
bank-customer-churn-prediction/
│
├── data/                  # Contiene el dataset original y procesado
│   ├── raw/               # Datos originales sin procesar
│   └── processed/         # Datos ya transformados y limpios
│
├── notebooks/             # Jupyter notebooks para EDA, modelado, etc.
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_Modeling.ipynb
│   └── 04_Evaluation.ipynb
│
├── src/                   # Scripts reutilizables
│   ├── data_preparation.py
│   ├── modeling.py
│   └── utils.py
│
├── reports/               # Resultados, visualizaciones y documentos
│   └── figures/           # Gráficos y visualizaciones
│
├── models/                # Modelos entrenados y serializados
│
├── .gitignore             # Ignora archivos temporales y carpetas
├── README.md              # Descripción general del proyecto
└── requirements.txt       # Librerías necesarias para reproducir el entorno
```


## 🚀 Requisitos

Para instalar las dependencias:

```bash
pip install -r requirements.txt
```
## 🧠 Técnicas a aplicar
- Análisis Exploratorio de Datos (EDA)

- Ingeniería de características

- Modelos de clasificación (Logistic Regression, Random Forest, XGBoost, etc.)

- Evaluación con métricas como AUC, Precision, Recall

- Interpretabilidad de modelos (SHAP, Feature Importance)
