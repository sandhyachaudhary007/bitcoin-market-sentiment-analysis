# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project explores the relationship between Bitcoin market sentiment and trader performance using two datasets:

1. Bitcoin Fear & Greed Index Dataset
2. Hyperliquid Historical Trader Data

The objective is to investigate how market sentiment influences trader profitability, win rates, trading behavior, and risk, and to uncover patterns that can support smarter trading decisions.

---

## Datasets Used

### 1. Bitcoin Market Sentiment Dataset

Columns include:

* Date
* Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)
* Sentiment Value

### 2. Hyperliquid Historical Trader Data

Columns include:

* Account
* Coin
* Execution Price
* Size Tokens
* Size USD
* Side (BUY/SELL)
* Closed PnL
* Fee
* Timestamp
* Transaction Details

---

## Project Workflow

### Data Preparation

* Loaded and inspected both datasets
* Checked data types and missing values
* Converted timestamps into datetime format
* Created a common trade date column
* Merged sentiment and trading datasets

### Exploratory Data Analysis

* Distribution of trades across sentiment categories
* Profitability analysis by sentiment
* Win rate analysis
* Buy vs Sell performance comparison
* Trade size analysis
* Fee analysis
* Coin-wise profitability analysis
* Top trader analysis
* Risk (PnL volatility) analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Key Findings

### 1. Market Sentiment Influences Profitability

Extreme Greed periods generated the highest average profit per trade compared to other sentiment categories.

### 2. Win Rates Improve During Extreme Greed

Traders achieved the highest win rates during Extreme Greed market conditions.

### 3. Fear Drives Trading Activity

Fear periods recorded the largest number of trades, indicating increased market participation during uncertainty.

### 4. Trade Direction Matters

BUY trades performed better during Fear periods, while SELL trades outperformed during Greed and Extreme Greed periods.

### 5. Trader Behavior Changes With Sentiment

Trade sizes and fees varied across sentiment categories, suggesting changes in risk appetite and activity levels.

### 6. Risk Varies Across Market Conditions

PnL volatility differed across sentiment categories, highlighting the importance of balancing profitability and risk.

---

## Project Structure

├── Trader_Performance_Analysis.ipynb

├── fear_greed_index.csv

├── historical_data.csv

└── README.md

---

## Conclusion

The analysis demonstrates a measurable relationship between Bitcoin market sentiment and trader performance. Extreme Greed conditions were associated with higher profitability and win rates, while Fear conditions led to increased trading activity. These findings suggest that sentiment indicators can provide valuable context for evaluating trading opportunities and managing risk.
