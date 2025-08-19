# Time-Series-Forecasting-Automotive-Stocks  

Time series forecasting of automotive stock prices using ARIMA, Prophet, XGBoost, LSTM, and a hybrid SARIMA–LSTM. Includes code, analysis, final report, and presentation.  

---

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

## Results  
- The **Hybrid SARIMA–LSTM** model outperformed all others, achieving the lowest error (**RMSE ≈ 0.54, MAPE ≈ 3.6%**).  
- Demonstrated trade-offs between interpretability (ARIMA/Prophet) and predictive power (XGBoost/LSTM).  

---

## Data Source  
Volkswagen ADR (VWAGY) historical stock price data was obtained from **[Investing.com](https://www.investing.com/equities/volkswagen-adr-historical-data)** for the period 2020–2025.  

---

## 📓 Methodology (Notebook)  
The Jupyter Notebook (`Volkswagen_Prediction_Modeling_&_Evaluation.ipynb`) performs the entire workflow:  

- **Data Cleaning**  
  - Date parsing, numeric conversion, and handling of percentages/volume suffixes.  
  - Missing values filled with medians.  

- **EDA**  
  - Price trends, seasonal effects, monthly averages, and volatility analysis.  

- **Forecasting Models**  
  - ARIMA/SARIMA with grid search.  
  - Prophet with yearly seasonality.  
  - XGBoost with lag features.  
  - LSTM with 30-step sequences and stacked architecture.  
  - Hybrid SARIMA–LSTM with residual correction.  

- **Evaluation**  
  - Metrics: RMSE & MAPE.  
  - Visualization of predictions vs. actuals and hybrid performance.  

---

## Tech & Tools  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Modeling Libraries**: statsmodels, prophet, scikit-learn, xgboost, tensorflow/keras, cmdstanpy  
- **Concepts**: Time Series Forecasting · Financial Data Analytics · Predictive Modeling · Data Visualization  

---

## Presentation  
[![Watch the Presentation](https://img.youtube.com/vi/YTk_70t6-jM/0.jpg)](https://www.youtube.com/watch?v=YTk_70t6-jM&ab_channel=TyrotheThird)  

---

## Team Members  
- Steven Sullivan  
- Robert Lignowski  
- Uditi Shah  
- Ahmad Javed  

---

*This project was developed as part of DSCI 592 at Drexel University (Spring 2025).*  
