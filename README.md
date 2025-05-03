**Ethereum Price Forecasting with ARIMA**

---

```markdown

## 📝 Project Overview
**Objective**: Predict Ethereum (ETH/USDT) prices using historical data and ARIMA models.  
**Approach**:
- Collected OHLCV data from Yahoo Finance API
- Performed exploratory data analysis (EDA)
- Tested stationarity with Augmented Dickey-Fuller (ADF)
- Built ARIMA models with optimal `(p,d,q)` parameters
- Generated 30-day forecasts with confidence intervals

---

## ✨ Key Features
✅ **Data Pipeline**  
- Automated data fetching from Yahoo Finance  
- Handling missing values with forward-fill  

✅ **Time Series Analysis**  
- ADF tests for stationarity  
- ACF/PACF plots for ARIMA parameter selection  

✅ **Model Evaluation**  
- RMSE and MAPE metrics  
- Visualizations of actual vs predicted prices  

✅ **Forecasting**  
- 30-day price predictions  
- 95% confidence intervals  

---

## ⚙️ Installations
1. Clone the repository:

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(Sample `requirements.txt`: pandas numpy matplotlib seaborn yfinance statsmodels scikit-learn)*

---

## 🚀 Usage
1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ETH_ARIMA_Forecasting.ipynb
   ```

2. Key Steps:
   - **Data Collection**: Fetch fresh data by running the first code cell.
   - **EDA**: Visualize trends, returns, and volatility.
   - **Model Training**: Execute ARIMA model cells.
   - **Forecasting**: Generate future predictions.

---

## 📊 Results
### Model Performance (Example)
| Metric | Value |
|--------|-------|
| RMSE   | 85.32 |
| MAPE   | 2.15% |

### Forecast Visualization
*(Add a screenshot of your forecast plot here)*  
![Forecast Plot](images/forecast.png) *(You'll add this)*

---

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

---

## 📜 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 📚 References
- [Yahoo Finance API](https://pypi.org/project/yfinance/)
- [Statsmodels ARIMA Documentation](https://www.statsmodels.org/stable/tsa.html)
- Hyndman & Athanasopoulos, *Forecasting: Principles and Practice*
```
