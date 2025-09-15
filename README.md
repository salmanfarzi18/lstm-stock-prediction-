# 📈 LSTM Stock Price Prediction

This project demonstrates how Long Short-Term Memory (LSTM) neural networks can be used to forecast stock prices based on historical data. It’s designed to help investors, analysts, and researchers understand short-term market trends using deep learning.

---

## 📌 Project Overview

Stock price prediction is a challenging task due to market volatility and nonlinear patterns. This project builds an LSTM-based model that learns from past stock prices and predicts future values. It includes data preprocessing, model training, evaluation, and visualization.

---

## 🧠 Model Architecture

- **Input**: 60-day window of closing prices
- **Layers**:
  - LSTM (50 units, return sequences)
  - LSTM (50 units)
  - Dense (1 unit for output)
- **Loss Function**: Mean Squared Error
- **Optimizer**: Adam
- **Framework**: Keras with TensorFlow backend

---

## 📊 Results and Visualizations

- Plots of **training vs validation loss** to monitor learning
- Graph comparing **actual vs predicted prices**
- RMSE (Root Mean Squared Error) used to evaluate accuracy
- Predictions exported to `amzn_predictions.csv`
