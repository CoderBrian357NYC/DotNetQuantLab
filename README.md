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


### StochRSIBot [StochRSIBot](https://github.com/CoderBrian357NYC/StochRSIBot) 

A long-only cryptocurrency trading bot using the Stochastic RSI indicator with ATR-based position sizing. 
Designed to maintain only one open trade at a time.

Configuration

Equity: Initial capital for trading.
atrMultiplier: Controls the position size relative to market volatility.
MaxOpenTrades: Should be set to 1 to ensure only one trade is open at a time.
StochRSI parameters such as the RSI period, Stochastic period, and smoothing factors.
Trading pair and time intervals.
How It Works

The bot fetches live price data from Binance.
It calculates the Stochastic RSI indicator.
When the StochRSI signals an oversold condition, the bot attempts to open a long position.
The bot uses the ATR to size the position, adjusting for market volatility.
Only one position is allowed open at any time; new entries are skipped if a trade is already open.
Positions are closed based on exit conditions defined in the strategy.
Future Enhancements

Add short selling capability.
Implement trailing stops and dynamic exits.
Improve logging and monitoring features.
Add backtesting capabilities.

- Located in the `StochRSIBot` submodule.
- [Read more in the StochRSIBot README](./StochRSIBot/README.md)
