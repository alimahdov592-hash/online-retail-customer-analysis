# 🛍️ Online Retail Customer & Retention Analysis

## 📌 Project Overview
This project analyzes an Online Retail dataset to uncover product, time-based, and customer insights, then applies **RFM segmentation** to identify high-value customer groups.
A simple **machine learning baseline** is also included to predict invoice-level sales.

## 🔎 What’s inside
- Data loading from **PostgreSQL**
- Data cleaning (missing values, outliers, date parsing)
- Product insights (top products, revenue contribution)
- Time analysis (sales trends by month/weekday)
- Customer analysis + **RFM segmentation**
- ML baseline (Linear Regression) for predicting total invoice sales

## 🧰 Tech Stack
- Python: Pandas, NumPy
- Visualization: Matplotlib, Seaborn, Plotly
- Database: PostgreSQL (SQLAlchemy)
- ML: scikit-learn

## 🚀 How to run locally
1) Create a virtual environment and install dependencies:
```bash
pip install -r requirements.txt
```

2) Create a `.env` file (do **not** commit it) based on `.env.example` and set your database connection:
```bash
DATABASE_URL=postgresql+psycopg2://user:password@localhost:5432/onlineretail
```

3) Open the notebook:
- `notebooks/online_retail_analysis.ipynb`

## 🧠 Skills Demonstrated
Data Cleaning | Exploratory Data Analysis | Customer Segmentation (RFM) | Feature Engineering | Model Evaluation
