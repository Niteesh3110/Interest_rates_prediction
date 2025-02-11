# Interest Rate Prediction

## 📌 Project Overview
This project predicts **U.S. Federal Funds Effective Interest Rates** from historical data using **Machine Learning** and **Deep Learning** models. The dataset comes from the [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/series/FEDFUNDS).

## 📂 Dataset
- **Source**: Federal Reserve (FRED)
- **Time Range**: July 1954 – October 2024
- **Target Variable**: FEDFUNDS (Interest Rate)

## 🔧 Data Preprocessing
- Converted date columns to datetime format
- Handled missing values
- Visualized historical interest rate trends

## 📊 Models Used
- **RandomForestRegressor** 🌲
- **XGBRegressor** ⚡
- **ARIMA (AutoRegressive Integrated Moving Average)** ⏳
- **LSTM (Long Short-Term Memory Neural Network)** 🧠
- **GRU (Gated Recurrent Unit)** 🔄

## 📈 Evaluation Metrics
- **Mean Squared Error (MSE)** 📉
- **Mean Absolute Error (MAE)** 📊

## 🚀 How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Interest-Rate-Prediction.git
   cd Interest-Rate-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook CS583_FinalProject_Team2_Partial.ipynb
   ```

## 📬 Contact
For inquiries, reach out via [LinkedIn](https://www.linkedin.com/in/niteeshpanchal).
