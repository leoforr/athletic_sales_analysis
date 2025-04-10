# 📊 Athletic Sales Analysis

This project analyzes sales data related to athletic products using Python and pandas, offering business insights through data exploration and visualization. The notebook focuses on identifying sales trends, top-selling products, and peak purchasing periods to support strategic business decisions.

---

## Goals

- Understand overall sales performance.
- Identify best-selling products and most profitable months.
- Discover patterns by city, time of day, and customer behavior.

---

## Tools Used

- **Python 3**
- **pandas** – Data manipulation
- **matplotlib** & **seaborn** – Data visualization
- **Jupyter Notebook** – Interactive analysis

---

## Dataset

The analysis uses a compiled dataset of sales transactions. Each entry includes:

- Product
- Price
- Quantity Ordered
- Order Date
- Purchase Address

The raw data is sourced from multiple monthly CSV files and combined for analysis.

---

## Key Steps

1. **Data Cleaning**
   - Removed NaN values
   - Filtered invalid rows
   - Converted columns to appropriate types

2. **Feature Engineering**
   - Extracted month, hour, and city from datetime and address
   - Calculated sales = quantity × price

3. **Exploratory Data Analysis**
   - Best month for sales
   - Top cities by revenue
   - Frequently bought product combos
   - Sales by hour of the day

4. **Visualizations**
   - Bar charts for revenue per month
   - Line plots for hourly sales trends
   - Heatmaps for product pair frequency

---

## Sample Insights

- **December** had the highest revenue, hinting at holiday demand.
- **San Francisco** and **Los Angeles** led in total sales.
- Most orders were placed between **11 AM and 1 PM**.
- The product often bought with “AAA Batteries” was “USB-C Charging Cable”.

---

## How to Run

1. Clone this repo or download the notebook.
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open `athletic_sales_analysis.ipynb` in Jupyter.
4. Run all cells sequentially.

---

## Future Improvements

- Integrate forecasting models for future sales prediction
- Develop a dashboard using Streamlit or Dash
- Add
