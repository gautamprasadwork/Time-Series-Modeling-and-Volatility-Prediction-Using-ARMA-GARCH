# Time-Series-Modeling-and-Volatility-Prediction-Using-ARMA-GARCH
Predicting volatility and conditional mean of time series data using ARMA-GARCH models to better capture market dynamics and improve forecasts in R


# Reliance Stock and Nifty 50 Index

This project applies ARMA-GARCH modeling techniques to analyze and forecast the volatility of **Reliance Industries stock** and the **NIFTY 50 Index**. It aims to demonstrate volatility clustering, return forecasting, and risk analysis using real-world financial time series data.

## 📊 Objectives

- Model daily returns using ARMA and GARCH family models.
- Capture volatility clustering commonly seen in financial markets.
- Forecast short-term returns and conditional variance.
- Evaluate model performance using diagnostic tests (ACF, PACF, Ljung-Box, AIC/BIC, etc.).

## 🧠 Methods Used

- **ARMA (AutoRegressive Moving Average)**
- **GARCH (Generalized Autoregressive Conditional Heteroskedasticity)**
- Model selection using **AIC/BIC**
- Residual diagnostics and volatility plots

## 📌 Key Takeaways

- Volatility is persistent and clusters over time.
- GARCH models offer significant improvements over simple ARMA in modeling variance.
- Reliance stock exhibits higher conditional volatility compared to the Nifty index in the selected period.

## 🔧 Tools & Libraries

- R / Python (assumed based on report structure)
- `rugarch` / `arch` / `forecast` / `tseries`
- Jupyter / RMarkdown (for rendering the HTML report)


