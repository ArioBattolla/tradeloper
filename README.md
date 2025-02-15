# Trading Bot

This repository contains a modular framework for developing, backtesting, and executing trading strategies. The project is divided into the following components:

- **Data Handler:** Gathers historical and live market data.
- **Strategy Manager:** Manages one or more trading strategies (e.g., a mean reversion strategy) that generate buy/sell signals.
- **Risk Manager:** Quantifies risk and decides if an order should be executed.
- **Backtester:** Tests strategies on historical data.
- **Execution Handler:** Sends orders to a trading platform (IBKR) via their API.

