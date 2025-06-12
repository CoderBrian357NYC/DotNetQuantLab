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

