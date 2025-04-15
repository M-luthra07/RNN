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









