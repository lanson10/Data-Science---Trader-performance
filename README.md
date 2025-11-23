Trader Behavior vs Market Sentiment — Data Science Assignment

This project explores how Bitcoin market sentiment (Fear vs Greed) affects trader behavior on Hyperliquid.
The goal is to uncover patterns in execution, profitability, and risk-taking across different sentiment phases.

🚀 Project Overview

You are provided with two datasets:

Bitcoin Fear–Greed Index
Columns: Date, Classification

Historical Trader Data (Hyperliquid)
Columns include:
Account, Coin, Execution Price, Size Tokens, Size USD, Side, Timestamp,
Start Position, Direction, Closed PnL, Order ID, etc.

The objective is to analyze how market sentiment influences:

Trader profitability

Win-rate

Position sizing

Risk-taking behavior

Buy/Sell tendencies

Account-level performance

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📂 Repository Structure
├── DS Assignment.ipynb        # Full analysis notebook
├── fear_greed_index.csv       # Sentiment dataset
├── historical_data.csv        # Trader dataset
├── DS Assignment.html         # Exported HTML version
└── README.md                  # Project documentation

🔍 Key Steps Performed
1. Data Cleaning

Parsed timestamps into datetime

Normalized sentiment labels

Cleaned numeric fields

Removed incomplete and invalid rows

Created unified date column for merging

2. Dataset Merging

Merged trader executions with Fear–Greed sentiment using the date key.

3. Exploratory Data Analysis

Computed:

Average PnL

Median PnL

Total PnL

Win-rate (%)

Trade size differences

Buy/Sell behavior

Account-level PnL patterns

4. Visualizations

Created visual insights for:

PnL distribution (Fear vs Greed)

Average PnL

Win-rate comparison

Trade size in tokens & USD

📊 Insights & Findings
1. Trader performance varies across sentiment cycles

Greed phases are generally more profitable, while Fear introduces instability.

2. Win-rate increases during Greed

Positive sentiment boosts trader confidence and directional accuracy.

3. Traders use larger position sizes during Greed

Both Token and USD trade size plots confirm more aggressive trading in bullish sentiment.

4. Fear periods have wider PnL distributions

Losses and gains become more extreme due to volatility.

5. Buy/Sell tendencies shift

More BUY trades occur during Greed, while activity becomes defensive during Fear.

6. Account-level behavior shows unique patterns

Some accounts perform better during Fear, signaling contrarian strategies.

📘 Conclusion

Market sentiment plays a major role in influencing trader behavior:

Greed → higher win-rates, larger trades, more buying, smoother PnL

Fear → volatile outcomes, cautious sizing, erratic profitability

These patterns can help trading teams:

Build sentiment-aware risk models

Develop smarter automated trading filters

Identify traders who thrive in different market conditions

This analysis demonstrates the value of combining market psychology and trader behavior to improve decision-making.


⭐ Author

Lanson Daniel Bardeskar
MCA Student • Data Science Enthusiast
Government College of Engineering, Karad
