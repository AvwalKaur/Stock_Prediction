# NVIDIA Stock Price Prediction Using Time Series Forecasting
This project is aimed at predicting the future stock price movements of NVIDIA Corporation using time series forecasting techniques. The project explores and compares the performance of three different models: LSTM (Long Short-Term Memory), RNN (Recurrent Neural Network), and Random Forest.
## Introduction
In this project, we forecast the stock prices of NVIDIA using historical price data. Stock price prediction is a complex problem due to the volatile nature of the stock market, and accurate predictions can be beneficial for investors.
## Dataset
The dataset consists of historical stock prices for NVIDIA, which includes features such as the opening price, closing price, high, low, and volume of the stocks.
Source: [NVDIA.csv]
## Models Used
### LSTM
LSTM is a type of Recurrent Neural Network (RNN) capable of learning long-term dependencies. It's well-suited for time series forecasting tasks like stock price prediction.
### RNN
RNNs are powerful for sequential data, as they have connections that form directed cycles, allowing information to persist.
### Random Forest
Random Forest is an ensemble learning method used for classification and regression. It builds multiple decision trees and merges them to get a more accurate and stable prediction.

## Result (Actual vs Predicted Graphs)
### LSTM Model
![st pred graph](https://github.com/user-attachments/assets/08cca14c-c91c-4d3f-bd65-b5974c2efd0b){width="250px"}
### RNN Model
![rnn prediction](https://github.com/user-attachments/assets/2ebd861e-43a3-4183-bf04-3353edea9cb6){width="250px"}
### Random Forest Model
![Random forest](https://github.com/user-attachments/assets/cb910a3b-1750-43a4-9cfe-ed75a8cb8174){width="250px"}



## Conclusion
The project demonstrates the effectiveness of using deep learning models like LSTM and RNN for time series forecasting, specifically in predicting stock prices. While Random Forest provided decent results, the deep learning models outperformed it in terms of prediction accuracy.
