# Trader Performance vs Market Sentiment Analysis

## Objective

This project analyzes how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and performance on Hyperliquid. The goal is to identify sentiment-driven behavioral patterns and derive actionable trading insights.

---

## Data Sources

- Bitcoin Fear & Greed Index  
- Historical Trader Data (Hyperliquid)

---

## Methodology

- Cleaned and validated both datasets (missing values, duplicates)  
- Converted timestamps and aligned data at daily granularity  
- Merged sentiment data with trade-level records  
- Engineered key behavioral and performance metrics:
  - Closed PnL (mean & median)
  - Trade frequency
  - Position size (USD)
  - Long/short ratio  
- Segmented traders into **High Volume vs Low Volume** groups  

---

## Key Insights

1. **Profitability:**  
   Average PnL is slightly higher during Greed periods. However, median PnL remains zero across regimes, indicating skewed returns driven by large outliers.

2. **Risk Behavior:**  
   Traders take significantly larger position sizes during Fear periods.

3. **Market Participation:**  
   Trading activity increases during Greed.

4. **Segmentation Insight:**  
   - High-volume traders perform best during Greed  
   - Low-volume traders show relatively stronger performance during Fear and Neutral  

---

## Strategy Recommendations

1. **Risk Management During Fear:**  
   Reduce position size by 25–30% during Fear periods.

2. **Segment-Based Participation Strategy:**  
   - High-volume traders may increase participation during Greed  
   - Low-volume traders should be more selective during Greed  

---

## How to Run

Open the notebook in Jupyter or Google Colab and execute all cells sequentially to reproduce the analysis..
