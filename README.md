# Trader-s-Performance-and-Market-s-Sentiment-Analysis

## Project Overview
This project analyzes how the trader behavior changes based on market sentiment (Fear vs Greed). The analysis combines historical trading data with the Fear & Greed Index to examine patterns in trading performance, activity, and risk-taking behavior.

## Dataset Description

Two datasets are used:

### 1. Historical Trader Data
Contains individual trade-level information such as:
- Account
- Trade ID
- Timestamp
- Trade Size (USD)
- Closed PnL
- Trade Direction (BUY/SELL)

### 2. Fear & Greed Index
Daily market sentiment indicator with:
- Date
- Sentiment classification (Fear, Greed, Neutral, etc.)
- Sentiment value, etc.

## Key Metrics Created

To analyze trader behavior, the following metrics were derived:

- Daily PnL per trader
- Trade frequency
- Average trade size
- Long vs Short ratio
- Trading activity by sentiment

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Setup Instructions

### 1. Clone the Repository

git clone {Name of the GitHub Repository}

### 2. Navigate to the Project Directory

cd trader-sentiment-analysis

### 3. Install Required Libraries

pip install pandas numpy matplotlib seaborn jupyter

## Running the Project

1. Launch Jupyter Notebook

2. Open the notebook file

3. Run the cells sequentially to reproduce the analysis.

