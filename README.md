# 📈 Stock Anomaly Detection Tool

A Python command-line tool that fetches real-time stock data, calculates moving averages, and flags unusual price movements using statistical analysis.

---

## Features

- Fetches historical stock data using the `yfinance` API
- Calculates **20-day and 50-day moving averages**
- Detects anomalous trading days using a **rolling z-score method** (flags days where returns deviate more than 2 standard deviations from the 20-day mean)
- Visualises price history, moving averages, and anomalies on a chart
- Supports any valid ticker symbol (e.g. `AAPL`, `TSLA`, `GOOGL`)
- Supports multiple time periods (`1mo`, `3mo`, `6mo`, `1y`, `2y`)

---

## Example Output
<img width="1919" height="1006" alt="image" src="https://github.com/user-attachments/assets/5a45d675-0e1d-4868-97fc-b631eb2a8cf0" />

