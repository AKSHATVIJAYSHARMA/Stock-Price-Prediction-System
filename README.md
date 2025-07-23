# Stock Price Prediction using LSTM

This project implements a stock price prediction system using an LSTM (Long Short-Term Memory) neural network in Python with TensorFlow/Keras. It includes full data preprocessing, feature engineering, model training, and evaluation using historical stock market data.

## 📁 Files Included

* `Stock-Price-Prediction.ipynb` — Jupyter Notebook with the complete workflow
* `prices.csv` — Historical stock prices
* `securities.csv` — Company metadata for each stock symbol
* `results.csv` — Model predictions vs actual closing prices
* `stock_weights1.keras` — Trained LSTM model weights

## 🚀 Features

* Reads and merges data from `prices.csv` and `securities.csv`
* Preprocesses time series data for LSTM model input
* Builds and trains an LSTM model using Keras
* Saves model weights for reuse
* Generates prediction results and compares with actuals
* Provides visualization of model performance

## 🧠 Model

* Uses a stacked LSTM architecture
* Trained on normalized historical closing prices
* Sequence length and model parameters can be tuned

## 🔧 Requirements

Install the following Python packages before running:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

## 📊 Results

The model is evaluated using Mean Squared Error (MSE) and visualized through comparison plots between predicted and actual stock prices.

## 📝 How to Use

1. Open `Stock-Price-Prediction.ipynb` in Jupyter.
2. Ensure the CSV and `.keras` files are in the same directory.
3. Run all cells sequentially.
4. Review the prediction performance and graphs.

## 📌 Notes

* Suitable for educational and experimental use.
* Not intended for live trading or financial decision-making without further validation.

---

Feel free to fork, contribute, and build upon this project!
