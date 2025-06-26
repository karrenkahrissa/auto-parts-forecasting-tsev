# Automotive Parts Exports Forecasting with Exogenous Variables
Comparative study of Time Series models with exogenous variables (TSEV) for forecasting automotive parts sales under volatile economic drivers
This repository contains the implementation and results of a Bachelor's thesis project focused on improving sales forecasting for the automotive parts manufacturing sector using Time Series with Exogenous Variables (TSEV) models. The project supports robust scenario planning amid economic uncertainty, developed in collaboration with Atlantis Digital and Bontaz Groupe.

## Project Overview
Automotive parts manufacturers face significant challenges from external market shocks, including raw material price volatility, foreign exchange fluctuations, and the transition to electric vehicles. This project investigates the ability of different TSEV models to enhance forecasting accuracy by incorporating relevant external factors.

## Research Question
Which time series models that incorporate exogenous variables best predict automotive parts sales amid economic uncertainties and external market shocks?

## Models Implemented
The following forecasting models were compared:
* ARIMAX — AutoRegressive Integrated Moving Average with Exogenous Variables
* SARIMAX — Seasonal ARIMAX with Exogenous Variables
* ETSX — Error, Trend, Seasonality model with Exogenous Variables
* Prophet — Additive forecasting model by Meta with trend changepoint detection
* NeuralProphet — Neural network-enhanced extension of Prophet for improved short-term dynamics

## Key Features
* Forecasts EU automotive parts exports to the U.S. using key drivers
* Incorporation of exogenous variables:
  * EUR/USD exchange rates
  * Raw material prices (Iron, Aluminium)
  * Energy costs
  * U.S. Electric Vehicle (EV) sales
  * Hyperparameter optimization using Optuna
* Robust comparison based on forecasting accuracy and interpretability
* Scenario-ready framework designed to support strategic decision-making in volatile markets

## Packages Used
* `statsmodels` — ARIMAX, SARIMAX
* `prophet` — Prophet model
* `neuralprophet` — NeuralProphet model
* `optuna` — Hyperparameter optimization
* `scikit-learn` — Data preprocessing
* `matplotlib`, `seaborn` — Visualizations

## Evaluation Metrics
Model performance was assessed using: RMSE, MAE, sMAPE 
