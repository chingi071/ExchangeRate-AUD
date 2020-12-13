Many foreign exchange traders believe that past market price changes can be used to predict future exchange rates. There are many ways to predict exchange rates, including traditional time series and machine learning.

# Traditional time series
In traditional time series prediction method, the data has to be stationized before making predictions. There are two ways to make these data stationary: make a difference (ARIMA), decompose the data (SARIMA). Autoregressive integrated moving average (ARIMA) is the traditional time series model used by people to predict time series in the early days. Seasonal Autoregressive Integrated Moving Average model (SARIMA) is the variant of ARIMA and one of the methods for predicting the seasonal series.

# Machine learning
However, with the improvements in computing and processing, machine learning is becoming more popular. People use artificial neural network to predict the time series. Compared to traditional time series models, the past research works showed that the prediction performance of using machine learning models is better than other alternatives.

In order to accurately grasp the exchange rate, many studies use deep network models to make predictions and expect better results. Long Short-Term Memory (LSTM) is widely used by the public for prediction and has better performance than other models. To further improve the performance, scholars have designed variants of LSTM, LSTM attention, which performs better in many areas than other traditional deep network.

# 
In our experiments, we used these models to predict the exchange rate of Australia against the US dollar, such as ARIMA, SARIMA, ANN, LSTM and LSTM attention.
