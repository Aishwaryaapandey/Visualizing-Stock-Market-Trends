# Visualizing Stock Market Trends
## Project Overview

This project provides a comprehensive pipeline to analyze and forecast stock prices using Microsoft (MSFT) as a case study. The workflow includes in-depth exploratory data analysis (EDA), a comparative analysis of three different forecasting models (LSTM, ARIMA, Prophet), and a 30-day future forecast based on the best-performing model. The entire project is designed to run seamlessly in a Google Colab notebook.

---

## Core Features

* **Advanced EDA:** Interactive candlestick charts, time-series decomposition, and rolling volatility analysis.
* **Comparative Modeling:** Trains and evaluates LSTM, ARIMA, and Prophet models side-by-side.
* **Quantitative Evaluation:** Compares models using RMSE, MAE, and MAPE metrics to identify the most accurate forecaster.
* **Future Forecasting:** Generates and visualizes a 30-day price forecast with uncertainty intervals.

---

## Tech Stack

`yfinance` | `pandas` | `matplotlib` | `plotly` | `scikit-learn` | `keras` | `statsmodels` | `prophet`

---

## How to Run

1.  **Open in Google Colab:** Upload the `.ipynb` notebook file.
2.  **Install Dependencies:** Run the first cell to install all required libraries.
    ```python
    !pip install yfinance pandas numpy matplotlib seaborn plotly scikit-learn tensorflow keras statsmodels prophet
    ```
3.  **Execute All Cells:** From the menu, select `Runtime` > `Run all` to execute the entire analysis pipeline.

---

## Future Work

* Implement hyperparameter tuning for the LSTM and ARIMA models.
* Incorporate multivariate analysis using additional features like volume and technical indicators.
* Build an interactive dashboard with Streamlit or Dash.
