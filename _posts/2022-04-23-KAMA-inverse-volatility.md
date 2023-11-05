---
title: "A moving average crossover strategy using Kaufman's Adaptive Moving Average indicator"
excerpt: "Kaufman's Adaptive Moving Average filters out 'market noise' during high volatility periods and prevents generating false signals."
categories:
  - Systematic Trading
tags:
  - Python
---

The Momentum Strategy using Kaufman's Adaptive Moving Average is ideal as it filters out "market noise" during high volatility periods and prevents generating false signals. A smoother, longer-term KAMA indicator can be used to represent the bigger trend of the performance of a stock and a shorter-term KAMA indicator can be used to generate the trading signals. The crossover of a faster KAMA line above a slower KAMA line indicates a change from downtrend to uptrend, which triggers a buy signal, which is reversed once the faster KAMA line crosses back over.

The portfolio is weighted using the Inverse Volatility weighting strategy, which relies on using a stock's n day standard deviation to model price volatility and attempt to quantitatively measure the stock's risk. The lower the standard deviation, the higher weighting the stock will have.

View my analysis: [Available on GitHub](https://github.com/martina-torce/systematic-trading/blob/main/KAMA-InverseVolatility.ipynb)
