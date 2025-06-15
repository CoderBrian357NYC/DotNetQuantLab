# DotNetQuantLab 🧠📈

A collection of algorithmic trading bots and financial analysis tools written in C# using .NET.  
This lab is built to demonstrate real-world trading strategies, clean architecture, and robust code quality for potential freelance clients, employers, and fellow developers.

---

## 🔍 Included Projects

### ✅ [AtrBot](https://github.com/CoderBrian357NYC/AtrBot)  
A long-only Bitcoin trading bot that uses:
- **Average True Range (ATR)** for position sizing
- **Volatility filtering**
- **Moving average crossover strategy**
- Performance metrics: Win rate, P/L, Sharpe ratio, max drawdown

> Located in the `AtrBot` submodule.

### ✅ [StochRSIBot](https://github.com/CoderBrian357NYC/StochRSIBot)
A long-only cryptocurrency trading bot using the Stochastic RSI indicator with ATR-based position sizing.
- **Supports Binance API for live trading.**
- **Trades based on Stochastic RSI indicator signals.**
- **Position sizing using ATR and an adjustable multiplier.**
- Restricts to a single open position at any time.
- Configurable parameters for flexibility.

> Located in the `StochRSIBot` submodule.

---

## 🔧 Tech Stack

- C# / .NET 8
- Binance API
- Console-based architecture (clean separation of concerns)
- Git submodules for modular portfolio structure

---

## 📁 Structure

```bash
DotNetQuantLab/
├── AtrBot/                # Submodule: ATR-based Bitcoin bot
├── .gitmodules
└── README.md
├── StochRSIBot/                # Submodule: StochasticRSI-based Bitcoin bot
├── .gitmodules
└── README.md

---


