📄 Overview

This project delivers a quantitative analysis of cryptocurrency trading behavior, examining how market sentiment influences profitability, trade size, and risk exposure.

By combining personal trading history with the Crypto Fear & Greed Index, it highlights behavioral biases shaping decision-making under various market conditions.

Goal: Identify actionable patterns in trading behavior and optimize strategies based on market psychology.

🔑 Key Findings
💰 Profitability Trends

Highest average PnL during Extreme Greed: +$67.89/trade

Lowest average PnL during Neutral sentiment: +$34.30/trade

Insight: Strategy performs best during bullish, momentum-driven phases

📉 Risk Exposure

Average trade size peaked during Fear (~$7,816); lowest during Extreme Greed (~$3,112)

Suggests a “buy-the-dip” bias, with larger positions taken in pessimistic markets

PnL volatility highest during Fear and Extreme Greed, indicating elevated risk at extremes

📊 Trade Direction Analysis

Compared long vs. short profitability across sentiment phases

Identified optimal trade direction patterns linked to sentiment

⚡ Volatility Mapping

Measured PnL standard deviation by sentiment category

Trades during Extreme Fear showed the highest unpredictability

🛠️ Technology Stack

Language: Python 3.10+

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook / Google Colab

Data Sources:

Personal Trading Ledger (trades.csv)

Crypto Fear & Greed Index (sentiment.csv)

🔍 Methodology

Data Ingestion

Imported trading history and sentiment data

Data Cleaning & Preprocessing

Standardized date formats with pd.to_datetime

Renamed columns for clarity (e.g., Closed PnL → PnL)

Data Merging

Performed a left join on trade date to map sentiment to each trade

Exploratory Data Analysis (EDA)

Grouped trades by sentiment to calculate:

Mean PnL

Average trade size

Trade frequency

PnL volatility

Visualization

Created insight-oriented plots showing relationships between sentiment, profitability, and behavior

📊 Key Visualizations

PnL Distribution by Sentiment


Average PnL by Sentiment


Trade Size vs. Sentiment


🚀 How to Run
# Clone the repository
git clone https://github.com/waheed24-03/Quantitative-Trading-Behavior-Analysis

# Install dependencies
pip install pandas matplotlib seaborn jupyterlab

# Place datasets in the root directory
csv_files/trades.csv
csv_files/sentiment.csv

# Launch Jupyter Notebook
jupyter lab

👤 Author

Syed Abdul Waheed

Data Science & Machine Learning Enthusiast

📬 LinkedIn

🐙 GitHub
