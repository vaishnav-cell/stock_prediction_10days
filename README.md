 Stock Price Prediction using LSTM

This project focuses on predicting stock prices for the next 10 days using a **Long Short-Term Memory (LSTM)** neural network model. The notebook demonstrates the complete pipeline of data acquisition, preprocessing, model building, training, evaluation, and forecasting.

---

Project Overview

Stock market forecasting is a challenging task due to its non-linear and highly volatile nature. Deep learning methods such as **LSTM** are well-suited for time-series forecasting since they can capture long-term dependencies in sequential data.

This project applies an LSTM model to predict future stock closing prices based on historical data.  

---

Features

- Data collection using **Yahoo Finance API (yfinance)**  
- Data preprocessing (handling missing values, scaling, train-test split)  
- LSTM model design and training using **TensorFlow/Keras**  
- Visualization of training vs. validation loss  
- Prediction of stock prices for the next **10 days**  
- Graphical comparison of actual vs predicted prices  




---

Technologies Used

- Python 3.x  
- Google colab Notebook  
- NumPy, Pandas (Data Handling)  
- Matplotlib (Visualization)  
- scikit-learn (Preprocessing)  
- TensorFlow/Keras (Deep Learning)  
- yfinance (Stock Data Fetching)  

---

Workflow

1. **Data Acquisition** – Fetch historical stock data using `yfinance`.  
2. **Preprocessing** – Clean, normalize, and prepare sequences for the LSTM model.  
3. **Model Building** – Define and compile the LSTM architecture.  
4. **Training** – Fit the model on training data with validation.  
5. **Prediction** – Forecast next **10 days** stock prices.  
6. **Evaluation & Visualization** – Compare predicted vs. actual prices.  

---

Results

- The model successfully captures trends in stock prices.  
- Future predictions for the next 10 days are generated and visualized.  

Results

The model successfully captures trends in stock prices.  
Future predictions for the next 10 days are generated and visualized.  

![10-day Rolling Forecast](Screenshot%202025-09-07%20125303.png)


---




