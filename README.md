# Stock Price Prediction with LSTM (TensorFlow)

This code implements a stock price prediction model using LSTM (Long Short Term Memory) networks in TensorFlow.

## Why LSTM?

- Stock prices form time-series data where future values depend on past values.

- Traditional models struggle to capture long-term dependencies (e.g. price trends that span weeks/months).

- LSTM networks have memory cells that store information over long sequences, allowing the model to remember important patterns from far back in time.

- Its gates (input, forget, output) control what information to keep or discard, preventing issues like the vanishing gradient problem that affects basic RNNs.

- This makes LSTMs capable of learning both short-term fluctuations and long-term trends in stock movements.

- Ultimately, LSTM can identify repeating patterns, momentum shifts, and seasonality, which are critical in financial forecasting.
  
## Tools & Technologies

- **Python** — for scripting and data handling
- **TensorFlow (Keras)** — for building and training the LSTM model
- **Pandas & NumPy** — for data preprocessing
- **Matplotlib** — for visualizing model performance

## Key Highlights

- Built an end-to-end pipeline: data preprocessing, model training, evaluation, and visualization.
- Demonstrates practical application of deep learning in financial data prediction.
- Focused on clean code, modular design, and reproducibility.

---

> **Note:** This project is for learning purposes only and not intended for actual financial trading.

