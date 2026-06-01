# Trader Behavior Analysis Based on Market Sentiment

## Overview

This project investigates the relationship between cryptocurrency trader performance and market sentiment using historical trading data and the Bitcoin Fear & Greed Index.

The objective is to determine whether market sentiment influences trader profitability, trading activity, position sizing, and overall trading behavior.

---

## Datasets Used

### Historical Trader Data
Contains detailed trading records including:

- Account ID
- Trade Direction
- Execution Price
- Position Size
- Closed PnL
- Fees
- Timestamp

### Bitcoin Fear & Greed Index
Contains daily market sentiment information:

- Date
- Sentiment Classification
- Sentiment Value

Sentiment Categories:

- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

---

## Objectives

- Analyze trader behavior across different market sentiment regimes.
- Evaluate profitability during Fear and Greed periods.
- Measure win rates under varying market conditions.
- Study trading activity and position sizing behavior.
- Determine whether sentiment has a statistically significant impact on profitability.

---

## Methodology

### Data Cleaning

- Converted timestamps to datetime format.
- Extracted dates for analysis.
- Removed duplicate records.
- Validated dataset consistency.

### Feature Engineering

- Created Win/Loss indicator.
- Generated sentiment score mappings.
- Computed trader performance metrics.

### Data Integration

Merged trading records with daily sentiment data using date-based joins.

---

## Analysis Performed

### Exploratory Data Analysis (EDA)

- Sentiment Distribution
- Profitability Analysis
- Trading Activity Analysis
- Position Size Analysis
- Long vs Short Trade Distribution

### Trader Performance Analysis

Calculated:

- Total Profit/Loss
- Average Profit/Loss
- Win Rate
- Total Number of Trades

### Statistical Testing

Performed the Kruskal-Wallis test to evaluate whether profitability distributions differ significantly across sentiment categories.

---

## Visualizations

The project includes:

- Average PnL by Sentiment
- Win Rate by Sentiment
- Trading Activity by Sentiment
- Average Position Size by Sentiment
- Long vs Short Distribution
- Correlation Heatmap
- Top 10 Trader Performance Analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab

---

## Project Structure

```text
├── Trader_Behavior_Analysis.ipynb
├── README.md
└── Trader_Performance_Report.csv
```

---

## Results

Key findings and statistical results are documented within the notebook along with supporting visualizations and interpretations.

---

## Conclusion

This analysis provides insights into how market sentiment influences cryptocurrency trading behavior and trader performance. The findings can help in understanding risk-taking patterns, profitability trends, and sentiment-driven market dynamics.

---

## Author

**Akshansh Bakshi**  
B.Tech CSE (Data Science)
