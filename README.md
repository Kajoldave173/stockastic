# **Stockastic**
### **Predicting Stocks with ML**

**Stockastic is an ML-powered stock price prediction app built with Python and Streamlit. It utilizes machine learning models to forecast stock prices and help investors make data-driven decisions.**

## **How It's Built**

Stockastic is built with these core frameworks and modules:

- **Streamlit** - To create the web app UI and interactivity
- **YFinance** - To fetch financial data from Yahoo Finance API
- **StatsModels** - To build the ARIMA time series forecasting model
- **Plotly** - To create interactive financial charts

The app workflow is:

1. User selects a stock ticker
2. Historical data is fetched with YFinance
3. ARIMA model is trained on the data
4. Model makes multi-day price forecasts
5. Results are plotted with Plotly

## **Key Features**

- **Real-time data** - Fetch latest prices and fundamentals
- **Financial charts** - Interactive historical and forecast charts
- **ARIMA forecasting** - Make statistically robust predictions
- **Backtesting** - Evaluate model performance
- **Responsive design** - Works on all devices

## **Getting Started**

### **Local Installation**

1. Clone the repo

```bash
git clone https://github.com/Kajoldave173/stockastic.git
```

2. Install requirements

```bash
pip install -r requirements.txt
```

3. Change directory
```bash
cd streamlit_app
```

4. Run the app

```bash
streamlit run 00_Main.py
```

The app will be live at ```http://localhost:8501```

## **Future Roadmap**

Some potential features for future releases:

- **More advanced forecasting models like LSTM**
- **Quantitative trading strategies**
- **Portfolio optimization and tracking**
- **Additional fundamental data**
- **User account system**

## **Disclaimer**
**This is not financial advice! Use forecast data to inform your own investment research. No guarantee of trading performance.**

## **About the Maintainer**

This project is currently maintained by Kajol Dave.

Kajol is a Data Scientist with 4+ years of experience in retail and digital marketing, building demand forecasting models, marketing mix models, and real-time personalization pipelines that drive revenue, reduce cost, and inform commercial strategy.

Connect with Kajol:
- GitHub: [Kajoldave173](https://github.com/Kajoldave173/)
- LinkedIn: [Kajol Dave](https://www.linkedin.com/in/kajol-dave)
- Email: [kajoldave031@gmail.com](mailto:kajoldave031@gmail.com)