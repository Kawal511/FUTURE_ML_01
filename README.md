# Sales Forecasting Dashboard

## Overview
This project predicts future retail sales using historical transaction data. We utilize **Facebook Prophet** for time series forecasting and **Power BI** for interactive dashboarding.
## Dataset
Sales data from a retail business containing transaction information such as order dates, product lines, and sales figures.

Dataset source: [Sample Sales Data (Kaggle)](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
## Key Features
-   **Forecasting**: Predicts sales for the next 90 days.
-   **Seasonality**: Captures Weekly and Yearly sales patterns.
-   **Insights**: Identifies top-selling products and high-growth periods.

## Key Insights
-   **Trend**: Overall sales trajectory is positive, with distinct seasonal peaks.
-   **Seasonality**: Strong weekly patterns observed (e.g., higher sales on specific weekdays) and yearly peaks around holiday seasons.
-   **Top Performers**: Specific product lines drive the majority of revenue (see Dashboard for details).

## Project Structure
-   `Sales_Forecasting_Analysis.ipynb`: Python notebook for data cleaning, EDA, and modeling.
-   `forecast_results_full.csv`: The final dataset containing Actuals + Forecasts for Power BI.


## Tools
-   **Python**: Pandas, Prophet, Seaborn.
-   **Power BI**: For visualization and reporting.
