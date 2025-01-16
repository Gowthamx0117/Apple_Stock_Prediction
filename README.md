# Apple Stock Prediction using LSTM

This project implements a stock price prediction model for Apple (AAPL) using Long Short-Term Memory (LSTM) neural networks. The model is trained on historical stock data to predict future prices based on the past stock trends.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [How to Use](#how-to-use)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Project Overview

This project uses LSTM (Long Short-Term Memory) networks to predict the future stock prices of Apple (AAPL). We leverage the `yfinance` library to fetch historical stock data and preprocess it for the LSTM model, which is then used to predict future stock prices. The model is trained on historical stock prices, and the predictions are compared with actual values.

## Technologies Used

- **Python**: The main programming language.
- **TensorFlow/Keras**: For building the LSTM model.
- **yfinance**: For fetching historical stock data.
- **Matplotlib**: For data visualization and plotting the results.
- **scikit-learn**: For data preprocessing and splitting data into training and testing sets.

## Installation Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Gowthamx0117/apple-stock-prediction.git
   cd apple-stock-prediction
