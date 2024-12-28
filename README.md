# Market Volatility Pattern Analysis

This project analyzes intraday stock market data to identify volatility patterns, calculate key statistical metrics, and generate visualizations to gain insights into stock price behaviors. The analysis leverages powerful R libraries and techniques to preprocess data, handle outliers, and calculate indicators like rolling volatility, moving averages, and volume-weighted average price (VWAP).  

---

## Features

- **Data Preprocessing**  
  - Fetch stock data using `quantmod` from Yahoo Finance.
  - Handle missing values and outliers using statistical methods.
  - Calculate returns and other derived metrics for analysis.

- **Statistical Measures**  
  - Daily return, volatility (annualized), skewness, and price range.
  - Summary statistics such as mean return, overall volatility, and average volume.

- **Technical Indicators**  
  - Rolling Volatility (10-period).
  - Moving Averages (20-period and 50-period).
  - Volume-Weighted Average Price (VWAP).

- **Visualizations**  
  - Scatter plot of Volume vs. Returns with trend line.
  - Rolling Volatility trend.
  - Comparison of Price vs. VWAP and Moving Averages.
  - Highlighting unusual patterns with z-scores.
  - Intraday volatility patterns by hour of the day.

- **Insights**  
  - Identify and highlight unusual stock price movements.
  - Analyze intraday volatility and volume trends to reveal trading patterns.

---

## Tools and Technologies

- **Languages:** R
- **Libraries:**  
  - `quantmod`  
  - `tidyverse`  
  - `ggplot2`  
  - `zoo`  
  - `moments`

---
