# Stock-Mutual-Fund-Sentiment-Dashboard
A Python-based desktop application that combines real-time market data, ML sentiment analysis, and technical indicators to help retail investors make informed decisions on stocks and Indian mutual funds.

#Features

1.Stock Analysis

Live stock price, trend, RSI, MACD with interactive candlestick/line charts

Hover tooltips showing OHLCV, RSI, MACD values on chart

Earnings calendar overlaid on price chart

Insider trading alerts with transaction details

Real-time watchlist with custom price alert notifications


2.Sentiment Analysis

Reddit (WallStreetBets) — no API key needed, uses public JSON

Twitter/X — via NewsAPI fallback

News — multi-source cascade: yFinance → Google News RSS → NewsAPI → Finviz

Naive Bayes (TF-IDF) ML classifier trained on financial headlines

Bullish/Bearish sentiment bars with confidence scores

Filterable news popup with keyword search


3.Mutual Fund Analysis

NAV history charts (3M / 6M / 1Y / 3Y) via mfapi.in (free, no key)

Period-wise returns: 1W, 1M, 3M, 6M, 1Y, 3Y + CAGR

Risk metrics: Sharpe Ratio, Annualised Volatility, Max Drawdown

SIP Calculator with XIRR approximation

Fund metadata: house, type, category, start date

MF watchlist with SIP tracking

Reddit & news sentiment for mutual funds

