# Sales Forecasting Project

## Overview
This project predicts future sales using historical order data.

## Problem Statement
To forecast upcoming monthly sales based on past sales patterns.

## Dataset Description
The dataset includes Order Date, Sales, Quantity, Discount, Profit, Category, Region, and product details.

## Workflow
- Data collection
- Data understanding
- Data preprocessing
- Feature engineering
- Model building
- Model evaluation
- Forecast generation
- Output visualization

## Model Used
Random Forest Regressor

## Results
- MAE: 9757.78
- RMSE: 12242.82
- R2: -0.89

## Output Files
- `output/sales_forecasting_metrics.csv`
- `output/sales_forecasting_output.csv`
- `output/sales_forecast_chart.png`

## Run Instructions
```bash
pip install -r requirements.txt
jupyter notebook sales_forecasting.ipynb
```
