# 📈 Yes Bank Stock Closing Price Prediction

![Yes Bank Stock](https://github.com/your-profile/Yes-Bank-Stock-Closing-Price-Prediction/image-link.jpg)

This project aims to predict the closing prices of Yes Bank stocks using various regression algorithms. The analysis explores how stock trends evolve over time, and multiple models are compared to find the best performing one for production.

---

## 📊 Project Overview

The project focuses on predicting stock prices based on historical data. Regression techniques were implemented to build models, and their performances were evaluated using error metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²).

![Stock Price Trend](https://github.com/your-profile/Yes-Bank-Stock-Closing-Price-Prediction/another-image-link.jpg)

---

## 📝 Key Steps

### 1. **Exploratory Data Analysis (EDA)**
- Visualized stock data to identify patterns, trends, and relationships.
- Cleaned data by handling missing values, outliers, and duplicate records.
- Applied data visualization techniques to better understand the features and target variable.
  
![EDA Visualization](https://github.com/your-profile/Yes-Bank-Stock-Closing-Price-Prediction/eda-image-link.jpg)

### 2. **Data Scrubbing & Pre-processing**
- Removed duplicates and missing values, and performed outlier detection.
- Normalized and standardized features to prepare the dataset for modeling.
- Split the data into training and test sets for evaluation purposes.

### 3. **Feature Engineering**
- Created new features such as Year, Month, and Quarter to enhance model accuracy.
  
![Feature Engineering](https://github.com/your-profile/Yes-Bank-Stock-Closing-Price-Prediction/feature-engineering-image-link.jpg)

### 4. **Model Implementation**
- Implemented and compared various regression models including:
  - Linear Regression
  - Ridge & Lasso Regression
  - Polynomial Regression
  - Random Forest Regressor
  - XGBoost Regressor
- Cross-validated each model and assessed their performance using error metrics.

### 5. **Model Explainability**
- Used SHAP (SHapley Additive exPlanations) to interpret feature importance and explain the model predictions.
- Discovered that OHL features and Year were the most significant contributors to stock price predictions.

---

## 📉 Final Model

After cross-validation and comparison, the **Random Forest Regressor** was selected as the optimal model due to its superior performance with a mean CV score of **95.77%**. The model was then saved using `joblib` for future predictions.

---

## 🔍 Insights & Conclusions

1. **Stock Trends**:
   - Significant price drop after 2018.
   - Sudden rise in stock price in 2014.
   
2. **COVID-19 Impact**: 
   - Less significant than expected; the 2020 scam had a more pronounced effect on stock prices.
   
3. **Model Performance**:
   - Lasso Regression outperformed Linear and Ridge Regression.
   - RandomForest and XGBoost models showed the best performance, with RandomForest being chosen for production.

---

## 📈 Visualizations

Throughout the project, multiple visualizations were created to support data analysis. Below are some key charts:

```python
# Example code for visualizing stock price trends
import matplotlib.pyplot as plt

plt.plot(df['Date'], df['Closing_Price'])
plt.title('Stock Closing Prices Over Time')
plt.xlabel('Date')
plt.ylabel('Closing Price')
plt.show()
