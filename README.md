# Neural_Networks
RNN LSTM models comparison

In this exercise I built two Recurrent Neural Network models using different types of input data. Namely, FNG (Crypto Fear and Grid Index) values and crypto closing prices. I compare both models to understand which one was a better predictor of future prices. 

### Tools used
To build both models I used resources from the **sklearn** package such as MinMax scaler to scale data points and the train_test_split method to easily split the available data. I also used keras via tensorflow to build a Sequential type of model and the layers method to build the deep learning models.

### Results
The closing price predictor model tracks the actual values better than the FNG predictor model.

The model based on closing prices had a lower loss than the model using FNG values. Hence the model using closing prices achieved more accurate prediction results.

