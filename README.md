# 📊 Intelligent Sales Forecasting and Demand Analysis System

An end-to-end Machine Learning and Business Analytics project developed to forecast retail sales, detect anomalies, segment product demand, and support inventory planning using Python and Streamlit.

---

# Project Objective

The objective of this project is to help retail businesses make better inventory and sales planning decisions by analyzing historical sales data and forecasting future demand.

The project combines:

- Exploratory Data Analysis (EDA)
- Time Series Analysis
- Sales Forecasting
- Machine Learning
- Anomaly Detection
- Product Demand Segmentation
- Interactive Dashboard Deployment

---

# Dataset

Dataset Used:

- Superstore Sales Dataset

Main files:

- train.csv
- vgsales.csv

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-Learn
- XGBoost
- Prophet
- Statsmodels
- Streamlit

---

# Project Workflow

## Task 1 – Exploratory Data Analysis

- Sales Trend Analysis
- Category Analysis
- Regional Sales Analysis
- Monthly Sales Pattern
- Shipping Analysis

---

## Task 2 – Time Series Analysis

- Monthly Sales Aggregation
- Seasonal Decomposition
- Trend Analysis
- Stationarity Test (ADF Test)

---

## Task 3 – Sales Forecasting

Models Implemented:

- SARIMA
- Prophet
- XGBoost

Evaluation Metrics:

- MAE
- RMSE
- MAPE

Best Performing Model:

**XGBoost**

---

## Task 4 – Forecasting Dashboard

Forecasts generated for:

- Furniture
- Technology
- Office Supplies
- East Region
- West Region

Forecast Horizon:

- 1 Month
- 2 Months
- 3 Months

---

## Task 5 – Anomaly Detection

Techniques Used:

- Isolation Forest
- Z-Score Method

Outputs:

- Weekly anomaly chart
- Anomaly report
- Detected anomaly table

---

## Task 6 – Product Demand Segmentation

Algorithm Used:

- K-Means Clustering

Features:

- Total Sales
- Growth Rate
- Volatility
- Average Order Value

Demand Groups:

- High Volume, Stable Demand
- Growing Demand
- Low Volume, High Volatility
- Declining Demand

---

## Task 7 – Interactive Streamlit Dashboard

The dashboard consists of four pages.

### 📈 Sales Overview

- KPI Cards
- Yearly Sales
- Monthly Sales Trend
- Region Filters
- Category Filters

### 📉 Forecast Explorer

- Category Selection
- Region Selection
- Forecast Horizon Selection
- Forecast Chart
- MAE
- RMSE

### 🚨 Anomaly Report

- Weekly Anomaly Chart
- Anomaly Table

### 📦 Product Demand Segments

- Cluster Visualization
- Demand Cluster Table

---

## Task 8 – Executive Business Report

Prepared a professional business report summarizing:

- Executive Summary
- Forecast Results
- Product Demand
- Business Recommendations
- Risks
- Inventory Strategy

---

# Folder Structure

```
SalesForecasting_Hanny_Rangera
│
├── analysis.ipynb
├── app.py
├── requirements.txt
├── summary.pdf
├── train.csv
├── vgsales.csv
├── forecast_results.csv
├── anomaly_results.csv
├── cluster_results.csv
│
└── charts
    ├── 1_monthly_sales_trend.png
    ├── 2_time_series_decomposition.png
    ├── 3_forecast_actual_vs_predicted.png
    ├── 4_category_region_forecasts.png
    ├── 5_anomaly_detection.png
    └── 6_product_clusters.png
```

---

# Dashboard

The application was developed using **Streamlit**.

Dashboard Pages:

- Sales Overview
- Forecast Explorer
- Anomaly Report
- Product Demand Segments

---

# Results

- Successfully forecasted retail sales for future months.
- XGBoost achieved the lowest prediction error.
- Detected abnormal sales weeks using Isolation Forest and Z-Score.
- Segmented products into four inventory groups.
- Built an interactive business dashboard for decision support.

---

# How to Run

Clone the repository

```bash
git clone https://github.com/hannyrangera/SalesForecasting_Hanny_Rangera.git
```

Move into the project folder

```bash
cd SalesForecasting_Hanny_Rangera
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

# Streamlit Deployment

Live App:

(Add your Streamlit URL here after deployment)

---

# Author

**Hanny Rangera**

B.Tech Student

Project developed as part of a Machine Learning and Business Analytics project .