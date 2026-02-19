# PrimeTrade Junior Data Scientist Assignment: Trader Behavior Insights

This repository contains the completed assignment for the Junior Data Scientist role at PrimeTrade. The project explores the relationship between Bitcoin market sentiment and historical trader performance on the Hyperliquid platform.

**Objective:** To uncover patterns in trader behavior and PnL relative to market sentiment and to deliver insights that can drive smarter trading strategies.

## Files in this Repository:

**`Trader_Sentiment_Analysis.ipynb`**: The main Jupyter Notebook containing all the Python code, analysis steps, visualizations, interpretations, and conclusions.
**`fear_greed_index.csv`**: The dataset for Bitcoin market sentiment (Fear & Greed Index).
**`historical_data.csv`**: The dataset containing historical trader data from Hyperliquid.
**`README.md`**: This file.

## How to View and Run the Analysis:

1. **View Online:** The Jupyter Notebook (`Trader_Sentiment_Analysis.ipynb`) can be viewed directly on GitHub.
2. **Run Locally:**
    * Clone or download this repository.
    * Ensure you have Python 3 installed along with the following libraries:
        * `pandas`
        * `numpy`
        * `matplotlib`
        * `seaborn`
        * `jupyter` (for running the notebook)
    * You can install these using pip:

        ```bash
        pip install pandas numpy matplotlib seaborn notebook
        ```

    * Navigate to the cloned/downloaded directory in your terminal.
    * Launch Jupyter Notebook:

        ```bash
    
        jupyter notebook
        ```

    * Open the `Trader_Sentiment_Analysis.ipynb` file from the Jupyter dashboard.
    * Ensure the CSV data files (`fear_greed_index.csv` and `historical_data.csv`) are in the same directory as the notebook for the code to run correctly.

## Summary of Findings:

The analysis revealed a significant correlation between market sentiment and trader performance/behavior:
*Trading during **"Extreme Greed"** conditions was found to be detrimental to PnL, despite traders adopting a contrarian (shorting) stance.
**"Fear"** (specifically when the sentiment index value was 44), **"Neutral"**, and **"Greed"** were generally profitable periods, with traders predominantly maintaining a bullish bias.
Behavioral shifts in trade sizing and directional bias were observed across different sentiment states.

Detailed insights and actionable strategy suggestions are provided within the Jupyter Notebook.

---
Submitted by: Prakash Sharma
Date: 26/5/2025
