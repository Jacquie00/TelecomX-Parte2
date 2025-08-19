# TelecomX-Parte2

Un proyecto integral de ciencia de datos que abarca desde el análisis exploratorio (EDA) hasta el entrenamiento y evaluación de modelos de Machine Learning para predecir la evasión de clientes en una empresa de telecomunicaciones.

Este proyecto, contenido en el notebook TelecomX_LATAM_2.ipynb, aborda el problema de la evasión de clientes (churn) desde dos frentes:

    Análisis Exploratorio de Datos (EDA): Se realiza un análisis detallado de datos de clientes para extraer insights sobre el perfil demográfico y de consumo de los clientes que cancelan el servicio, la influencia del tipo de contrato, los métodos de pago y el impacto de los servicios adicionales.
    Modelado Predictivo (Machine Learning): Se entrenan, evalúan y comparan cuatro modelos de clasificación (Regresión Logística, Random Forest, SVM y Red Neuronal) para predecir con precisión qué clientes tienen una alta probabilidad de abandonar la empresa.

El objetivo final es proporcionar a la empresa una herramienta de análisis y un modelo predictivo que permitan diseñar estrategias de retención efectivas y basadas en datos.
⚙️ Análisis y Modelado Realizado

    Carga y Limpieza: Extracción de datos desde una API en formato JSON, manejo de inconsistencias y valores nulos.
    Ingeniería de Características: Creación de nuevas variables (Costo_Diario), estandarización de variables categóricas (Churn a formato binario).
    Análisis Exploratorio (EDA):
        Análisis descriptivo y de distribución de variables.
        Visualización de la tasa de evasión por grupos (género, tipo de contrato, método de pago).
        Análisis de correlación entre variables numéricas.
    Preprocesamiento para ML:
        Codificación de variables categóricas mediante One-Hot Encoding.
        División de datos en conjuntos de entrenamiento y prueba.
    Entrenamiento y Evaluación de Modelos:
        Implementación de Regresión Logística, Random Forest, SVM y Red Neuronal (MLP).
        Evaluación de rendimiento con métricas como Accuracy, Precision, Recall y F1-Score.
        Generación y análisis de Matrices de Confusión.
    Análisis de Importancia de Variables: Identificación de los factores más influyentes en la predicción de cada modelo.
