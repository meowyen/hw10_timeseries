# Homework 10 - Time Series

## Time-Series Forecasting
- [Analysis notebook](time_series_analysis.ipynb)
- [Dataset](yen.csv)

### Based on your time series analysis, would you buy the yen now?

No, based on the time series analysis and Garch prediction, I would not buy the yen now. The Garch model predicts an increasing risk in the near term while the ARMA and ARIMA models aren't a good fit.

### Is the risk of the yen expected to increase or decrease?

The risk is expected to increase. The slope of the plot above is positive.

### Based on the model evaluation, would you feel confident in using these models for trading?

Based on the model evaluation, I would not feel confident in using the models because the p-values are greater than 0.05, indicating the models are not a good fit.

## Linear Regression Forecasting
- [Analysis notebook](regression_analysis.ipynb)
- [Dataset](yen.csv)

### Does this model perform better or worse on out-of-sample data compared to in-sample data?

The out-of-sample performance is better than the in-sample performance because the root mean squared error of out-of-sample model is lower.