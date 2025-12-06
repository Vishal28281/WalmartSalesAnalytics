# WalmartSalesAnalytics
Data-driven analysis of Walmart weekly sales across outlets using EDA, statistical tests, and outlier handling. Insights on unemployment, CPI, temperature, and seasonality with top/worst store performance. Predictive modeling applied to forecast sales for the next 12 weeks.


```markdown
# Walmart Sales Analysis & Forecasting 📊

## Overview
This project analyzes **weekly sales data** from Walmart outlets across the country. The goal is to uncover insights into how external factors such as unemployment rate, consumer price index (CPI), fuel price, temperature, and holidays impact sales performance. Using statistical analysis, exploratory data analysis (EDA), and predictive modeling, the project provides actionable insights and forecasts to improve inventory management and demand-supply alignment.

## Dataset Features
- **Store**: Store number  
- **Date**: Week of sales  
- **Weekly_Sales**: Sales for the given store in that week  
- **Holiday_Flag**: Indicates if the week includes a holiday  
- **Temperature**: Temperature on the day of sale  
- **Fuel_Price**: Fuel cost in the region  
- **CPI**: Consumer Price Index  
- **Unemployment**: Unemployment rate  

## Objectives
1. **Statistical & Exploratory Analysis**
   - Assess if weekly sales are affected by unemployment rate and identify impacted stores.
   - Detect seasonal trends in sales and analyze reasons behind them.
   - Evaluate the effect of temperature on weekly sales.
   - Study CPI’s influence on sales across stores.
   - Identify top-performing stores based on historical data.
   - Highlight the worst-performing store and compare performance gaps.

2. **Predictive Modeling**
   - Build forecasting models to predict sales for each store for the next **12 weeks**.
   - Compare model performance and select the most accurate approach.

## Below Tasks performed on the dataset --

1. You are provided with the weekly sales data for their various outlets. Use statistical
analysis, EDA, outlier analysis, and handle the missing values to come up with various
insights that can give them a clear perspective on the following:
   a. If the weekly sales are affected by the unemployment rate, if yes - which stores
   are suffering the most?
   b. If the weekly sales show a seasonal trend, when and what could be the reason?
   c. Does temperature affect the weekly sales in any manner?
   d. How is the Consumer Price index affecting the weekly sales of various stores?
   e. Top performing stores according to the historical data.
   f. The worst performing store, and how significant is the difference between the
   highest and lowest performing stores.
2. Use predictive modeling techniques to forecast the sales for each store for the next 12
weeks.

## Methodology
- **Data Cleaning**: Handle missing values and outliers.  
- **EDA**: Visualize trends, correlations, and seasonal patterns.  
- **Statistical Tests**: Validate relationships between sales and external factors.  
- **Modeling**: Apply regression, time-series forecasting, and machine learning techniques.  
- **Evaluation**: Use metrics like RMSE, MAE, and R² to assess model accuracy.  

## Outcomes
- Clear insights into how macroeconomic and environmental factors affect Walmart sales.  
- Identification of top and bottom performing stores.  
- Reliable forecasts to support inventory planning and demand management.  

## Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, Statsmodels)  
- **Visualization** (Matplotlib, Seaborn, Plotly)  
- **Forecasting** (ARIMA, Prophet, ML models)  

---

✨ This README gives your repo a professional edge and makes it clear to collaborators what the project is about.  

Would you like me to also add a **“Getting Started” section with installation and usage instructions** so others can easily run your project?
