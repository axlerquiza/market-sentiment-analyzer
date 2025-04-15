# Market Sentiment Analyzer

**Market Sentiment Analyzer** is a data mining project that explores the relationship between Twitter sentiment and stock market behavior. By integrating social sentiment with financial data, this tool applies NLP and time series forecasting to model and potentially predict market movements.

## 📌 Project Objective

> Can public sentiment on Twitter be used as a signal for stock price fluctuations and market volatility?

We tackle this question by analyzing tweets related to major stock tickers, scoring their sentiment, and combining the results with historical price and volume data to explore correlations and make forecasts.

## 🧰 Features

- 🧠 Sentiment analysis using VADER (via NLTK)
- 🧼 Sentiment outlier filtering via K-means clustering
- 📈 SARIMAX forecasting model with and without sentiment as exogenous input
- 🔁 EDA including daily returns, volatility analysis, and sentiment distributions
- 🔗 Correlation heatmaps between sentiment and price/volume

## ⚙️ Dependencies

- Python 3.10+
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `statsmodels`
- `nltk`, `vaderSentiment`
- `snscrape`, `yfinance`

## 🔧 Setup & Installation

Install dependencies:
```bash
pip install pandas numpy nltk statsmodels
```

Download VADER lexicon for sentiment scoring:
```python
import nltk
nltk.download('vader_lexicon')
```
