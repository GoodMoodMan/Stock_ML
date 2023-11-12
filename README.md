Project Description: Stock Price Prediction with Multiple Machine Learning Models, including LSTM

Overview:
The project aims to predict stock prices using various machine learning models, with a focus on LSTM (Long Short-Term Memory) networks. The dataset is obtained from Alpha Vantage, containing daily stock market data for a selected stock ticker. The implemented models include baseline models, linear models, dense models, convolutional models, and LSTM models. Additionally, a feedback LSTM model is implemented for multi-step predictions.

Dependencies:
TensorFlow (for building and training models)
Pandas (for data manipulation)
Matplotlib (for plotting)
NumPy (for numerical operations)
Seaborn (for data visualization)


Usage:
in the SETTINGS block,
Change 'ticker' to any stock
Change ALPHA VANTAGE API key if you wish to.

To implement new models, 
Create a WindowGenerator instance for data windowing, with wanted settings.



Create a new ML model using TF
use 'compile_and_fit' function on said Window and model.
use 'plot' on window using the model as is done in all the other models.

Note:
The project assumes that the necessary libraries and dependencies are installed.
The dataset retrieval from Alpha Vantage requires a valid API key.
The code includes comments for clarity and understanding.

Author:
Noam 
