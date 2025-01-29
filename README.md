# Bike_Sharing
This is an Upgrad project to predict bike sharing demand

# Bike Rental Demand Prediction

## General Information
This project focuses on predicting bike rental demand using historical data. The goal is to build a machine learning model that helps bike rental companies optimize fleet management by forecasting demand based on various factors such as weather conditions, time of day, and seasonal trends.

## Business Problem
- Efficiently managing bike availability to reduce shortages or surpluses.
- Understanding key factors that influence rental demand.
- Enhancing user experience by ensuring bike availability during peak hours.

## Dataset
The dataset includes:
- **Temporal Data:** Hour, day, month, and season.
- **Weather Data:** Temperature, humidity, and wind speed.
- **Holiday & Working Day Indicators:** Helps understand demand fluctuations.
- **Bike Rental Counts:** Target variable representing total rented bikes.

## Conclusions
- Weather conditions (temperature and humidity) significantly impact bike rentals.
- Demand is higher on weekdays during commuting hours.
- Random Forest outperformed Linear Regression due to its ability to capture non-linear relationships.
- Residual analysis confirms that the final model provides reliable predictions.

## Technologies Used
- **Python (Jupyter Notebook)**
- **Pandas, NumPy** for data processing
- **Scikit-learn** for model training and evaluation
- **Matplotlib, Seaborn** for data visualization
- **Statsmodels** for statistical analysis
