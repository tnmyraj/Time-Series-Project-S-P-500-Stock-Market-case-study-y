📊 S&P 500 Stock Correlation Analysis
This Jupyter Notebook explores the correlation between different S&P 500 company stock closing prices using Python libraries such as Pandas, Matplotlib, and Seaborn.

📁 Project Overview
The notebook performs the following steps:

1. Data Collection

    * Loads multiple CSV files using glob and merges them into a single DataFrame.

    * Each CSV contains historical stock price data for a company listed on the S&P 500 index.

2. Exploratory Data Analysis

    *  Displays samples of the dataset.

    *  Visualizes the relationship between various stock prices using Seaborn.

3. Correlation Analysis

    *  Computes a correlation matrix using .corr().

    *  Plots a heatmap to understand how different stocks move relative to each other.
