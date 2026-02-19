# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes how market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid.

## Data Sources
- Bitcoin Fear & Greed Index
- Historical Trader Data (Hyperliquid)

## Methodology
- Cleaned and aligned datasets to daily level
- Merged sentiment with trade data
- Created performance metrics (PnL, trade frequency, position size, long/short ratio)
- Compared trader behavior across sentiment regimes

## Key Insights
1. Average PnL is slightly higher during Greed periods.
2. Traders take significantly larger position sizes during Fear.
3. Trading activity increases during Greed.
4. Profit distribution is highly skewed (median PnL = 0).

## Strategy Recommendations
1. Reduce position size during Fear to manage volatility risk.
2. Increase trade participation during Greed while maintaining disciplined risk management.

## How to Run
Open the notebook in Jupyter or Google Colab and execute cells sequentially.
