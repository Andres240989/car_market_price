# car_market_price

## Busineess context

This project focuses on developing a machine learning model capable of predicting the market value of vehicles based on key features such as brand, model, year, mileage, fuel type, transmission, and other relevant characteristics.

## Objectives

The main objective is to provide customers with an accurate vehicle price estimation that allows them to compare their car’s value against current market prices. This solution can support both buyers and sellers in making more informed decisions within the automotive market.

This project focuses on developing a machine learning model capable of predicting the market value of vehicles based on key features such as brand, model, year, mileage, fuel type, transmission, and other relevant characteristics.

The main objective is to provide customers with an accurate vehicle price estimation that allows them to compare their car’s value against current market prices. This solution can support both buyers and sellers in making more informed decisions within the automotive market.

## Technologies used

- **Python** → Main programming language used for data analysis and model development.
- **Pandas & NumPy** → Data cleaning, manipulation, and numerical computations.
- **Matplotlib** → Data visualization and exploratory data analysis (EDA).
- **Scikit-learn** → Machine learning preprocessing, model training, and evaluation.
- **Linear Regression** → Baseline model used for initial performance comparison.
- **Random Forest Regressor** → Ensemble learning model used to improve prediction performance.
- **LightGBM** → Gradient boosting framework evaluated for prediction accuracy and training speed.
- **CatBoost** → Boosting algorithm tested for efficient handling of categorical variables and high predictive performance.
- **Statistical Analysis** → Descriptive statistics and parameter analysis applied to better understand data behavior and feature relationships.
- **Model Evaluation Metrics** → Used to compare model precision, accuracy, and computational efficiency.


## Methodology

1. **Data Collection**
   - Gathered vehicle market data including features such as brand, model, year, mileage, fuel type, transmission, and price.

2. **Data Cleaning & Preprocessing**
   - Removed missing or inconsistent values.
   - Handled duplicates and incorrect records.
   - Prepared categorical and numerical variables for modeling.

3. **Exploratory Data Analysis (EDA)**
   - Performed statistical analysis to identify patterns, correlations, and outliers.
   - Visualized data distributions and relationships using Matplotlib.

4. **Feature Engineering**
   - Selected the most relevant variables influencing vehicle prices.
   - Transformed and prepared features to improve model performance.

5. **Model Development**
   - Implemented multiple regression models for comparison:
     - Linear Regression (baseline model)
     - Random Forest Regressor
     - LightGBM
     - CatBoost

6. **Model Evaluation**
   - Compared models based on prediction accuracy, precision, and computational speed.
   - Selected the best-performing model according to business and technical requirements.

## improvements

- Deploy the best-performing model into a **Streamlit web application** to allow users to estimate vehicle market prices interactively.
- Develop an interactive **dashboard** with visual analytics and market insights for customers and business users. 

## Results & Key Findings

- Multiple regression models were trained and evaluated to identify the best balance between prediction accuracy and computational efficiency.
- **CatBoost Regressor** achieved the best overall performance among the tested models.
- The final CatBoost model produced an approximate prediction error of **2,144 USD** compared to the actual market value.
- The model also demonstrated high computational efficiency with an average response time of approximately **0.048 seconds**.
- **RMSE (Root Mean Squared Error)** was used as the primary evaluation metric to measure prediction accuracy and compare model performance.
- The results indicate that boosting-based algorithms provided better predictive performance than the baseline Linear Regression model.

## Business Insights

Business Insights

Although the primary objective of this project was to develop a vehicle valuation model with the lowest possible prediction error compared to market prices, the analysis also provides valuable insights that can support strategic business decision-making across commercial, financial, and marketing areas.

From a managerial perspective, the identification and analysis of outliers can help detect vehicles with unusually high or low market rotation. This information can be used to evaluate inventory performance, identify slow-moving vehicles, and design targeted commercial campaigns to stimulate vehicle sales and purchases.

Additionally, the analysis can support profitability assessments by identifying which vehicle categories or brands generate better market opportunities and profit margins. These insights can help businesses optimize pricing strategies, improve inventory management, and make more data-driven operational decisions.

This project combines predictive analytics with a business-oriented approach, demonstrating how data science can be applied not only for accurate forecasting but also for generating actionable insights that contribute to strategic management and decision-making

# Contexto de Negocio

Este proyecto se enfoca en desarrollar un modelo de machine learning capaz de predecir el valor de mercado de vehículos basándose en características clave como marca, modelo, año, kilometraje, tipo de combustible, transmisión y otras variables relevantes.

## Objetivos

El principal objetivo es proporcionar a los usuarios una estimación precisa del precio de un vehículo, permitiéndoles comparar el valor de su automóvil con los precios actuales del mercado. Esta solución puede apoyar tanto a compradores como vendedores en la toma de decisiones más informadas dentro del mercado automotriz.

## Tecnologías Utilizadas

- **Python** → Lenguaje principal utilizado para el análisis de datos y desarrollo del modelo.
- **Pandas & NumPy** → Limpieza, manipulación de datos y cálculos numéricos.
- **Matplotlib** → Visualización de datos y análisis exploratorio (EDA).
- **Scikit-learn** → Preprocesamiento, entrenamiento y evaluación de modelos de machine learning.
- **Linear Regression** → Modelo base utilizado para la comparación inicial de desempeño.
- **Random Forest Regressor** → Modelo de aprendizaje ensamblado utilizado para mejorar el rendimiento predictivo.
- **LightGBM** → Framework de gradient boosting evaluado por precisión y velocidad de entrenamiento.
- **CatBoost** → Algoritmo boosting probado por su eficiencia en el manejo de variables categóricas y alto rendimiento predictivo.
- **Análisis Estadístico** → Aplicación de estadísticas descriptivas y análisis de parámetros para comprender el comportamiento de los datos y relaciones entre variables.
- **Métricas de Evaluación** → Utilizadas para comparar precisión, exactitud y eficiencia computacional de los modelos.

## Metodología

1. **Recolección de Datos**
   - Se recopilaron datos del mercado automotriz incluyendo variables como marca, modelo, año, kilometraje, tipo de combustible, transmisión y precio.

2. **Limpieza y Preprocesamiento de Datos**
   - Eliminación de valores faltantes o inconsistentes.
   - Tratamiento de duplicados y registros incorrectos.
   - Preparación de variables categóricas y numéricas para el modelado.

3. **Análisis Exploratorio de Datos (EDA)**
   - Se realizó análisis estadístico para identificar patrones, correlaciones y outliers.
   - Visualización de distribuciones y relaciones entre variables utilizando Matplotlib.

4. **Ingeniería de Variables**
   - Selección de las variables más relevantes que influyen en el precio de los vehículos.
   - Transformación y preparación de variables para mejorar el desempeño del modelo.

5. **Desarrollo de Modelos**
   - Implementación de múltiples modelos de regresión para comparación:
     - Linear Regression (modelo base)
     - Random Forest Regressor
     - LightGBM
     - CatBoost

6. **Evaluación de Modelos**
   - Comparación de modelos basada en precisión predictiva, exactitud y velocidad computacional.
   - Selección del modelo con mejor desempeño según requerimientos técnicos y de negocio.

## Mejoras Futuras

- Desplegar el mejor modelo en una aplicación web desarrollada con **Streamlit** para permitir estimaciones interactivas del valor de vehículos.
- Desarrollar un **dashboard interactivo** con análisis visuales e insights de mercado para usuarios y clientes.

## Resultados y Hallazgos Clave

- Se entrenaron y evaluaron múltiples modelos de regresión para identificar el mejor equilibrio entre precisión predictiva y eficiencia computacional.
- **CatBoost Regressor** obtuvo el mejor desempeño general entre los modelos evaluados.
- El modelo final de CatBoost produjo un error aproximado de predicción de **2,144 USD** respecto al valor real de mercado.
- El modelo también demostró alta eficiencia computacional con un tiempo de respuesta promedio de aproximadamente **0.048 segundos**.
- Se utilizó **RMSE (Root Mean Squared Error)** como métrica principal para medir la precisión de las predicciones y comparar el desempeño de los modelos.
- Los resultados indican que los algoritmos basados en boosting ofrecieron un mejor rendimiento predictivo que el modelo base de Linear Regression.

## Business Insights

Aunque el objetivo principal de este proyecto fue desarrollar un modelo de valuación vehicular con el menor error posible respecto al mercado, el análisis realizado también proporciona información valiosa que puede apoyar la toma de decisiones estratégicas en áreas comerciales, financieras y de marketing.

Desde una perspectiva gerencial, la identificación y análisis de outliers puede ayudar a detectar vehículos con una rotación de mercado inusualmente alta o baja. Esta información puede utilizarse para evaluar el desempeño del inventario, identificar vehículos de baja rotación y diseñar campañas comerciales dirigidas para impulsar la compra y venta de vehículos.

Adicionalmente, el análisis puede apoyar evaluaciones de rentabilidad al identificar qué categorías o marcas de vehículos generan mejores oportunidades de mercado y mayores márgenes de ganancia. Estos insights permiten optimizar estrategias de precios, mejorar la gestión de inventario y tomar decisiones operativas basadas en datos.

Este proyecto combina analítica predictiva con un enfoque orientado al negocio, demostrando cómo la ciencia de datos puede aplicarse no solo para realizar pronósticos precisos, sino también para generar información accionable que contribuya a la gestión estratégica y la toma de decisiones.
  

