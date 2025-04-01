Historical Stock Performance Dashboard

Overview

From my four years as a financial trader to my new path in data analysis, this project is a personal milestone: a Historical Stock Performance Dashboard that transforms raw stock data into actionable insights. Built with Python, PostgreSQL, Excel, and Tableau, it tracks the performance of five major stocks—AAPL, MSFT, GOOGL, AMZN, TSLA—from 1984 to March 2025. It’s a blend of my trading instincts and data skills, delivering price trends, volatility, and correlations in an interactive package.

Features

Data Span: Daily stock prices from 1984-09-07 to 2025-03-12.
Metrics: Daily returns, annualized volatility, and pairwise correlations.
Visualization: Interactive Tableau dashboard with:
Price trend lines (filterable by date and stock).
Volatility bar chart.
Correlation heatmap.

Project Structure

historical-stock-dashboard/

│
├── data_loading/

│   ├── load_kaggle_data.py     # Loads Kaggle dataset into PostgreSQL

│   └── extend_with_yfinance.py # Fetches and appends yfinance data

├── analysis/

│   └── portfolio_calculations.xlsx # Excel file with returns, volatility, correlations

├── visualization/

│   └── dashboard_screenshot.png # Tableau dashboard preview

├── README.md                   # You’re reading it!

└── requirements.txt            # Python dependencies

Tech Stack

Python 3.9+: Data fetching (yfinance) and database ops (psycopg2).

PostgreSQL: Stores historical and extended stock data.

Excel: Calculates performance metrics.

Tableau Public: Visualizes results interactively
