# Trader Performance vs Market Sentiment Analysis

## Objective

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on Hyperliquid.

## Dataset

### Fear & Greed Dataset

* Timestamp
* Value
* Classification
* Date

### Hyperliquid Historical Trading Dataset

* Account
* Coin
* Execution Price
* Size USD
* Side
* Closed PnL
* Timestamp
* Additional trading attributes

## Methodology

1. Data Cleaning and Validation
2. Timestamp Standardization
3. Daily-Level Dataset Alignment
4. Feature Engineering
5. Sentiment-Based Performance Analysis
6. Trader Behavior Segmentation
7. Strategy Recommendation Generation

## Key Insights

### Insight 1

Trader profitability is highest during Greed sentiment periods with an average Closed PnL of 87.89.

### Insight 2

Position sizes increase significantly during Extreme Greed periods, indicating higher risk-taking behavior.

### Insight 3

Greed periods show a stronger sell-side bias, suggesting active profit-taking behavior.

## Recommendations

1. Increase participation during Greed sentiment periods.
2. Reduce position size during Extreme Greed conditions.
3. Implement sentiment-aware risk management strategies.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure

```text
data/
notebooks/
outputs/
README.md
requirements.txt
```
