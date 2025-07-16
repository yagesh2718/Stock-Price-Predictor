# 📈 Stock Price Prediction using LSTM

This project focuses on using **Long Short-Term Memory (LSTM)** neural networks to predict future stock prices based on past historical data. The model is trained using monthly stock prices for companies like **MSFT, AMZN, IBM, GOOG, and AAPL** from **Jan 2000 to Mar 2010**.

---

## 📌 Features

- 🧠 Uses **LSTM model** for time series prediction  
- 📉 Trained on over 10 years of historical data  
- 🧪 Evaluates with **Root Mean Squared Error (RMSE)**  
- 📊 Visualizes predictions vs actual prices  
- 🔁 Includes sliding window dataset generation  

---

## 🧰 Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib  

---

## 📝 Dataset

- **Historical Monthly Stock Prices** from Jan 2000 to Mar 2010  
- Companies included:  
  - Microsoft (MSFT)  
  - Amazon (AMZN)  
  - IBM  
  - Google (GOOG)  
  - Apple (AAPL)  

> Format: `symbol, date, price`  
> You can customize the model to train on any one or all of the companies.

---

## ⚙️ Model Details

- **Architecture**:  
  - LSTM (64 units, ReLU)  
  - Dense output layer  
- **Window Size**: 12 months sliding window  
- **Loss Function**: Mean Squared Error  

---

## 🧪 Evaluation Metrics

- **Root Mean Squared Error (RMSE)**  
  - Example: `RMSE: 2.7134` (varies by stock)
- **Prediction Graph**: Actual vs Predicted prices  
- **Train/Test Split**: 80/20  

---

## 🚀 How to Run

### ✅ Steps to Run on Google Colab

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` notebook and the CSV dataset
3. Ensure the CSV file is named `stocks.csv` or change the path in code
4. Set the runtime type to **GPU** (optional, faster training)
5. Click `Runtime` > `Run All`

---

## 🎯 Possible Extensions

- Predict multi-stock prices simultaneously  
- Add external features (volume, indicators, etc.)  
- Use Bidirectional LSTM or GRU  
- Add a GUI using Streamlit  

---

## 👨‍💻 Developed By

**Yagesh Kumar Jha**  

> Designed and tested as part of ML mini-projects.

---

## 📎 License

This project is free to use and modify for academic or educational purposes.
