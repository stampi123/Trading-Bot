# OANDA Trading Bot

## Project Overview

The OANDA Trading Bot is an automated trading system developed to execute trades in the foreign exchange (FOREX) market using the OANDA API and Python. This bot analyzes historical market data and applies a custom trading strategy to make informed buy or sell decisions, optimizing trade execution based on specific market signals.

### Features

- **Data Acquisition**: 
  - Utilizes the `yfinance` library to download historical price data for currency pairs.
  - Connects to the OANDA API to fetch real-time market data.

- **Signal Generation**:
  - Implements a signal generator function that identifies bullish and bearish patterns using the last two periods of price data.
  - Generates trading signals (1 for sell, 2 for buy, and 0 for no action) based on defined criteria.

- **Trade Execution**:
  - Executes market orders with automatic stop loss and take profit settings based on the calculated price levels.
  - Integrates scheduling functionality to automate trading decisions at specified intervals.

### Skills Demonstrated

- **API Integration**: Successfully connected to the OANDA API for real-time market data and trade execution.
- **Algorithm Development**: Developed trading algorithms based on technical analysis and market signals.
- **Data Analysis**: Analyzed historical market data to inform trading decisions and optimize execution.
- **Python Proficiency**: Demonstrated proficiency in Python programming, including libraries such as `pandas`, `yfinance`, and `apscheduler`.
- **Automation**: Implemented automation features to streamline the trading process, enhancing efficiency and responsiveness to market changes.

### Future Enhancements

- Expanding the trading strategies to incorporate additional indicators and machine learning models for improved decision-making (such as sentiment analysis).
- Developing a user-friendly graphical interface for monitoring trades and managing settings.
- Implementing logging and error-handling mechanisms to track performance and troubleshoot issues.


