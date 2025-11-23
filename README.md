# 📘 Trader Behavior vs Market Sentiment — Data Science Assignment

This project analyzes how Bitcoin market sentiment (Fear vs Greed) shapes trader behavior on Hyperliquid.
The goal is to uncover patterns in trading performance, execution behavior, and risk-taking under different sentiment conditions.

# 🚀 Project Overview

You are provided with two datasets:

1. Bitcoin Fear–Greed Index

Date

Classification (Fear / Greed)

2. Historical Trader Data (Hyperliquid)

Includes fields such as:
Account, Coin, Execution Price, Size Tokens, Size USD, Side, Timestamp,
Start Position, Direction, Closed PnL, Order ID, and more.

This project explores how sentiment influences:

Trader profitability

Win-rate

Position sizing

Risk-taking behavior

Buy/Sell tendencies

Account-level performance

# 🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook


# 🔍 Key Steps Performed
1. Data Cleaning

Parsed timestamps into datetime

Normalized sentiment labels

Converted numeric fields

Removed invalid & inconsistent rows

Created unified date column for merging

2. Dataset Merging

Merged the trader dataset with the Fear–Greed index using the date key.

3. Exploratory Data Analysis

Computed important behavioral metrics:

Average PnL

Median PnL

Total PnL

Win-rate (%)

Position size differences

Buy/Sell patterns

Account-level performance

4. Visualizations

Generated clear visual insights:

PnL distribution (Fear vs Greed)

Average PnL comparison

Win-rate comparison

Trade size boxplots (Tokens & USD)

# 📊 Insights & Findings
1. Trader performance varies across sentiment cycles

Greed phases show stronger profitability, while Fear introduces higher variance and instability.

2. Win-rate improves during Greed

Positive sentiment increases trader confidence and directional accuracy.

3. Larger position sizes during Greed

Traders take bigger risks in bullish conditions—clear from both token and dollar-based size metrics.

4. Fear periods have wider PnL distributions

Losses and gains become more extreme during uncertainty and volatility.

5. Buy/Sell tendencies shift with sentiment

More BUY activity in Greed; more conservative or defensive behavior in Fear.

6. Account-level behavior shows trader archetypes

Certain traders perform better during Fear (contrarians), while others thrive during Greed (momentum-driven).

# 📘 Conclusion

Market sentiment strongly shapes trader behavior:

Greed → Higher win-rates, larger trades, bullish bias, smoother PnL

Fear → Volatile PnL, cautious sizing, unpredictable outcomes

These insights can help trading teams:

Build sentiment-aware risk models

Create smarter automated strategy filters

Identify traders who excel in specific sentiment regimes

This project highlights how combining behavioral analysis + sentiment data leads to deeper trading intelligence.

# ⭐ Author

Lanson Daniel Bardeskar
MCA Student • Data Science Enthusiast
Government College of Engineering, Karad
