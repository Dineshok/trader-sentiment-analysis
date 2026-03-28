# Trader Performance vs Market Sentiment

## Setup
pip install pandas numpy matplotlib

## How to run
1. Place datasets in a `data/` folder
2. Run all cells top to bottom in `notebook.ipynb`

## Key Findings
- Extreme Greed days produce highest avg PnL ($130) and win rate (89%)
- Fear days drive the most trading activity and largest trade sizes — opposite of intuition
- Infrequent traders outperform frequent traders across all sentiment regimes
- Biggest edge for infrequent traders: Greed days ($485 avg PnL per trade)

## Strategy Rules
1. Conviction traders: size up on Greed and Fear days, reduce on Neutral
2. Frequent traders: best edge only on Extreme Greed — reduce activity elsewhere
```
