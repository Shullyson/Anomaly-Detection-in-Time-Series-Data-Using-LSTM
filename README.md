# LSTM-Based Time Series Analysis

## Overview
This project leverages Long Short-Term Memory (LSTM) networks for time series analysis, with a primary focus on anomaly detection in financial data. The model is trained to identify unusual patterns in stock market prices using historical data.

## Features
- Uses LSTM networks for sequence prediction and anomaly detection
- Implements data preprocessing including normalization and feature engineering
- Visualizes detected anomalies using matplotlib
- Trained on stock market historical data sourced from Yahoo! Finance

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Shullyson/Anomaly-Detection-in-Time-Series-Data-Using-LSTM.git
   cd  cd Anomaly-Detection-in-Time-Series-Data-Using-LSTM
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your dataset and update the `data.csv` file.
2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook code-lstm.ipynb
   ```
3. Train the model and analyze results.

## Dataset
- The project uses historical stock market data sourced from [Yahoo! Finance](http://finance.yahoo.com/).
- Ensure your dataset follows the required format before training.

## References
- [Keras LSTM for Time Series](https://keras.io/examples/timeseries/timeseries_anomaly_detection/)

## License
