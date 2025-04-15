
# README FOR PRACTICALS
Practical_14 📈 RNN-Based Bitcoin Price Predictor
This project uses a **Recurrent Neural Network (RNN)** to predict future **Bitcoin prices** based on historical closing price data.
## 📂 Dataset
- **File:** `btc-1.csv`
- **Column Used:** `Close` (closing price of Bitcoin)
## 🧠 Model Architecture

- **Input:** 60 previous days of closing prices
- **Layer 1:** SimpleRNN (50 units)
- **Layer 2:** Dense (1 unit, output layer)
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam
## ⚙️ How It Works

1. Load and normalize the closing prices.
2. Create sliding windows of 60 days to use as input sequences.
3. Train an RNN to predict the price on day 61.
4. Evaluate predictions using:
   - Mean Squared Error (MSE)
   - Mean Absolute Error (MAE)
   - R² Score
5. Plot predicted vs actual prices.
6. (Optional) Confusion-matrix style heatmap for binned predictions.

## 📊 Evaluation Metrics

- **MSE**: How far predictions are from actual values (squared error).
- **MAE**: Average error in predictions.
- **R² Score**: How much of the variation in price is explained by the model (closer to 1 = better).

## 🔥 Visualization

- **Actual vs Predicted Price Plot**
- **Confusion-Matrix Style Heatmap** using binned values

## 🛠 Requirements_2

- Python 3.x
- numpy
- pandas
- matplotlib
- sklearn
- keras
  
---
  
PRATICAL-13 # 📈 RNN Alcohol Sales Prediction

This project uses a Recurrent Neural Network (RNN) to predict monthly alcohol sales based on past data. It's a regression problem solved using deep learning in Keras.
## 🧠 Model Architecture
- **Input**: Time series window of previous alcohol sales
- **RNN Layer**: SimpleRNN with 50 units
- **Dense Layer**: Output layer with 1 neuron for regression
## 📊 Evaluation Metrics
| Metric | Description |
|--------|-------------|
| **MSE** | Mean Squared Error |
| **MAE** | Mean Absolute Error |
| **R² Score** | How well future samples are likely to be predicted |
## 📈 Training vs Validation Loss Curve
A plot is generated to show model performance over 50 epochs.
## 📁 Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow / keras
## 🏃‍♂️ How to Run
```bash
pip install -r requirements.txt









