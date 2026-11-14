# 📈 Stock Portfolio Tracker

A command-line Python application that calculates the total value of a user's stock portfolio using hardcoded stock prices, with an option to save the report to a `.txt` or `.csv` file.

## Features
- Displays available stocks and their prices
- Accepts stock tickers and quantities from the user
- Calculates the value of each holding and the total investment value
- Validates input (unknown tickers, negative or non-numeric quantities)
- Saves the report as `.txt` or `.csv`

## Concepts Used
- Python dictionaries
- Loops and conditional statements
- User input and exception handling (`try/except`)
- File handling (`open`, `write`)
- String formatting (f-strings)

## Supported Stocks
| Ticker | Price (USD) |
|--------|-------------|
| AAPL   | 180.50 |
| TSLA   | 250.75 |
| GOOG   | 135.20 |
| AMZN   | 140.90 |
| MSFT   | 350.00 |

## How to Run
```bash
python stock_portfolio_tracker.py
```
Uncomment `stock_portfolio_tracker()` at the bottom of the file first.

## Sample Output
```
--- Your Portfolio ---
  AAPL | Quantity: 10 | Price: $180.50 | Value: $1805.00
  TSLA | Quantity: 5  | Price: $250.75 | Value: $1253.75
==============================
TOTAL INVESTMENT VALUE: $3058.75
==============================
```

## Future Improvements
- Fetch live prices using a stock API
- Add a GUI or web interface
- Support selling and updating holdings

## Author
[Your Name] | CodeAlpha Python Programming Internship
