# Copula-Based Pairs Trading with Mispricing Index and Bollinger Bands
## Overview
This project implements a Copula-Based Pairs Trading strategy that utilizes a Mispricing Index and Bollinger Bands to identify and exploit arbitrage opportunities in financial markets. The objective is to construct a statistical arbitrage strategy by detecting and trading on price discrepancies between two co-integrated assets.

## Features
  Copula Modeling: Uses copula models to capture the dependency structure between pairs of assets, allowing for more flexible modeling of joint distributions compared to traditional linear methods.
Mispricing Index: Calculates a Mispricing Index to quantify the divergence of asset prices from their expected equilibrium. This index serves as the primary signal for initiating trades.
Bollinger Bands: Employs Bollinger Bands to assess volatility and identify mean-reversion opportunities, complementing the Mispricing Index.
Pairs Selection: Implements a selection process to identify pairs of assets that are likely to be co-integrated, enhancing the robustness of the strategy.
Backtesting: Includes backtesting capabilities to evaluate the historical performance of the trading strategy, with metrics such as Sharpe ratio, drawdown, and cumulative returns.
