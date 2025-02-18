# Stock Data Visualization Dashboard

This project is a Stock Data Visualization Dashboard built using Bokeh and yFinance. The dashboard allows users to visualize stock data, apply indicators, and compare two different stocks.

## Features

- **Data Loading**: Load stock data from Yahoo Finance.
- **Indicators**: Apply indicators such as 30 Day SMA, 100 Day SMA, and Linear Regression Line.
- **Comparison**: Compare two different stocks side by side.
- **Custom Date Range**: Select a custom date range for the stock data.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/stock-data-visualization-dashboard.git
    cd stock-data-visualization-dashboard
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To run the Bokeh web app, use the following command:
```sh
bokeh serve --show main.py
