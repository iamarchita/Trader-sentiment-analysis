# Trader Behavior Analysis using Market Sentiment

## Overview
This project analyzes how market sentiment (Fear & Greed Index) affects trader
performance and behavior using historical trading data.

## Data Sources
- historical_data.csv: individual trade-level data
- fear_greed_index.csv: daily market sentiment classification

## Methodology
- Trades were merged with daily sentiment data
- Data was aggregated at Account–Date level
- Performance metrics (PnL, win rate proxy) were compared across sentiment regimes
- Trader behavior such as trade frequency, position size, and directional bias was analyzed
- Traders were segmented based on activity and bias
- A baseline predictive model was built to predict same-day profitability (bonus)

## Key Insights
- Trader performance differs significantly between Fear and Greed periods
- Trading activity and risk-taking increase during Greed regimes
- High-frequency traders show higher volatility compared to infrequent traders

## How to Run
1. Install dependencies:
2.pip install pandas numpy matplotlib seaborn scikit-learn
3. Open and run the notebook:


## Files
- analysis.ipynb: main analysis and insights
- predictive_model.ipynb: predictive model
