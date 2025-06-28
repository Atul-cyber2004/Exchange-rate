# Exchange-rate
exchange rate analysis between bitcoin and us dollar

In this mini-project, we visualize the historical exchange rate between Bitcoin and the US Dollar using public data provided by the Coindesk API. The notebook fetches price data for a user-defined date range and plots the daily BTC-USD closing prices. This simple tool helps understand long-term Bitcoin price trends and volatility.

The project is ideal for anyone getting started with API-based data access, data wrangling using pandas, and time-series plotting in Python.

This script is for exploratory analysis only — no machine learning or prediction is performed.

**File Overview:
**

exchange_rates.ipynb – A Google Colab notebook that:

Connects to the Coindesk API

Retrieves BTC-USD historical prices

Displays a line chart of closing values over time
**
Data**

The data is pulled directly from Coindesk’s public API and does not require any authentication or API key. You can customize the start and end date within the notebook using:


**Running**

Open the notebook in Google Colab and run all cells in order. The notebook will:

Fetch historical BTC-USD exchange rate data from Coindesk.

Convert the raw JSON data into a pandas DataFrame.

Plot the closing prices using matplotlib.

Make sure you're connected to the internet — the notebook relies on live API access.

This project can be extended to other currencies supported by Coindesk or even integrated with other crypto APIs such as CoinGecko or Binance.
