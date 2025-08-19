# Time-Series-Forecasting-Automotive-Stocks
Time series forecasting of automotive stock prices using ARIMA, Prophet, XGBoost, LSTM, and hybrid SARIMA–LSTM. Includes code, analysis, final report, and presentation.

## Overview
This project explores time series forecasting techniques to predict automotive stock prices, with a focus on **Volkswagen ADR (VWAGY)** between 2020–2025.

We implemented and compared traditional statistical models and modern machine learning approaches to evaluate accuracy, interpretability, and forecasting power.  

**Models Used**
- ARIMA / SARIMA (classical time series)
- Prophet (additive modeling with seasonality)
- XGBoost (gradient boosting on engineered features)
- LSTM (deep learning recurrent networks)
- Hybrid SARIMA–LSTM (combining statistical + neural approaches)

---

## Key Contributions
- Cleaned, normalized, and preprocessed stock price data.  
- Conducted exploratory data analysis (EDA) to identify seasonality, volatility, and correlation patterns.  
- Implemented multiple forecasting models and evaluated performance using metrics such as **RMSE** and **MAPE**.  
- Visualized and compared forecast accuracy across models.  
- Collaborated in a 4-person team and presented results to faculty and peers.  

---

## Tech & Tools
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Modeling Libraries**: statsmodels, prophet, scikit-learn, xgboost, tensorflow/keras  
- **Concepts**: Time Series Forecasting · Financial Data Analytics · Predictive Modeling · Data Visualization
  
---

## Results
- The **Hybrid SARIMA–LSTM** model outperformed all others, achieving the lowest error (RMSE ≈ 0.54, MAPE ≈ 3.6%).  
- Demonstrated the trade-off between interpretability (ARIMA/Prophet) and predictive power (XGBoost/LSTM).  

---

## Team Members
- Steven Sullivan
- Robert Lignowski
- Uditi Shah
- Ahmad Javed

---

*This project was developed as part of DSCI 592 at Drexel University (Spring 2025).*
