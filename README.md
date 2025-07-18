# Blinkit Price Surge Analysis

Welcome to the **Blinkit Price Surge Analysis** project!  
This project investigates how product prices on Blinkit change over time — especially during **weekends, festivals, and peak hours** — and applies ML techniques to forecast future trends.

## Project Overview

Instant delivery platforms like **Blinkit**, **Zomato**, and **Zepto** use dynamic pricing models. This project aims to:

- Analyze historical pricing trends
- Detect surge patterns
- Predict future price surges using machine learning
- Visualize trends via Power BI dashboards

##  Features
-  Exploratory Data Analysis (EDA) to uncover surge triggers
-  Machine Learning Models for surge prediction:
- Forecasting future prices
-  Price comparison across platforms *(optional)*
-  Discount and delivery time correlation analysis

## 🗃 Dataset

**File:** `price_surge_dataset.csv`

**Columns:**
- `date_time`: Timestamp of price snapshot  
- `product_name`: Item being tracked  
- `price`: Recorded price at the time  
- `platform`: Delivery platform (e.g., Blinkit)  
- `discount`, `delivery_time`, `category`, etc.


##  Tech Stack

- **Languages:** Python, SQL
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, TensorFlow/Keras
- **IDE:** Jupyter Notebook, VS Code

##  Use Cases

-  Understand when price surges occur (weekends/festivals)
-  Predict upcoming surges to plan purchases
-  Compare pricing trends across platforms


The full implementation, from data to final model evaluation can be foun in .['mpp2.ipynb'].(./mpp2.ipynb)


