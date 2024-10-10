# Price-Momentum-Trading-Strategy

## Overview
This project implements a price momentum trading strategy that ranks and selects the top 0.2% of stocks based on a risk-adjusted performance metric. The strategy incorporates various signals, including mean reversion, trend confirmation, and volatility-based exits. The backtesting was conducted using 10 years of historical data from 2013 to 2024 on stocks listed on the NSE exchange.

## Table of Contents
- [Objective](#objective)
- [Data](#data)
- [Methodology](#methodology)
  - [Performance Metric](#performance-metric)
  - [Stock Selection](#stock-selection)
  - [Trading Signals](#trading-signals)
- [Backtesting Results](#backtesting-results)
- [Files Included](#files-included)
- [Conclusion](#conclusion)

## Objective
The objective of this strategy is to identify high-performing stocks based on price momentum, utilizing a systematic approach to trading that incorporates multiple indicators for enhanced decision-making.

## Data
The strategy is backtested using historical price data from the NSE exchange for the years 2013-2024. A total of 10 stocks were selected for analysis.

## Methodology

### Performance Metric
The strategy utilizes a risk-adjusted performance metric to rank and select stocks. This metric accounts for both returns and volatility, providing a more comprehensive evaluation of stock performance.

### Stock Selection
Stocks are ranked and selected based on their performance metrics, focusing on the top 0.2% of stocks within the dataset. This selective approach aims to identify stocks with strong momentum potential.

### Trading Signals
The following trading signals are implemented in the strategy:
- **Mean Reversion**: Identifies potential price reversals based on historical price movements.
- **Trend Confirmation**: Uses indicators to confirm the strength of an ongoing trend before entering trades.
- **Volatility-Based Exits**: Determines exit points based on volatility levels to manage risk effectively.

## Backtesting Results
The strategy was backtested over the specified 10-year period, demonstrating its effectiveness in identifying profitable trading opportunities.

## Conclusion
The price momentum trading strategy leverages a combination of rigorous stock selection criteria and various trading signals to enhance trading performance. The results from the backtesting period indicate a robust approach to capitalizing on price momentum within the stock market.


