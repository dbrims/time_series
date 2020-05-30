# Time Series Homework
### Time series Analysis

* Based on your time series analysis, would you buy the yen now? Based on these analyses, it is inconclusive, the ARMA model says the yen will decrease but the ARIMA model says it will increase. These data almost act like white noise with no correlation between trials

* Is the risk of the yen expected to increase or decrease? Based ont he GARCH model, the volitility and thus risk for the Yen is expected to increase over the coming days

* Based on the model evaluation, would you feel confident in using these models for trading?
based on the statistics surrounding these models I would not trust them. The data itself lacks correlation which when doing autocorrelation modeling would be a nice thing... and the resulting statistics of the models do not support rejection of H(o)

### Regression analysis

* The model performs better on the test data compared to the training data. this makes sense since the training data is <2019, and the magnitude of the variability much higher, based on both visual inspection of the data and it has a higher standard deviation compared to the test set(.566 vs .415). That decreased precision is reflected in the higher rmse.