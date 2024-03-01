# Stock Price Prediction with LSTM Model

This code implements a Long Short-Term Memory (LSTM) model to predict the future closing prices of a stock.

## Features

- Downloads historical stock data using pandas_datareader.
- Preprocesses data using MinMaxScaler for normalization.
- Builds an LSTM model with multiple layers and dropout for regularization.
- Trains the model on historical data and evaluates it on unseen test data.
- Visualizes the actual and predicted closing prices.

## Requirements

- Python 3.x
- NumPy
- pandas
- pandas-datareader
- matplotlib
- tensorflow

## Usage

1. **Install the Required Libraries**: Make sure you have all the required libraries installed. You can install them using pip:

2. **Update Company Variable**: Update the `company` variable with the desired stock symbol in the script.

3. **Adjust Data Retrieval Dates**: If needed, adjust the `start` and `end` dates for data retrieval in the script.

4. **Run the Script**: Execute the script. It will:
- Download historical data for the specified company.
- Train the LSTM model.
- Predict closing prices for the test period.
- Plot the actual and predicted closing prices.

## Disclaimer

Stock price prediction is inherently complex and involves a significant degree of uncertainty. This code is for educational purposes only and should not be used for making investment decisions.

