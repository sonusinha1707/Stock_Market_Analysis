# 📊 Stock Market Analysis and Forecasting Dashboard

![banner](https://github.com/sonusinha1707/Stock_Market_Analysis/blob/main/stock_market_analysis.png)

An advanced end-to-end dashboard powered by Python and Power BI to analyze and forecast stock prices for top NASDAQ-100 companies using real-time data and machine learning.

---

## 📖 Table of Contents
1. [About the Project](#about-the-project)  
2. [Project Objectives](#project-objectives)  
3. [Technologies Used](#technologies-used)  
4. [Data Source](#data-source)  
5. [Dashboard Features](#dashboard-features)  
6. [Machine Learning Model](#machine-learning-model)  
7. [How the Dashboard Works](#how-the-dashboard-works)  
8. [Challenges Faced](#challenges-faced)  
9. [Testing and Validation](#testing-and-validation)  
10. [Future Scope](#future-scope)  
11. [Conclusion](#conclusion)  
12. [📸 Dashboard Images](#dashboard-images)

---

## 🔗 GitHub Repository
[**GitHub Repository: StockMarket_Analysis**](https://github.com/Nikitachatse/StockMarket_Analysis)

### 📁 Repository Contents
- 🐍 Python scripts for data collection, preprocessing, and machine learning.
- 📂 Power BI files (`.pbix`) for interactive dashboards.
- 📄 Project documentation.
- 🖼️ Visual previews of the dashboard.

---

## 📚 About the Project
The **Stock Market Analysis and Forecasting Dashboard** is an interactive tool that provides in-depth insights into stock trends, performance metrics, and future forecasts for 10 major NASDAQ-100 companies. Using the `yfinance` API and XGBoost regression, this project empowers analysts and investors with accurate predictions and business intelligence through dynamic Power BI dashboards.

### 🏢 Companies Analyzed
- Amazon (AMZN)  
- Apple (AAPL)  
- Meta (META)  
- PayPal (PYPL)  
- Cisco (CSCO)  
- Microsoft (MSFT)  
- Google (GOOGL)  
- Intel (INTC)  
- Tesla (TSLA)  
- NVIDIA (NVDA)

---

## 🎯 Project Objectives
- Provide an intuitive dashboard for exploring historical and current stock data.
- Forecast short-term stock prices using machine learning.
- Enable near real-time data integration with dynamic updates.

---

## 🛠️ Technologies Used
- **Power BI** – Interactive dashboard creation and visualization.
- **Python** – Data pipeline, modeling, and integration with Power BI.
- **yfinance** – Real-time and historical stock data fetching.
- **XGBoost** – Machine learning model for regression and forecasting.
- **scikit-learn** – Model evaluation and data preprocessing.
- **ta (Technical Analysis)** – Feature engineering using RSI, SMA, etc.

---

## 📂 Data Source
Historical daily stock data (1984–Present) was collected via the `yfinance` API, including:
- Opening and closing prices
- High and low prices
- Adjusted close
- Trading volume
- Technical indicators (SMA, RSI)

---

## ✨ Dashboard Features
1. **📡 Real-time Data Integration**  
   Embedded Python scripts fetch and refresh data dynamically.

2. **📊 Interactive Visualizations**  
   - Time-series trends (daily, monthly, yearly)
   - Stock performance comparisons
   - Treemaps, line charts, candlesticks

3. **📈 Forecasting Section**  
   - 7-day predictive analytics for selected companies using XGBoost

4. **🔍 Detailed Insights**  
   - Company-specific drill-downs
   - EPS and % price change comparisons

5. **⚡ Seamless Filtering**  
   - Slicers for company, time range, performance metrics

---

## 🤖 Machine Learning Model

### 🚀 Model Workflow
- **Preprocessing**:  
  - Null value handling  
  - Feature engineering: SMA, RSI, lag variables  

- **Model Training**:  
  - XGBoost Regressor with tuned hyperparameters  
  - Evaluation using RMSE and MAE  

- **Forecasting**:  
  - Predict next 7 trading days  
  - Rolling updates for live prediction

- **Power BI Integration**:  
  - Model and predictions integrated via Python scripting

---

## ⚙️ How the Dashboard Works
1. **Data Collection**:  
   Real-time and historical stock data fetched using `yfinance`

2. **Preprocessing and Modeling**:  
   Python scripts generate indicators and run XGBoost model

3. **Live Forecast Updates**:  
   Python embedded in Power BI triggers live data and prediction refresh

4. **User Exploration**:  
   Interactive filters allow custom views per company or metric

---

## 🚧 Challenges Faced
| Challenge | Solution |
|----------|----------|
| Handling large datasets across decades | Efficient memory use and company-wise data shaping |
| Python-Power BI integration | Used embedded scripts and data gateways |
| Accurate short-term predictions | Introduced indicators + lag features in XGBoost |

---

## ✅ Testing and Validation
- Evaluated model performance using:
  - 📉 RMSE (Root Mean Squared Error)
  - 📈 MAE (Mean Absolute Error)
- Dashboard tested for:
  - Data accuracy
  - Cross-device responsiveness
  - Interactivity and responsiveness

---

## 🔮 Future Scope
- 📊 Add more indices (e.g., S&P 500, NIFTY 50)
- 📰 Integrate news sentiment and social media analysis
- 💬 Enable natural language queries with AI integration
- ⚙️ Improve performance for real-time scalability

---

## 🏁 Conclusion
This project showcases how data science, finance, and BI tools can be integrated into a single solution that delivers real-time analytics and future price predictions. It is ideal for investors, analysts, and decision-makers who rely on data-driven insights.

---

## 📸 Dashboard Images

### Dashboard Sample 1  
![Dashboard Image 1](https://github.com/user-attachments/assets/dd7baea3-b47f-4c0d-8c49-12eb10767ad8)

### Dashboard Sample 2  
![Dashboard Image 2](https://github.com/user-attachments/assets/77034c43-ce7e-4898-a535-6fcc4048d7c7)

---

