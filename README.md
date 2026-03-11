# Supply Chain Demand Forecasting & Inventory Optimization System

## Overview

This project develops a **Supply Chain Analytics System** that forecasts product demand and optimizes inventory decisions to reduce operational costs and improve supply chain efficiency.

The system integrates **demand forecasting using machine learning** with **inventory optimization using Operations Research techniques** to support better decision-making in supply chain management.

## Technologies Used

* Python
* Machine Learning (Scikit-learn)
* Linear Programming (PuLP)
* SQL
* Power BI

## Dataset

The dataset contains historical supply chain data including product demand, order quantities, and inventory levels.

Key fields include:

* `date` – Transaction or demand date
* `product_id` – Product identifier
* `region` – Sales region
* `demand` – Product demand
* `inventory_level` – Available inventory

## Methodology

1. Data preprocessing and demand analysis
2. Demand forecasting using machine learning models
3. Inventory optimization using linear programming
4. Performance evaluation and visualization

## Results

* Forecast Accuracy (MAPE): ~6%
* Inventory Cost Reduction: ~18%
* Improved Inventory Utilization: ~92%

## Project Structure

```id="m1n1h8"
Supply-Chain-Optimization
│
├── data
│   └── demand_data.csv
│
├── notebooks
│   └── demand_forecasting.ipynb
│
├── src
│   ├── forecasting_model.py
│   └── inventory_optimization.py
│
└── README.md
```

## Author

Sudhanshu Gupta
M.Tech Operations Research – NIT Durgapur
