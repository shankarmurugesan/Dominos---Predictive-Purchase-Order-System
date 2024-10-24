# Dominos - Predictive Purchase Order System

## Project Summary
The **Dominos - Predictive Purchase Order System** project focuses on predicting future pizza sales and generating an efficient purchase order system. The goal is to optimize the ordering process for ingredients by forecasting future demand. By accurately predicting sales, Dominos can avoid stockouts, minimize waste, and reduce the costs associated with excess inventory. This project leverages historical sales data and ingredient information to build a predictive model that informs the purchase order system.

## Problem Statement
Dominos aims to optimize the process of ordering ingredients by predicting future sales of pizzas. The project seeks to minimize inventory waste and prevent shortages by ensuring that the right amount of ingredients is ordered. Through accurate sales forecasting, Dominos can streamline its supply chain operations and improve inventory management.

## Business Use Cases
- **Inventory Management**: Ensure optimal stock levels without overstocking.
- **Cost Reduction**: Minimize waste and avoid costs due to expired or excess ingredients.
- **Sales Forecasting**: Predict sales trends and use them to make informed business decisions.
- **Supply Chain Optimization**: Improve the efficiency of ingredient orders based on sales predictions.

## Skills Learned
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Time Series Forecasting
- Predictive Modeling
- Business Decision Making
- Real-world Application of Data Science

## Domain
**Food Service Industry**

## Approach

### 1. Data Preprocessing and Exploration
- **Data Cleaning**: Cleaned the dataset by removing missing values, handling outliers, and reformatting data for analysis.
- **Exploratory Data Analysis (EDA)**: Analyzed historical sales trends, seasonality, and patterns. Visualized sales data to uncover significant features.

### 2. Sales Prediction
- **Feature Engineering**: Developed features based on day of the week, month, promotional periods, and holiday effects.
- **Model Selection**: Evaluated and selected the ARIMA model for time series forecasting. Other models considered include SARIMA, Prophet, and LSTM.
- **Model Training**: Trained the ARIMA model on the historical sales data.
- **Model Evaluation**: Evaluated the model using Mean Absolute Percentage Error (MAPE) for accurate prediction assessment.

### 3. Purchase Order Generation
- **Sales Forecasting**: Forecasted pizza sales for the next week based on the trained ARIMA model.
- **Ingredient Calculation**: Calculated the required quantities of each ingredient based on predicted sales and ingredient data.
- **Purchase Order Creation**: Generated a detailed purchase order listing the required ingredients for the forecasted sales period.

## Model Selected and Purpose
We selected the **ARIMA (AutoRegressive Integrated Moving Average)** model due to its ability to handle univariate time series data with trends and seasonality. The model was trained on historical sales data to predict future sales for the next week, enabling Dominos to optimize their purchase order process. The model's accuracy was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Technical Tags
- **Data Cleaning**
- **Exploratory Data Analysis (EDA)**
- **Time Series Forecasting** (ARIMA)
- **Predictive Modeling**
- **Inventory Management**
- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib/Seaborn**

## Datasets Used
- **Sales Dataset**: Contains historical sales records (Date, Pizza Type, Quantity Sold, Price, Category, Ingredients).
- **Ingredients Dataset**: Contains ingredient requirements for each pizza type (Pizza Type, Ingredient, Quantity Needed).



## Model Performance Results
- **Mean Absolute Error (MAE): 4.857
- **Mean Squared Error (MSE): 53.143
- **Root Mean Squared Error (RMSE): 7.290


## Conclusion
The ARIMA model was effective in predicting sales for Dominos, allowing the company to generate accurate purchase orders for ingredients based on future demand. This project demonstrates how predictive modeling and time series forecasting can improve business decision-making, particularly in optimizing inventory and reducing costs in the food service industry.
