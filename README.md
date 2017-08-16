# Time Series Forecasting on Visitors data of USA
---
***Summary:***

- Naive forecasting: Naive forecasting technique is technique in which the last period’s actuals are used as this period’s forecast, without adjusting them or attempting to establish causal factors. Mostly Naive model is used to compare it with forecasts generated by better modelling techniquess. Naive model is useful when we have less information about the process. It is useful because it discards all the observations and tracks the changes rapidly and also sets a benchmark to judge other models.

- Moving average method: This method is a calculation to analyze data points by creating series of averages of different subsets of the full data set. When the observations are near the base values moving average method proves useful. In terms of accuracy measure we can say that naive method performed the worst compared to rest of the methods.

- Simple Smoothing method: The simplest of the exponentially smoothing methods is naturally called “simple exponential smoothing” (SES). This method is suitable for forecasting data with no trend or seasonal pattern. Here greater weightage is given to the most recent observations of the time series. Simple Smoothing method gave better accuracy results than naive method and holt winters.

- ARIMA: : ARIMA models are, in theory, the most general class of models for forecasting a time series which can be made to be “stationary” by differencing, perhaps in conjunction with nonlinear transformations such as logging or deflating. A random variable that is a time series is stationary if its statistical properties are all constant over time. A stationary series has no trend, its variations around its mean have a constant amplitude, and it wiggles in a consistent fashion, i.e., its short-term random time patterns always look the same in a statistical sense. The latter condition means that its autocorrelations remain constant over time, or equivalently, that its power spectrum remains constant over time. A random variable of this form can be viewed as a combination of signal and noise, and the signal could be a pattern of fast or slow mean reversion, or sinusoidal oscillation, or rapid alternation in sign, and it could also have a seasonal component. An ARIMA model can be viewed as a “filter” that tries to separate the signal from the noise, and the signal is then extrapolated into the future to obtain forecasts.ARIMA models are applied in some cases where data show evidence of non-stationarity, where an initial differencing step can be applied one or more times to eliminate the non-stationarity. So in this casse it proves to be very stable and exhibits same pattern over the years.


## CONCLUSION: (1) ARIMA proved to be the best method to forecast and Naive proved to be the worst method (2) We can see from results that => time series value is increasing (3) Number of visitors is increasing as each year passes by
 
