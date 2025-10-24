🚗 Tesla Stock Price Prediction — Final Report
🧠 Project Overview

✨This project focuses on predicting Tesla’s stock prices using time-series deep learning models.
✨It compares the performance of two neural network architectures — SimpleRNN and LSTM — on historical stock data.

📊 Data Source

✨Dataset: TSLA.csv (Tesla stock data)

✨Columns: Date, Open, High, Low, Close, Adj Close, Volume

✨Duration: 2010–2023

✨Missing Values: None detected ✅

⚙️ Methodology

✨Data preprocessing using Pandas and NumPy.

✨Normalization with MinMaxScaler.

✨Created 60-step time windows for sequence learning.

✨Built and trained two models:

🧩 SimpleRNN – baseline recurrent model

🧠 LSTM – advanced memory-based recurrent model

Compared their performance using Mean Squared Error (MSE).

📈 Results
Model	MSE (Mean Squared Error)
SimpleRNN	95.55
LSTM	22.56 ✅

✨Observation:
LSTM produced more accurate predictions with less error,
capturing complex time dependencies better than SimpleRNN.

📉 Visualization

✨Both models closely followed the actual Tesla stock price trend,
✨with LSTM showing smoother and more stable predictions.

🧾 Conclusion

✨LSTM outperformed SimpleRNN in stock price forecasting.

✨Demonstrates how deep learning can effectively model financial time-series data.

🎯Future Scope:

✨Incorporate additional features (Volume, Technical Indicators)

✨Use GRU or Transformer models

✨Extend prediction to multi-step (5-day / 10-day) forecasting

👨‍💻 Developed BY
Youraj Kumar
🎓 Computer Science — IIT Patna
💻 Tools Used: Python, Pandas, NumPy, Matplotlib, Scikit-Learn, TensorFlow, Keras
🧩 IDE: Jupyter Notebook
