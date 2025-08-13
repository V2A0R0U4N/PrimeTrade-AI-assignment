# Trader Behavior & Market Sentiment Analysis

# Overview :-
This project explores how Bitcoin market sentiment impacts trader performance by merging historical trader data (~211k trades) from Hyperliquid with the Fear–Greed Index.
It includes both EDA and advanced quantitative methods to uncover patterns for regime-aware trading strategies.

**Note** : The merged dataset (merged_fear_greed_trades.csv) is too large to upload due to GitHub file size limits. Contact the author for access.

# Feature Engineering Highlights :-
- Profitability flags (is_win), rolling averages, and volatility measures.

- Normalized trade size & PnL values.

- Time-based features (hour, day_of_week, weekend flag).

- Contrarian trade detection.

# Exploratory Data Analysis Dashboard :-
- Sentiment distribution of trades.

- PnL distribution (capped ±40).

- Win rate by sentiment.

- Average PnL: Fear vs Greed.

- 7-day rolling PnL trends.

- Sentiment volatility vs PnL.

# Advanced Methods :-
- Risk-adjusted performance metrics.

- Top trader PnL quantiles.

- Trader archetype clustering.

- Sentiment flip and lag effects.

- Volatility–sentiment–PnL interactions.

- Trade size profitability by sentiment.

- Rolling correlation of sentiment & PnL.

- Sentiment-filtered strategy backtest.

# Key Insights :-
- Greed phases have higher win rates; mild Fear can give better risk-adjusted returns.

- Large trades excel in Greed, risky in Fear.

- Sentiment–PnL correlation changes over time.

- Adaptive, regime-aware strategies outperform static approaches.
