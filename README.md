# Time-Series-Forecasting-and-Bit-Predict
This repository contains an introduction to the Time_series fundamentals in TensorFlow and also an end-to-end forecasting model that is going to predict the future price of Bitcoin, based on the historical price of Bitcoin. Time Series problems refer to certain computational problems where a time constraint affects the production results. It is generally of two types : classification and forecast. The model built in this notebook predicts future results based on past outcomes under a 'time' factor and follows a supervised learning approach meaning we'd have some example data and a label associated with that data.

## What we are going to cover (broadly):

1. Get time series data (the historical price of Bitcoin)
  * Load in time series data using pandas/Python's CSV module
2. Format data for a time series problem
  * Creating training and test sets (the wrong way)
  * Creating training and test sets (the right way)
  * Visualizing time series data
  * Turning time series data into a supervised learning problem (windowing)
  * Preparing univariate and multivariate (more than one variable) data
3. Evaluating a time series forecasting model
4. Setting up a series of deep learning modelling experiments
  * Dense (fully-connected) networks
  * Sequence models (LSTM and 1D CNN)
  * Ensembling (combining multiple models together)
  * Multivariate models
  * Replicating the N-BEATS algorithm using TensorFlow layer subclassing
5. Creating a modelling checkpoint to save the best performing model during training
6. Making predictions (forecasts) with a time series model
7. Creating prediction intervals for time series model forecasts
8. Discussing two different types of uncertainty in machine learning (data uncertainty and model uncertainty)
9. Demonstrating why forecasting in an open system is BS (the turkey problem)

