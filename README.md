# Air-Quality-Index-AQI-Predictive-Analytics

# Overview

This project provides an end-to-end pipeline for Air Quality Index (AQI) prediction and forecasting. By leveraging environmental pollutant data, this analysis identifies key pollution drivers, handles non-linear relationships, and models long-term seasonal trends in urban air quality.

# Key Features

Robust Data Cleaning: Handles missing values, performs outlier analysis using IQR, and uses log-transformation to stabilize variance.
Feature Engineering: Extracts temporal features (Year, Month, Day) and implements seasonal encoding (Winter, Summer, Monsoon, Autumn).
Advanced Machine Learning: Compares performance across Linear Regression, Random Forest, and Gradient Boosting.
Time-Series Forecasting: Implements Facebook Prophet with external regressors (PM2.5, PM10, CO) to enhance prediction accuracy for urban centers.

# Analytics Highlights

Pollution Hotspots: Identified Delhi, Ahmedabad, and Patna as major pollution centers.
Primary Drivers: Correlation analysis revealed PM2.5 as the dominant contributor to AQI variability.
Seasonal Trends: Validated that AQI peaks during winter months, correlating strongly with colder temperatures and specific weather patterns.
Model Superiority: Tree-based regressors (Random Forest) significantly outperformed linear models, capturing complex pollutant interactions.


# Tech Stack

Language: Python
Data Processing: pandas,numpy
Visualization: seaborn,matplotlib
Machine Learning: scikit-learn
Forecasting: prophet

# Project Structure

├── dataset/
│   └── city_day.csv        # Primary air quality data
├── notebooks/
│   └── aqi_analysis.ipynb  # Full EDA, modeling, and forecasting
├── README.md
└── requirements.txt

# Insights for Stakeholders

Predictive Accuracy: Random Forest serves as the most reliable engine for real-time AQI estimation.
Policy Implication: Forecasting indicates that targeted reduction of PM2.5 emissions remains the most effective lever for improving overall air quality.

# Contact

Feel free to reach out if you have questions about the methodology or potential real-world applications of this predictive model.
