# Task 7: Sales Forecasting System

## Project Overview

A comprehensive time series forecasting system that predicts future sales using 5 machine learning models with 17 engineered features. Includes an interactive 4-page Streamlit dashboard for model comparison, customisable forecasting, and historical trend analysis.

**Status:** Complete and Production Ready
**Last Updated:** October 22, 2025

---

## Models

- Linear Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM

---

## Feature Engineering

17 features across 4 categories:
- **Temporal:** Day, Month, DayOfWeek, Quarter, Year, Weekend indicator
- **Lag Features:** Sales from 1, 7, 14, and 30 days ago
- **Moving Averages:** 7, 14, and 30-day rolling windows
- **Volatility:** Standard deviation for each rolling window

---

## Streamlit App

4 interactive pages:

- **Dashboard** — Model performance comparison with R² and RMSE charts, key metrics
- **Forecasting** — Select model, store, item, and forecast horizon up to 365 days with interactive Plotly charts and CSV download
- **Model Insights** — Best model details, feature group breakdown, model selection guide
- **Historical Data** — Sales trends over time, monthly aggregation, recent data viewer

---

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, Seaborn, Plotly, Streamlit, Joblib, Jupyter

---

## Screenshots

### Dashboard
Model performance comparison with R² score and RMSE visualisations.

![Dashboard](screenshots/sales_forcasting%20(1).png)

### Forecasting
Interactive sales forecasting with configurable model, store, and date range.

![Forecasting](screenshots/sales_forcasting%20(2).png)

### Model Insights
Detailed model comparison, feature importance, and selection guide.

![Model Insights](screenshots/sales_forcasting%20(3).png)

### Historical Analysis
Sales trends and monthly aggregation with interactive Plotly charts.

![Historical Analysis](screenshots/sales_forcasting%20(4).png)

### Additional Views
![Sales View](screenshots/sales_forcasting%20(5).png)
![Sales View](screenshots/sales_forcasting%20(6).png)
![Sales View](screenshots/sales_forcasting%20(7).png)
![Sales View](screenshots/sales_forcasting%20(8).png)
![Sales View](screenshots/sales_forcasting%20(9).png)
![Sales View](screenshots/sales_forcasting%20(10).png)

---

**Status:** Complete and Production Ready
**Live:** https://forcasting-sales.streamlit.app/
**Last Updated:** October 22, 2025
