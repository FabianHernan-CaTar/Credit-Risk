# Credit-Risk
# Análisis de Riesgo Crediticio (Credit Risk) 📊

## Descripción del Proyecto
Este proyecto se centra en la evaluación y predicción del riesgo crediticio utilizando técnicas de Machine Learning. A través de un análisis detallado de datos financieros, el objetivo es predecir la probabilidad de incumplimiento de pago (default), optimizando así la toma de decisiones en la concesión de créditos para maximizar la rentabilidad y reducir la exposición al riesgo.

El modelo principal utiliza un algoritmo de **Random Forest** para clasificar y predecir los resultados basándose en datos históricos.

## Estructura del Repositorio 📂
El flujo de trabajo está organizado en los siguientes archivos:

* `1_Data_Exploration_Cleaning.ipynb`: Limpieza de datos, tratamiento de valores atípicos y Análisis Exploratorio de Datos (EDA).
* `2_Data_Random_Forest.ipynb`: Entrenamiento, validación y evaluación del modelo predictivo.
* `LCDataDictionary.xlsx`: Diccionario de datos con la descripción detallada de cada variable financiera utilizada.
* `Resultados_vs_Realidad.csv`: Comparación directa entre las predicciones generadas por el modelo y los resultados reales del mercado.
* `requirements.txt`: Lista de librerías y dependencias necesarias para ejecutar los notebooks.

## Instalación y Requisitos ⚙️
Para ejecutar este proyecto localmente, clona el repositorio e instala las dependencias:

```bash
git clone [https://github.com/FabianHernan-CaTar/Credit-Risk.git](https://github.com/FabianHernan-CaTar/Credit-Risk.git)
cd Credit-Risk
pip install -r requirements.txt
