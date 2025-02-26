# Analysis-of-Wind-Energy-Time-Series-in-Germany

This data appears to be a table of energy generation in Germany over a 24-hour period from midnight on January 1, 2022. The table contains 35040 rows × 15 columns, each representing a 15-minute interval, and 12 columns representing different sources of energy generation.

This project analyzes wind energy production and electricity prices in Germany using time-series data. It explores patterns, correlations, and forecasting techniques to understand energy trends and market behavior.

# Dataset
The dataset consists of two CSV files:

## 1. Wind Power Data
- Contains historical wind energy production in Germany.
- Data is recorded at 15-minute intervals over a full year (2022).
- The dataset includes multiple energy sources but focuses on:
    - Offshore wind energy generation
    - Onshore wind energy generation
- The values represent megawatt-hours (MWh) of energy produced in each time interval.
- Data Source: smard.de
- 
## 2. Day-Ahead Electricity Prices
- File: Day-ahead_prices_202201010000_202212312359_Quarterhour.csv
- Contains day-ahead electricity market prices for Germany.
- Prices are recorded at 15-minute intervals for the entire year 2022.
- Used to analyze how electricity prices fluctuate in relation to wind energy production.
  
## Dataset Overview
- The dataset contains 35,040 rows × 15 columns, each row representing a 15-minute interval over the year.
- While the full dataset includes 12 different sources of energy generation, this study focuses only on:
     - Offshore wind energy
     - Onshore wind energy
  
## Goals of the Analysis
- Explore trends in offshore and onshore wind energy production.
- Investigate the relationship between wind power generation and electricity prices.
- Apply time-series forecasting techniques to predict future trends.
- Provide insights into market behavior and energy management strategies.
  
## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn) for data analysis and visualization.
- Jupyter Notebook for interactive data exploration.
