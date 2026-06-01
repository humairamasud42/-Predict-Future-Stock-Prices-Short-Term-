📌 Predict Future Stock Prices (Short-Term)

🎯 Objective
To predict the next day's stock closing price using historical stock market data and machine learning regression models.

📊 Dataset Used
- Source: Yahoo Finance
- Accessed using `yfinance` Python library
- Stock: Apple (AAPL)

✒️ Features:
- Open Price
- High Price
- Low Price
- Volume
- Close Price (Target shifted for prediction)

🧠 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- yfinance

📈 Methods Used

✔ Linear Regression Model  
✔ Train-test split (time series style)  
✔ Feature-based prediction  

🔍 Key Results & Findings

- Model learned general trend of stock movement
- Predictions follow overall direction of actual prices
- Some deviation exists due to market volatility
- Linear Regression works as a baseline model

🚀 Conclusion
This task helped understand time series forecasting basics and how machine learning can be applied to financial data.

📁 How to Run
```bash
python main.py
## 📁 How to Run
```bash
python main.py
