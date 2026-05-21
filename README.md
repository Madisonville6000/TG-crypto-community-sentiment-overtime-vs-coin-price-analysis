# TG-crypto-community-sentiment-overtime-vs-coin-price-analysis
Analyzing telegram crypto community sentiment against coin price movements using Python, Coingecko API and time-series analysis.

## Project Overview
This project analyzes the relationship between Telegram community activity and cryptocurrency price movements using Python and CoinGecko API data.

The project combines:
- Telegram exported chat data
- Daily message activity analysis
- CoinGecko historical price data
- Time-series visualization
- Correlation analysis

The objective is to explore whether spikes in Telegram community engagement may correlate with cryptocurrency price trends.

## Tech Used
- Python
- pandas
- matplotlib
- requests
- Jupyter Notebook
- CoinGecko API

## Features
- Extracted Telegram chat activity from exported JSON files
- Converted Telegram messages into structured pandas DataFrames
- Aggregated daily message counts
- Pulled past (Jan '25-May '26) WikiCat price data from CoinGecko API
- Merged social activity data with market price data
- Built sentiment/activity vs price visualization
- Performed basic correlation analysis

## Key Insight
The analysis showed major spikes in Telegram activity around periods where WikiCat experienced significant price movement, especially during the August 2025 rally.

This demonstrates how community engagement may influence or reflect speculative crypto market behavior.


## Future Improvements
- Whale wallet tracking
- TON wallet analytics
- Telegram bot integration
- Predictive machine learning models
- Real-time community monitoring dashboard

## Sample Visualization

Community sentiment vs WikiCat price movement over time:

![Chart](community_sentiment_chart.png)

## Repository Structure

```bash
.
├── README.md
├── TG Crypto comm activity vs coin price analysis.ipynb
├── community_sentiment_chart.png
├── LICENSE
└── .gitignore
```
## Author
Built by Unwana Umana (Madisonville6000) as part of a growing Web3/Data Intelligence portfolio.
