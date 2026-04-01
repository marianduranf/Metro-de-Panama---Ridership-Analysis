# Metro-de-Panama---Ridership-Analysis
Ridership analysis and time series modeling of the Panama Metro using Python.

## Overview
This project analyzes ridership patterns in the Panama Metro system to identify usage trends and explore potential opportunities for operational optimization. 
The analysis combines exploratory data analysis (EDA) with time series modeling techniques (ARIMA/SARIMA) to better understand demand behavior over time.
This project was developed as part of an academic research exercise in Data Science.

---

## Dataset
The dataset consists of historical ridership records from the Panama Metro system, provided in CSV format.

It includes variables such as:
- Date
- Passenger demand (ridership)
- Temporal information for trend analysis

The data was used to explore demand patterns over time and support time series modeling.

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## Methodology

### Data Preparation
- Data cleaning and formatting  
- Handling missing values  
- Time-based indexing for analysis  

### Exploratory Data Analysis (EDA)
- Trend analysis over time  
- Identification of seasonality patterns  
- Detection of anomalies and demand variability  

### Time Series Modeling
- ARIMA/SARIMA models were implemented to capture temporal dependencies  
- Model parameters were informed by ACF and PACF analysis  
- Model performance was evaluated using standard error metrics  

---

## Key Visualizations

The analysis includes visualizations such as:

- Ridership trends over time  
- Seasonal patterns in demand  
- Variability and outlier detection  
- Model predictions vs actual values  

(See images in the `/images` folder or within the notebook.)

---

## Key Insights

- Demand patterns vary significantly over time, showing identifiable trends and seasonality.
- External factors (such as atypical periods) can strongly affect demand behavior.
- Time series models provide a baseline for understanding and forecasting ridership trends.
- Insights from this analysis could support decision-making in transport planning and resource allocation.

---

## Repository Structure
- `PanamaMetro_Analysis.ipynb`: Main notebook containing data cleaning, exploratory analysis, and time series modeling (ARIMA/SARIMA).
- `metro_ridership_line1_2024.csv`: Dataset used for the analysis.
- `README.md`: Project documentation and summary of findings.
