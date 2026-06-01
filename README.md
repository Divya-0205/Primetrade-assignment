# Primetrade-assignment
# Fear & Greed vs Trader Behavior Analysis

## Project Overview

This project explores the relationship between cryptocurrency market sentiment and trader behavior using the Fear & Greed Index and Hyperliquid trading data.

The main goal is to understand whether trader performance changes under different market conditions and how traders react when the market is driven by fear or greed.

## Objectives

The analysis focuses on the following questions:
Does trader performance (PnL and win rate) differ between Fear and Greed periods?
Do traders change their behavior based on market sentiment?
How do different trader segments perform?
What trading strategies can be derived from the findings?

 ## Datasets Used

## Fear & Greed Index

This dataset contains daily sentiment scores and market classifications such as:

Extreme Fear
Fear
Neutral
Greed
 xtreme Greed

### Hyperliquid Trading Data

This dataset contains trade-level information including:

Account ID
Trade timestamp
Position size
Trade direction
Closed PnL
Trade volume

## Methodology

The two datasets were merged using the trading date. After cleaning and preprocessing the data, several metrics were created to analyze trader performance and behavior.

### Performance Metrics

* Average PnL
* Win Rate

### Behavioral Metrics

Trade Frequency
Trading Volume
Average Position Size
Buy/Sell Ratio

### Trader Segments

Frequent vs Infrequent Traders
Consistent Winners vs Inconsistent Traders

## Key Findings

Traders achieved the highest average profitability during Extreme Greed periods.
Win rates were generally higher during optimistic market conditions.
Fear periods showed the highest trading activity and volume.
Traders maintained a buying bias across all sentiment categories.
Frequent traders won more often, while infrequent traders generated higher average profits per trade.

## Strategy Ideas

### Strategy 1

Increase trading activity during Greed and Extreme Greed periods, where profitability and win rates were generally higher.

### Strategy 2

Focus on trade quality rather than trade quantity, as higher trading frequency did not necessarily lead to higher profits.

## How to Run the Project

### 1. Install Dependencies

pip install pandas 
### 2. Open the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

### 3. Run the Analysis

Open the notebook:

```text
Task 1.ipynb
```

Run all cells from top to bottom to reproduce the analysis and visualizations.

## Project Structure
`
fear_greed_index.csv
historical_data.csv
Task 1.ipynb
README.md


## Conclusion

The analysis suggests that market sentiment influences both trader behavior and trading outcomes. While optimistic market conditions were associated with stronger performance, trader success also depended on factors such as trading frequency, position sizing, and consistency.
