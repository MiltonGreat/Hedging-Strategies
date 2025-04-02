# Forex Trading Strategy using Moving Average Crossover

![screenshot-localhost_8888-2025 03 31-14_26_38](https://github.com/user-attachments/assets/fd39f8c3-dba2-4ff8-9cb1-55c44d7c864b)

### Project Overview

This project explores hedging strategies in forex trading by testing a moving average crossover strategy. The strategy generates trading signals based on the crossover of a short-term (20-day) and long-term (50-day) moving average. I analyze the strategy's profitability, volatility, and risk management using daily exchange rate data from 2000 to 2019.

### Strategy Explanation

1. Compute Moving Averages:
- Calculate 20-day (short-term) and 50-day (long-term) moving averages

2. Generate Buy/Sell Signals:
- Buy when the short MA crosses above the long MA
- Sell when the short MA crosses below the long MA

3. Backtest Strategy Performance:
- Calculate daily returns and cumulative returns
- Compare with a buy-and-hold approach
- Measure volatility, Sharpe ratio, and drawdowns

### Results Summary

- Total Market Return: +14.1% (Buy & Hold)
- Total Strategy Return: -51.6% (Underperformed)
- Sharpe Ratio: -1.73 (High risk, low reward)
- Max Drawdown: -26.25% (Significant loss potential)

**NOTE:** The moving average crossover in this setup failed to generate profitable signals and was not an effective hedging strategy.

### Future Improvements

- Optimize MA Periods: Test different short/long window lengths
- Combine with Other Indicators: Add RSI, MACD, Bollinger Bands
- Improve Risk Management: Use stop-loss/take-profit levels
- Explore Alternative Strategies: Consider machine learning-based forecasting

### Source

![Forex Exchange Rates Since 2004 from Kaggle](https://www.kaggle.com/datasets/asaniczka/forex-exchange-rate-since-2004-updated-daily)
