Trader Performance vs Market Sentiment Analysis
Objective

This project analyzes how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and performance on Hyperliquid. The goal is to identify sentiment-driven behavioral patterns and derive actionable trading insights.

Data Sources

Bitcoin Fear & Greed Index

Historical Trader Data (Hyperliquid)

Methodology

Cleaned and validated both datasets (missing values, duplicates).

Converted timestamps and aligned data at daily granularity.

Merged sentiment data with trade-level records.

Engineered key behavioral and performance metrics:

Closed PnL (mean & median)

Trade frequency

Position size (USD)

Long/short ratio

Segmented traders into High Volume vs Low Volume groups to analyze heterogeneous behavior across sentiment regimes.

Key Insights

Profitability:
Average PnL is slightly higher during Greed periods; however, median PnL remains zero across all regimes, indicating skewed returns driven by large outliers.

Risk Behavior:
Traders take significantly larger position sizes during Fear periods, suggesting increased risk-taking in volatile markets.

Market Participation:
Trading activity increases during Greed, indicating higher engagement during positive sentiment regimes.

Segmentation Insight:

High-volume traders perform best during Greed periods.

Low-volume traders show relatively stronger performance during Fear and Neutral periods.
This demonstrates that sentiment impacts trader segments differently.

Strategy Recommendations

Risk Management During Fear:
Reduce position size by 25–30% during Fear periods to manage volatility exposure.

Segment-Based Participation Strategy:

High-volume traders may increase participation during Greed regimes.

Low-volume traders should exercise caution during Greed and focus on selective trades during Fear/Neutral periods.

How to Run

Open the notebook in Jupyter or Google Colab and execute all cells sequentially to reproduce the analysis.
