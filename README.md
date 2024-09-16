# 🔬 Regression Analysis On Yes Bank Stock Closing Price Prediction
--------------------------------------------------------------------------------------------

This repository contains the code and dataset for predicting the closing price of Yes Bank stock using regression analysis. The project uses a dataset containing historical stock prices of Yes Bank from 2005 to 2020.

--------------------------------------------------------------------------------------------

## 📋 Abstract

This study aims to predict the closing price of Yes Bank stock using regression analysis. The dataset includes historical stock prices of Yes Bank from **July 2005 to November 2020**, with variables such as opening price, highest price, lowest price, and closing price.

We applied **multiple regression techniques**, including **Random Forest** and **XGBoost**, to predict stock prices. The models are evaluated using **root mean squared error (RMSE)** and **mean absolute error (MAE)**. Cross-validation was also used to finalize the model. Results show that Random Forest performed best in terms of accuracy, while XGBoost also provided competitive results.

--------------------------------------------------------------------------------------------

## 💾 Project Files Description

This project includes the following files:

- **Google Colab Notebook**: Contains all code and steps.
- **Project Summary**: Includes the complete project details and GitHub Repo link.
- **Presentation Video**: A video walkthrough of the project.
- **Dataset**: Historical stock prices of Yes Bank from **AlmaBetter**.
    - `data_YesBank_StockPrices.csv`: Monthly stock data with open, high, low, close, and date.
- **Model Implementation**: Python scripts for regression analysis and model deployment.

--------------------------------------------------------------------------------------------

## 🗺️ Roadmap and Navigation Guide

1. **Data Collection**: Gather historical stock prices from **January 2005 to September 2020**.
2. **Data Cleaning and Preprocessing**: Remove missing values, outliers, and errors, and preprocess the data.
3. **Model Building**: Implement models like **Multiple Linear Regression**, **Support Vector Regression (SVR)**, **Random Forest**, and **XGBoost**.
4. **Model Evaluation**: Evaluate using **RMSE**, **MAE**, and **cross-validation**.
5. **Results and Conclusion**: Discuss the model performance and choose the best for deployment.

--------------------------------------------------------------------------------------------

## 🛠️ Built With

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Plotly**
- **Google Colab**

--------------------------------------------------------------------------------------------

## 📜 Conclusion

After comparing six regression models, we concluded that **Optimal_RandomForest** and **XGBRegressor** are the top-performing models. Considering cross-validation scores and time complexity, **Optimal_RandomForest** was chosen as the final model for deployment.

--------------------------------------------------------------------------------------------

## 💶 Credits

Feel free to reach out through the following platforms:

- **[GitHub](
