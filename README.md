Project Summary: FBI Time Series Forecasting

Introduction: Time series forecasting is a crucial analytical technique used to predict future data points based on historical trends. In the case of law enforcement, time series forecasting can help anticipate crime rates, detect patterns, and optimize resource allocation. This project aims to apply time series forecasting techniques to FBI crime data to predict future incident counts and support data-driven decision-making for law enforcement agencies.

Problem Statement:

Crime prediction is one of the most significant challenges faced by law enforcement agencies. Understanding crime trends over time can enable better policing strategies and resource distribution. However, crime data often exhibit seasonality, trends, and fluctuations, making accurate forecasting a complex task. This project leverages machine learning and statistical models to analyze and forecast crime incidents, enabling proactive crime prevention measures.

Objectives:

Perform exploratory data analysis (EDA) to understand crime trends.

Test stationarity and transform data accordingly.

Build and compare various time series forecasting models such as ARIMA, SARIMA, Prophet, and machine learning models like XGBoost.

Evaluate model performance using metrics like MAE, MSE, RMSE, MAPE, AIC, and BIC.

Provide insights into crime patterns to assist law enforcement agencies in strategic planning.

Data Overview: The dataset consists of two files:

Train Dataset: Contains historical crime incident counts with attributes such as Date, Incident_Counts, Month, and transformed features (log, square root, etc.).

Test Dataset: Lacks Incident_Counts, requiring forecasting techniques to predict future values.

Methodology 1️⃣ Exploratory Data Analysis (EDA):

Visualize trends, seasonality, and cyclic patterns in crime data.

Use different time series plots like line plots, seasonal decomposition, autocorrelation plots, and histograms.

2️⃣ Stationarity Testing & Transformation:

Apply Augmented Dickey-Fuller (ADF) and KPSS tests to check stationarity.

Apply differencing, log transformation, and moving averages to make the series stationary.

3️⃣ Feature Engineering & Data Preprocessing:

Create lag features, rolling averages, and seasonal indicators.

Handle missing values using rolling mean and forward fill techniques.

Scale and normalize data where required.

4️⃣ Time Series Forecasting Models:

Classical Models:

ARIMA: Captures autoregressive and moving average components.

SARIMA: Accounts for seasonality in the data.

VAR: Handles multivariate time series forecasting.

Machine Learning Models:

XGBoost: Boosting algorithm trained on time-based features.

Deep Learning Models:

LSTM: Neural network model designed for sequential data.

Hybrid Model:

Combining SARIMA with XGBoost to enhance predictions.

5️⃣ Model Evaluation:

Evaluate models using MAE, MSE, RMSE, and MAPE.

Compare AIC and BIC values for model selection.

6️⃣ Results & Insights:

Identify seasonal crime patterns and high-risk periods.

Provide recommendations based on crime forecasts for better law enforcement strategies.

Conclusion: This project demonstrates the application of time series forecasting techniques to FBI crime data. By leveraging statistical, machine learning, and deep learning models, we provide valuable insights into crime trends, helping authorities take proactive measures. The findings can assist in optimizing police patrolling, resource allocation, and crime prevention strategies.

