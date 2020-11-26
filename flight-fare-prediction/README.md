# [Flight Fare Prediction MH](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh/)

## Table of Contents
- [Overview](#overview)
- [Notebooks](#notebooks)
- [Tools and Libraries Used](#tools-and-libraries-used)
- [Models and Eval Metrics](#models-and-eval-metrics)
- [Future Scope](#future-scope)

## Overview
Predicting the ticket air-fare given all the necessary features.

## Notebooks
- [EDA and Model](./fare-prediction.ipynb)

## Tools and Libraries Used
- Sklearn
- Viz libraries(Seaborn and Matplotlib)
- 

## Models and Test Metrics
| Model | RMSE | MSE %| R-Squared |
| :-: | :-: | :-: | :-: |
| Lasso Regressor | 3171.13 | 33 | 0.468 |
| Ridge Regressor | 3170.48 | 33 | 0.468 |
| K Neighbors Regressor | 2761.66 | 20 | 0.597 |
| Decision Tree Regressor | 1750.41 | 9 | 0.8381 | 
| Random Forest Regressor | 1254.14 | 8 | 0.9168 | 
| XGBoost Regressor | 1567.10 | 11.0 | 0.88 |

**Random Forest Regressor** & **XGB Regressor** are giving Maximum Accuracy as compare to other Regressor algorithm.

## Future Scope
- This model could be deployed using flask or django
- Neural Nets could be used to train a more optimal regressor model
- High performing models could lay a foundation to help hypertune to provide opitimal metrics 
