# TimeSeriesAnalysis


## Components of a Time-Series <br/>
![image](https://github.com/user-attachments/assets/35566dfd-9ba8-489c-bdfe-1b3a04b88eaf) <br/>
A. Trend - The trend shows a general direction of the time series data over a long period of time. A trend can be increasing(upward), decreasing(downward), or horizontal(stationary). <br/>

![image](https://github.com/user-attachments/assets/e57425d8-9d7b-4a57-807d-471b2d96a159) <br/>
B. Seasonality - The seasonality component exhibits a trend that repeats with respect to timing, direction, and magnitude. Some examples include an increase in water consumption in summer due to hot weather conditions. <br/>

![image](https://github.com/user-attachments/assets/68f15fdc-1079-4789-b7d2-3155c11c2e19) <br/>
C. Cyclical Component - These are the trends with no set repetition over a particular period of time. A cycle refers to the period of ups and downs, booms and slums of a time series, mostly observed in business cycles. <br/> These cycles do not exhibit a seasonal variation but generally occur over a time period of 3 to 12 years depending on the nature of the time series. <br/>

![image](https://github.com/user-attachments/assets/57b127ba-4105-4f93-832a-7674776e8644) <br/>
D. Irregular Variation - These are the fluctuations in the time series data which become evident when trend and cyclical variations are removed. These variations are unpredictable, erratic, and may or may not be random. <br/>

E. ETS Decomposition - ETS Decomposition is used to separate different components of a time series. The term ETS stands for Error, Trend and Seasonality. <br/>

# Types of data <br/> 

A time series data means that data is recorded at different time periods or intervals. The time series data may be of three types: <br/>

1. Time series data - The observations of the values of a variable recorded at different points in time is called time series data. <br/>

2. Cross sectional data - It is the data of one or more variables recorded at the same point in time. <br/>

3. Pooled data- It is the combination of time series data and cross sectional data. <br/>


## Time Series Terminology<br/>

1. Dependence - It refers to the association of two observations of the same variable at prior time periods.<br/>

2. Stationarity - It shows the mean value of the series that remains constant over the time period. If past effects accumulate and the values increase towards infinity then stationarity is not met.<br/>

3. Differencing - Differencing is used to make the series stationary and to control the auto-correlations. There may be some cases in time series analyses where we do not require differencing and over-differenced series can produce wrong estimates.<br/>

4. Specification - It may involve the testing of the linear or non-linear relationships of dependent variables by using time series models such as ARIMA models.<br/>

5. Exponential Smoothing - Exponential smoothing in time series analysis predicts the one next period value based on the past and current value. It involves averaging of data such that the non-systematic components of each individual case or observation cancel out each other. The exponential smoothing method is used to predict the short term prediction.<br/>

6. Curve fitting - Curve fitting regression in time series analysis is used when data is in a non-linear relationship.<br/>



Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
