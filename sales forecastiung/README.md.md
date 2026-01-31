# Sales Forecasting Project

This project analyzes monthly sales data and forecasts future sales using time series analysis (ARIMA).

## Problem Statement
Predict future sales from past monthly sales data.

## Dataset
Monthly sales data with two columns: Month and Sales.

## 🛠 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn

## Approach
1. Load and visualize time series data  
2. Convert Month to datetime and set index  
3. Split into train and test sets  
4. Fit ARIMA model  
5. Forecast future sales  
6. Evaluate using RMSE  

## Results
The model forecasts the last 3 months and evaluates accuracy using RMSE.

## How to Run
1. Install dependencies:
```
pip install pandas matplotlib statsmodels scikit-learn
```
2. Run Jupyter Notebook:
```
jupyter notebook
```
3. Open `sales_forecasting.ipynb`

## Project Structure
```
sales-forecasting/
│── data/
│   └── monthly_sales.csv
│── sales_forecasting.ipynb
│── README.md
```
