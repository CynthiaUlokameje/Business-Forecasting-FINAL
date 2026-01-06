# Business Forecasting: Time Series Modeling and Forecast Evaluation for Sydney Tourism and Wheat Pricing

## Intro

This project applies modern time-series forecasting techniques to real-world economic and tourism datasets, with an emphasis on **model selection, interpretation, diagnostic testing, and forecast comparison**.

The analysis demonstrates the full forecasting workflow taught in the course, including data preparation, exploratory analysis, model estimation, residual diagnostics, and forecast evaluation.

---

## Data Sources

Two datasets were analyzed:

### Tourism Dataset
- Quarterly tourism visits by state and purpose
- Focused on the **Sydney region**
- Categories analyzed:
  - Business travel
  - Holiday travel

### Prices Dataset
- Annual inflation-adjusted prices for:
  - Eggs
  - Chicken
  - Copper
  - Nails
  - Oil
  - Wheat
  
- Analysis focused on **real wheat prices starting in 1890**

---

## About the Analysis

Each dataset was analyzed using multiple forecasting approaches to assess trend, seasonality, and predictive performance.

Key techniques include:

- Time series visualization
- Autocorrelation (ACF) and partial autocorrelation (PACF)
- Exponential smoothing (ETS)
- ARIMA modeling
- Regression with time-series components
- Forecast interval construction
- Residual diagnostics

---

## Assignment Requirements Addressed

### Question 1: Tourism Forecasting (Quarterly Data)

- Data filtering for Sydney (Business and Holiday travel)
- Visualization and descriptive analysis
- Simple exponential smoothing via ETS()
- Multiplicative seasonal ETS models
- Automated ETS model selection
- Multivariate regression with time-series components
- Forecast comparison using error metrics
- Residual diagnostics and white-noise testing

---

### Question 2: Wheat Price Forecasting (Annual Data)

- Inflation-adjusted price filtering from 1890 onward
- Stationarity assessment and transformation
- ACF and PACF interpretation
- Manual ARIMA model selection
- Automated ARIMA model comparison
- ETS model selection
- Forecast comparison across ARIMA and ETS models
- Final forecast generation and interpretation

---

## Key Findings

- ETS and ARIMA models perform differently depending on trend strength and seasonality.
- Automated model selection often aligns with manual ACF/PACF-based choices.
- Regression models provide interpretability but may underperform pure time-series models.
- Diagnostic testing is essential to confirm residuals resemble white noise.
- Forecast uncertainty increases substantially for long-horizon predictions.


---

## Tech Stack

- **R**
- **R Markdown**
- **fpp3/forecast**
- **ggplot2**
- **tidyverse**

