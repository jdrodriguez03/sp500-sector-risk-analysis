# S&P 500 Sector Risk-Return Analysis During High-Volatility Events (2020–2024)

## Context
Market crises don't affect all sectors equally — some collapse, others hold or even outperform.
Understanding these differences is critical for building resilient investment strategies.
This project examines how six S&P 500 sector ETFs behaved across two major disruptions:
the COVID-19 crash (February–March 2020) and the inflationary crisis driven by Fed rate hikes (2022).

## Business Objective
Determine which sectors offered the best risk-adjusted performance during high-volatility events,
and derive actionable implications for sector-based asset allocation.

## Data Objective
Quantify and compare sector performance using cumulative return, annualized volatility,
Sharpe ratio, and maximum drawdown. Analyze how sector correlations shift between
normal market conditions and crisis periods.

## Assets & Period
**ETFs analyzed:** XLK · XLF · XLE · XLV · XLP · XLY  
**Period:** January 2019 – December 2024  
*2019 is included as a pre-crisis baseline.*

## Repository Structure
'''
sp500-analysis/
├── data/
│   └── raw/
│       └── sector_prices_raw.csv
├── notebooks/
│   └── 01_risk_return_analysis.ipynb
├── requirements.txt
├── LICENSE
└── README.md
'''
## Setup
```bash
conda create -n sp500-analysis python=3.11
conda activate sp500-analysis
pip install -r requirements.txt
```

## Data Source
Data retrieved via [yfinance](https://github.com/ranaroussi/yfinance) from Yahoo Finance.
Assets are SPDR Sector ETFs managed by State Street Global Advisors.
This project is for academic and portfolio purposes only.
