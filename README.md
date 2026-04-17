# Stock Price Analysis Dashboard

A portfolio-grade financial analytics project that examines five years of historical stock data for Apple, Amazon, Google, and Microsoft through an interactive Streamlit dashboard. The project focuses on trend analysis, return behaviour, volatility, correlation, signal exploration, and simple strategy backtesting to demonstrate practical, business-oriented analytical thinking.

## Project Snapshot

- Built as an end-to-end financial data analytics case study, not just a charting exercise
- Compares four large-cap technology stocks: `AAPL`, `AMZN`, `GOOG`, and `MSFT`
- Uses Streamlit for presentation, Pandas for data work, and Plotly for interactive visuals
- Frames analysis around decision support, risk interpretation, and portfolio-style comparison
- Designed as a portfolio project for GitHub, recruiter review, and interactive showcase

## What This Project Covers

- Dataset inspection and preprocessing review
- Multi-stock price trend analysis
- Moving-average overlays and trend structure exploration
- Daily return analysis and distribution diagnostics
- Volatility comparison and rolling risk analysis
- Sharpe Ratio and risk-adjusted performance comparison
- Closing-price and return-level correlation analysis
- Moving-average crossover signal exploration
- Simple moving-average strategy backtesting versus buy and hold
- Consolidated insights and limitations for stakeholder-style interpretation

## Dashboard Pages

- `Home`: high-level summary, key KPIs, and dashboard overview
- `Dataset Overview`: data coverage, schema, quality, and preprocessing summary
- `Trend Analysis`: price comparison and moving-average overlays
- `Return Analysis`: daily returns, distribution diagnostics, and cumulative performance
- `Risk & Volatility`: volatility, Sharpe Ratio, rolling risk, and risk-return positioning
- `Correlation Analysis`: price and return correlation with pairwise analysis
- `Signal Explorer`: buy/sell crossover logic and signal event tables
- `Strategy & Backtesting`: MA strategy comparison versus buy and hold
- `Key Insights`: consolidated analytical takeaways and limitations
- `About Project`: project summary, author profile, and technology stack

## Business and Analytical Questions Answered

- Which stock showed the strongest total return over the analysis period?
- Which stock offered the strongest risk-adjusted return?
- Which stock behaved most aggressively in terms of volatility?
- Which stock behaved most defensively?
- How similar are these stocks in their day-to-day return movements?
- Which pair provides the best diversification potential within this universe?
- How do moving averages change the interpretation of trend direction?
- How do crossover-style signals appear historically across each company?
- How does a simple MA strategy compare with passive buy and hold?

## Technology Stack

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- Pathlib

## Project Structure

```text
New folder/
|-- README.md
`-- stock_dashboard/
    |-- app.py
    |-- requirements.txt
    |-- assets/
    |   |-- profile.jpg
    |   `-- *.png
    |-- individual_stocks_5yr/
    |   |-- AAPL_data.csv
    |   |-- AMZN_data.csv
    |   |-- GOOG_data.csv
    |   `-- MSFT_data.csv
    |-- pages_content/
    |   |-- about.py
    |   |-- correlation.py
    |   |-- dataset.py
    |   |-- home.py
    |   |-- insights.py
    |   |-- returns.py
    |   |-- risk.py
    |   |-- signals.py
    |   |-- strategy.py
    |   `-- trend.py
    `-- utils/
        |-- charts.py
        |-- data.py
        |-- sidebar.py
        `-- styles.py
```

## Run Locally

1. Open a terminal in:

```text
C:\Users\MIR SHAHADUT HOSSAIN\DATA ANALYTICS PROJECTS\STOCK PRICE ANALYSIS\New folder\stock_dashboard
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the app:

```bash
streamlit run app.py
```

## Data Notes

- The project uses historical CSV files stored in `individual_stocks_5yr/`
- Comparative metrics are based on the overlapping date window across all stocks
- Daily returns and moving averages are computed per ticker to avoid cross-stock leakage
- This project is built for educational analysis and portfolio presentation, not live trading

## Why This Project Matters

This project demonstrates more than visualisation. It shows how raw financial data can be transformed into structured analysis that supports interpretation, comparison, and decision framing. It highlights practical analyst skills including:

- time-series thinking
- data cleaning and feature engineering
- risk-return interpretation
- metric design and comparison
- dashboard presentation and storytelling
- clear communication of assumptions and limitations

## Current Strengths

- Clean multi-page Streamlit application
- Strong visual consistency across hero sections, KPI cards, and chart cards
- Real profile branding and portfolio-ready About page
- Interactive exploration across trend, return, risk, correlation, and strategy analysis
- Better-than-basic dashboard structure with page-level analytical context

## Limitations

- The stock universe is limited to four large-cap technology companies
- The analysis is historical and does not provide predictive forecasting
- Dividend-adjusted and execution-aware total return is not modeled
- Backtesting is simplified and does not include transaction costs, slippage, or position sizing
- The universe is too concentrated for true cross-sector diversification analysis

## Future Improvements

- Add benchmark comparisons such as SPY or QQQ
- Expand the stock universe beyond technology
- Introduce more advanced risk metrics such as drawdown and Value at Risk
- Add forecasting or scenario-analysis layers
- Improve the strategy layer with walk-forward validation and richer backtesting assumptions
- Prepare a public deployment link for easier portfolio sharing

## Recommended GitHub Presentation Assets

For the strongest GitHub presentation, include 3 to 5 polished screenshots from the current app. Best choices:

- Home page overview
- Trend Analysis page
- Return Analysis page
- Risk & Volatility page
- Strategy & Backtesting page

If you want to add screenshots to this README later, store them in a consistent folder and reference them near the top of the file under a `Screenshots` section.

## Author

**Mir Shahadut Hossain**  
Data Analyst

- GitHub: [doyancha](https://github.com/doyancha)
- LinkedIn: [mir-shahadut-hossain](https://www.linkedin.com/in/mir-shahadut-hossain/)

## Disclaimer

This project is for educational, analytical, and portfolio demonstration purposes only. Nothing in this repository should be interpreted as financial advice or a recommendation to buy or sell any security.
