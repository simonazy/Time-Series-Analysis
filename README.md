# Time-Series-Analysis

[Prediction the price of Microsoft stock](Time_series_predict_microsoft.ipynb)

#### Part 1
Before deciding which model to apply, we should first find out the time series scenarios, which can be recognized by asking the following questions:

**1.TS has a trend?**

+ If yes, is the trend increasing linearing or exponentially?

**2. TS has seasonality?**

+ If yes, do the seasonal components increase in magnitude over time?


**According to the above questions,there are nine Time Series Scenarios:**

+ No Trend, No seasonal
+ No Trend, Seasonal-Constant
+ No-Trend, Seasonal-Increasing
---
+ Trend-Linear, No seasonal
+ Trend-Linear, Seasonal-Constant
+ Trend-Linear, Seasonal-Increasing
---
+ Trend-Exponential, No-seasonal
+ Trend-Exponential, Seasonal-Constant
+ Trend-Exponential, Seasonal-Increasing

**The following are four ETS Models can help forcast thoes possible time-series scenarios**

+ Simple Exponential Smoothing Method
+ Holt’s Linear Trend Method
+ Exponential Trend Method
+ Holt-Winters Seasonal Method

Scenarios | No Seasonality | Seasonality
--- | --- | ---
No trend | Simpple Moving average or simple exponential smoothing | Holt-Winters no trend smoothing model or multiple regression
Trend | Double exponential smoothing | Holt-Winters additive or Holt-Winters multiplicative model

**But when to use additive and when to use mutiplicative model?** 


+ Trend-Linear, Seasonal-Constant
