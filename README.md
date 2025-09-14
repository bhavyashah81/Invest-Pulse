# Invest Pulse

A financial analytics platform that consolidates stock market data, social sentiment analysis, and risk assessment tools.

## Features

**Real-Time Stock Analysis**: Track comprehensive stock metrics including current price, 52-week highs/lows, target prices, dividend rates, and sector information with live Yahoo Finance integration

**Interactive Price Visualization**: Visualize historical price trends with dynamic line charts showing adjusted closing prices from 2016 to present

**Social Sentiment Integration**: Stay informed with real-time social media discussions through integrated Twitter feeds and Reddit community insights for specific stock tickers

**Risk Assessment Calculator**: Evaluate investment risk using beta coefficients and calculate potential share quantities based on investment amounts

**Comprehensive Stock Selection**: Access to extensive ticker database covering U.S. and Canadian markets with over 7,000+ available securities

**Multi-Source News Aggregation**: Get the latest market discussions from Twitter hashtags, Reddit subreddit threads, and Yahoo Finance news feeds

## Technologies and Languages Used

**Languages**: Python  
**Framework**: Streamlit  
**Libraries**: yfinance, pandas, matplotlib, tweepy, praw (Reddit API), PIL, requests  
**APIs**: Yahoo Finance API, Twitter API, Reddit API  
**Data Visualization**: Matplotlib, Streamlit native charts

## How to Run the Project

### 1. Install Dependencies
```bash
python3 -m pip install streamlit yfinance pandas tweepy praw matplotlib pillow requests
```

### 3. Run the Application
```bash
python3 -m streamlit run main_.py
```

This will:
- Launch the dashboard
- Load the comprehensive ticker database (7,000+ tickers)
- Enable real-time stock price tracking and analysis
- Fetch social media discussions for selected tickers (requires API setup)
- Display interactive charts with historical price data
- Provide risk assessment tools and investment calculators

## Dependencies

Required packages:
- streamlit >= 1.28.0
- yfinance >= 0.2.18
- pandas >= 2.0.0
- tweepy >= 4.14.0
- praw >= 7.7.0
- matplotlib >= 3.7.0
- pillow >= 10.0.0
- requests >= 2.31.0

**Note**: Twitter and Reddit API features require valid API credentials. The stock analysis and visualization features will work without API setup.

![image](https://github.com/user-attachments/assets/7dcd083e-a0f2-4762-b19d-683803c77308)
![image](https://github.com/user-attachments/assets/185aea2f-44d3-4f4f-9070-af4a1b47eb96)



