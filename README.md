# Busineess context

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

  

