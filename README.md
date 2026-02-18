# Airline Flight Delay Prediction
DATA 606 – Project Phase 1 (Project Pitch)

## Team Members
Gaurav Dali
Gopinath Mohanasundaram
Kortu Kiazolu

## Kaggle Team ID
(Add your Kaggle team ID here

## GitHub Repository
https://github.com/gopinathm188/DS606-Airline-Delay-Prediction

## Project Overview

This project develops a predictive analytics framework to analyze and forecast airline flight delays across U.S. airports.

We integrate:

- Monthly Airport-Carrier Delay Statistics (2013–2023)
- NOAA Storm and Weather Data

## Research Objectives

1. Regression:
   Predict total arrival delay minutes at the airport-month level.

2. Classification:
   Identify high-delay months using delay-rate thresholds.

3. Time-Series Forecasting:
   Forecast future delay trends using seasonal modeling.

## Datasets

### 1. Airline Delay Dataset
Source: Kaggle  
Records: ~171,000+  
Time Range: 2013–2023  
Link: https://www.kaggle.com/datasets/sriharshaeedala/airline-delay

### 2. NOAA Storm Events Dataset
Source: NOAA  
Records: 100,000+  
Link: https://www.ncei.noaa.gov/pub/data/swdi/stormevents/csvfiles/

## Planned Methods

Regression:
- Linear Regression
- Random Forest
- XGBoost

Classification:
- Logistic Regression
- Random Forest
- XGBoost

Time-Series:
- ARIMA
- Prophet

## Evaluation Metrics

Regression:
- RMSE
- MAE
- R²

Classification:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

Time-Series:
- MAE
- RMSE

## Repository Structure

- data/ → raw and processed datasets
- notebooks/ → Jupyter notebooks
- reports/ → figures and outputs
- presentation/ → slide decks
