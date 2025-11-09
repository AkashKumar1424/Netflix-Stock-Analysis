#  Netflix Stock Analysis – Predictive Modeling with Python & Tableau

An end-to-end **data analytics project** exploring **Netflix (NFLX)** stock performance (2002–2025).  
The project applies data cleaning, visualization, and machine learning models to understand stock behavior, volatility patterns, and predictive performance.

---

## 🚀 Objectives

- Identify long-term price growth and volatility trends  
- Examine whether trading volume predicts large price movements  
- Build predictive models to forecast short-term price changes  

---

## 🧰 Tech Stack

**Languages & Libraries:**  
`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`, `Statsmodels`  

**Visualization:**  
`Tableau` (interactive dashboards)  

**Techniques Used:**  
Feature Engineering · Regression · Time-Series Forecasting · Cross-validation  

---

## 📈 Models Implemented

| Model | RMSE | MAE | R² | Improvement vs Baseline |
|--------|------|-----|----|--------------------------|
| Naive Baseline | 15.19 | 10.72 | 0.75 | — |
| Ridge Regression | 11.47 | 7.60 | 0.86 | **+24.5%** |
| ARIMA(1,0,0) | 15.18 | 10.65 | 0.75 | +0.07% |

> 🧠 **Ridge Regression** outperformed the baseline with ~25% better RMSE, while ARIMA performed similarly to Naive.

---

## 🔍 Key Insights

- 📊 Netflix stock volatility peaked during major market events (2008 financial crisis & COVID-19).  
- 📈 High trading volume days were linked to significant price swings (≥ ±3%).  
- 💡 Ridge Regression offered a measurable forecasting edge, proving feature engineering’s impact.  
- 🔔 Confidence intervals highlighted higher uncertainty during volatile periods.  

---

## 📊 Visualizations

- Price trends with short-term & long-term moving averages  
- Rolling volatility (20-day)  
- Volume vs. Big Moves analysis  
- Correlation heatmap of engineered features  
- Actual vs Predicted comparison plots  

*(You can include screenshots here — e.g., your Tableau dashboard or regression plot.)*

---

## 🧩 Next Steps

- Add external factors (e.g., market indices, earnings events, sentiment analysis)  
- Explore nonlinear ML models such as **XGBoost** and **LSTM**  
- Build a real-time dashboard for live stock analysis  

---

## 📂 Project Files

| File | Description |
|------|--------------|
| `report.pdf` | Complete project report |
| `notebook.ipynb` | Python analysis & model code |
| `dashboard.twbx` | Tableau visualization dashboard |
| `presentation.pptx` | Presentation slides overview |

---

## 📬 Connect with Me

💼 **LinkedIn:**www.linkedin.com/in/akash-kumar-28b747277


If you find this project helpful, feel free to ⭐ **star the repo** or share your thoughts!  

---

### 🏷️ Tags
#DataAnalytics #Finance #Python #MachineLearning #Tableau #Netflix #StockMarket #PredictiveModeling #Visualization
