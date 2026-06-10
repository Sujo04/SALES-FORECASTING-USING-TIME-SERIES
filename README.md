# Sales Forecasting using Time Series Analysis

## Project Overview

This project focuses on forecasting future sales using Time Series Analysis on the Superstore Sales Dataset. The objective is to analyze historical sales patterns, identify trends and seasonality, and predict future sales using Facebook Prophet.

The project demonstrates key Data Science concepts including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Time Series Forecasting
- Model Evaluation
- Business Insights Generation

---

## Dataset

Dataset: Superstore Sales Dataset

Features include:

- Order Date
- Customer Information
- Product Details
- Category
- Region
- Sales

The dataset contains transactional sales records from multiple regions and product categories.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Facebook Prophet
- Google Colab

---

## Project Workflow

### 1. Data Preprocessing

- Converted Order Date to datetime format
- Aggregated transactional sales into daily sales
- Removed outliers using IQR method
- Prepared data for forecasting

### 2. Exploratory Data Analysis

Performed:

- Sales Trend Analysis
- Category-wise Sales Analysis
- Region-wise Sales Analysis
- Monthly Sales Trend Visualization

### 3. Time Series Forecasting

Implemented Facebook Prophet for:

- Trend Analysis
- Seasonality Detection
- Future Sales Prediction

### 4. Model Evaluation

Metrics Used:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

Results:

- Initial RMSE: 3069.45
- Improved RMSE: 1640.70
- MAE: 1375.38

---

## Forecast Visualization

The model generates:

- Future Sales Forecast
- Trend Components
- Seasonality Analysis

---

## Business Insights

### High Performing Categories

Identified categories contributing the highest revenue.

### Regional Performance

Analyzed sales performance across different regions.

### Sales Trend

Observed seasonal patterns and overall sales growth trends.

### Forecasting

Predicted future sales to support:

- Inventory Planning
- Revenue Forecasting
- Business Decision Making

---

## Project Structure

Sales-Forecasting-Time-Series/

│

├── train.csv

├── Sales_Forecasting.ipynb

├── README.md

├── requirements.txt

├── images/

│ ├── sales_trend.png

│ ├── forecast.png

│ └── seasonality.png

└── sales_forecast.csv

---


---

## Future Improvements

- XGBoost Forecasting
- LSTM Deep Learning Forecasting
- Hyperparameter Optimization
- Interactive Power BI Dashboard

---

## Author

Sujoy P T

M.Sc Data Science


