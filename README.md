# TFG---Predicci-n-del-xito-en-pisos-tur-sticos-de-Madrid-Airbnb-
Análisis de los factores de éxito en pisos turísticos de Madrid utilizando Python 
# Predicción del Éxito en Airbnb y Segmentación del Mercado
# Descripción del proyecto

Este proyecto analiza el mercado de alquiler turístico (Airbnb) utilizando técnicas de ciencia de datos y machine learning para identificar los factores que influyen en el éxito de los alojamientos.

El estudio combina segmentación de mercado mediante clustering y modelos predictivos para entender qué características de las propiedades y de los anfitriones están asociadas con una mayor probabilidad de éxito.

El objetivo es generar insights empresariales útiles para anfitriones, inversores y gestores de propiedades en el mercado del alquiler turístico.

# Objetivos del proyecto

El proyecto tiene como objetivos principales:

Identificar segmentos de mercado dentro de Airbnb

Analizar los factores que influyen en el éxito de un alojamiento

Construir modelos predictivos para estimar la probabilidad de éxito

Interpretar cómo los factores inciden en el éxito

# Metodología

El análisis sigue un flujo típico de proyecto de ciencia de datos.

1. Limpieza y preparación de datos

Se realizó un proceso de preparación del dataset que incluyó:

Tratamiento de valores faltantes

Creación de nuevas variables (feature engineering)

Codificación de variables categóricas

Selección de variables relevantes para el análisis

Algunas variables utilizadas incluyen:

precio del alojamiento

capacidad (accommodates)

número de dormitorios

número de baños

noches mínimas

número de propiedades del anfitrión

tasa de respuesta del anfitrión

puntuaciones de reseñas

condición de superhost

reserva instantánea

amenities (aire acondicionado, terraza, espacio de trabajo)

2. Segmentación del mercado

Para analizar la estructura del mercado se aplicaron técnicas de aprendizaje no supervisado.

Métodos utilizados:

PCA (Análisis de Componentes Principales) para reducción de dimensionalidad

K-Means Clustering para identificar segmentos de mercado

Este análisis permitió identificar diferentes tipos de alojamientos, como por ejemplo:

Apartamentos premium gestionados profesionalmente

Alojamientos de alta calidad gestionados por superhosts

Propiedades de gama media

Alojamientos con bajo rendimiento

3. Modelos predictivos

Para predecir el éxito de un alojamiento se entrenaron varios modelos de machine learning:

Regresión Logística

Random Forest

XGBoost

Los modelos se evaluaron utilizando métricas como:

Accuracy

Precision

Recall

F1 Score

Ejemplo de resultados obtenidos:

Modelo	Accuracy	F1 Score
XGBoost	0.86	0.78
Random Forest	0.85	0.73
Regresión Logística	0.79	0.61

El modelo XGBoost obtuvo el mejor rendimiento.

4. Interpretabilidad del modelo

Para interpretar los resultados del modelo se utilizó SHAP (SHapley Additive Explanations).

Esta técnica permite:

Identificar las variables más influyentes

Analizar el impacto de cada variable en la predicción

Interpretar modelos complejos de machine learning

Esto permite transformar el modelo en información útil para la toma de decisiones empresariales.

Principales conclusiones

El análisis identifica varios factores asociados con el éxito de los alojamientos:

Altas puntuaciones en reseñas

Alta tasa de respuesta del anfitrión

Reserva instantánea activada

Anfitriones superhost

Propiedades más grandes con más amenities

El estudio sugiere la existencia de dos estrategias exitosas en el mercado:

Apartamentos premium gestionados de forma profesional

Alojamientos boutique de alta calidad gestionados por superhosts

# Herramientas utilizadas

El proyecto se desarrolló utilizando Python y las siguientes librerías:

pandas

numpy

scikit-learn

xgboost

shap

matplotlib

seaborn

# Estructura del proyecto
airbnb-success-analysis/
│
├── data/
│   └── datasets utilizados
│
├── notebooks/
│   ├── 01_limpieza_datos.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_clustering.ipynb
│   ├── 04_modelos_predictivos.ipynb
│   └── 05_interpretacion_modelo.ipynb
│
├── figures/
│   └── gráficos y visualizaciones
│
└── README.md
# Relevancia empresarial

Este proyecto muestra cómo la ciencia de datos puede aplicarse al análisis del mercado de alquiler turístico.

Posibles aplicaciones:

análisis de inversiones inmobiliarias

optimización de estrategias de precios

posicionamiento de alojamientos en el mercado

gestión profesional de propiedades turísticas

