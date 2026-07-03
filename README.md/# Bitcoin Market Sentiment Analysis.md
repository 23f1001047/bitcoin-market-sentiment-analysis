# Bitcoin Market Sentiment Analysis

## Objective
The objective of this project is to analyze the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid.

## Datasets
- Historical Trader Data
- Bitcoin Fear & Greed Index

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Loaded both datasets.
2. Checked missing values and duplicates.
3. Converted date columns into proper datetime format.
4. Merged both datasets using the Date column.
5. Performed Exploratory Data Analysis (EDA).
6. Created multiple visualizations.
7. Generated insights based on market sentiment and trader performance.

## Visualizations
- Average Closed PnL by Market Sentiment
- Number of Trades by Market Sentiment
- Average Trade Size by Sentiment
- Buy vs Sell Analysis
- Distribution of Closed PnL
- Top 10 Most Traded Coins

## Key Insights
- Extreme Greed showed the highest average Closed PnL (67.89).
- Fear recorded the second-highest average Closed PnL (54.29).
- Neutral and Extreme Fear showed comparatively lower profitability.
- HYPE was the most actively traded coin.
- Market sentiment had a noticeable impact on trading performance.

## Conclusion
This project explored the relationship between Bitcoin market sentiment and trader performance. The analysis indicates that traders generally achieved higher average realized profits during Extreme Greed and Fear periods. These findings suggest that market sentiment can be a useful indicator for understanding trading behavior and supporting better trading decisions.