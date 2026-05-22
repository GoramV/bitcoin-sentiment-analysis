# Bitcoin Market Sentiment vs Trader Performance Analysis

## Objective

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

The goal is to identify how market psychology affects:

- Trader profitability
- Trading behavior
- Risk-taking patterns
- Long/short positioning

---

## Datasets Used

### 1. Fear & Greed Index Dataset

Contains:

- Date
- Market sentiment classification
  - Fear
  - Extreme Fear
  - Neutral
  - Greed
  - Extreme Greed

### 2. Hyperliquid Historical Trader Dataset

Contains:

- Account
- Coin
- Side
- Direction
- Closed PnL
- Size USD
- Fees
- Timestamp IST

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

1. Data Cleaning
2. Timestamp Conversion
3. Dataset Merging
4. Feature Engineering
5. Exploratory Data Analysis
6. Trader Segmentation
7. Sentiment-Based Insights
8. Strategy Recommendations

---

## Key Metrics Analyzed

- Closed PnL
- Win Rate
- Trade Frequency
- Average Trade Size
- Long vs Short Ratio
- Daily Trading Activity

---

## Key Insights

### 1. Extreme Greed generated the highest profitability

Aggressive market conditions created larger profit opportunities.

### 2. Contrarian strategies performed better

- BUY during Fear
- SELL during Extreme Greed

### 3. Fear markets encouraged cautious trading

Traders reduced aggressive behavior during bearish sentiment.

### 4. Market sentiment strongly influenced trader behavior

Trade frequency and profitability varied significantly across sentiment categories.

---

## Strategy Recommendations

### Strategy 1

Reduce aggressive long exposure during Extreme Greed periods due to higher reversal risk.

### Strategy 2

Use selective “buy-the-dip” strategies during Fear periods with controlled position sizing.

---

## Files Included

- `Bitcoin_Sentiment_Analysis.ipynb`
- `Presentation.pptx`
- `README.md`

---

## Conclusion

The analysis demonstrates that market sentiment significantly impacts trader profitability and behavior. Integrating sentiment indicators into trading strategies can improve decision-making, risk management, and overall trading performance.
