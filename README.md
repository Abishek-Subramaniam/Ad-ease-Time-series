# Ad-ease-Time-series
Ad Ease is an ads and marketing based company helping businesses elicit maximum clicks @ minimum cost. AdEase is an ad infrastructure to help businesses promote themselves easily, effectively, and economically. 

Observations

Problem Statement:

The main goal is to forecast the daily view counts on various Wikipedia pages to optimize ad placements for Ad Ease’s clients.

Usage Scenarios:

Advertising Optimization: Businesses can use this forecasted data to time and place their ads for maximum engagement.

Content and Media Planning: Content providers can target high-traffic pages to drive awareness or releases during peak times.

*Decomposition of Series *

Trend: The long-term direction of the data, showing an overall increase or decrease over time.

Seasonality: The repeated patterns or cycles in the data at regular intervals, such as daily, weekly, or monthly.

Differencing

Differencing was applied once (i.e., first-order differencing) in most cases to achieve stationarity. However, some series with strong seasonality might require seasonal differencing or second-order differencing depending on the outcome of the Augmented Dickey-Fuller (ADF) test.

ARIMA (AutoRegressive Integrated Moving Average): Models a time series based solely on its own past values (autoregression) and past forecast errors (moving average). It assumes the data is stationary.

SARIMA (Seasonal ARIMA): Extends ARIMA by adding seasonal components to handle seasonality in the data. It includes additional parameters for seasonal autoregression, seasonal differencing, and seasonal moving average.

SARIMAX (Seasonal ARIMA with Exogenous Regressors): Further extends SARIMA by incorporating external variables (exogenous variables) that might affect the time series, such as campaign data, which can improve model accuracy.

