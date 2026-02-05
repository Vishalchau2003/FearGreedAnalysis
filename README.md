# Trader Performance vs Market Sentiment

## Objective
Analyze how trader behavior and performance change under different market sentiment regimes (Fear vs Greed).

## Datasets
- Bitcoin Fear & Greed Index
- Hyperliquid historical trader data

## Methodology
- Converted timestamps to daily dates
- Aggregated trade-level data into daily trader metrics
- Merged trader data with market sentiment
- Analyzed performance and behavior across sentiment regimes
- Segmented traders by activity level

## Key Insights
1. Traders are more profitable during Fear periods.
2. Trade frequency and position size increase during Fear and Greed markets.
3. High-activity traders outperform during Fear periods.

## Strategy Recommendations
- Reduce position size risk during Fear periods.
- Allocate capital selectively to high-activity traders during volatile markets.

## How to Run
```bash
pip install -r requirements.txt
