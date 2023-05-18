Implemented a stock price prediction model using deep learning techniques. The process involved the following steps:

1. Data Collection: Retrieved historical stock data from Yahoo Finance using the `yfinance` library.

2. Data Preprocessing: Split the data into training and test sets. Applied standard scaling to normalize the data.

3. Model Architecture: Built a 4-layer LSTM model with Adam and RMSprop optimizers, as well as a 4-layer GRU model with SGD and RMSprop optimizers.

4. Model Training: Trained the LSTM and GRU models on the training set.

5. Evaluation: Calculated the mean squared error (MSE) to assess the performance of the models.

Results:
- 4-layer LSTM with Adam: MSE = [MSE value]
- 4-layer LSTM with RMSprop: MSE = [MSE value]
- 4-layer GRU with SGD: MSE = [MSE value]
- 4-layer GRU with RMSprop: MSE = [MSE value]

