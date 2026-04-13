# 🛒 E-Commerce Sales & Profit Analysis

An independent exploratory data analysis project on e-commerce sales
and profit data across products, categories and regions.
Built as part of my Data Science learning journey.

---

## 📌 Project Overview

This project analyses 3,500 e-commerce orders to uncover sales trends,
profit patterns, and regional performance across four regions and multiple
product categories. Unlike previous projects, this analysis was completed
independently without a tutorial.

---

## 📂 Dataset

- **Dataset:** [E-Commerce Sales and Profit Analysis Dataset](https://www.kaggle.com/datasets/nalisha/e-commerce-sales-and-profit-analysis-dataset)

---

## 🛠️ What Was Done

- Loaded and inspected the dataset using `.info()`, `.head()`, `.describe()`
- Converted Order Date to datetime and extracted Year, Month, Day of Week
- Analysed distributions of Sales, Profit and Quantity
- Compared orders and performance across Categories and Regions
- Built scatter plots to explore Sales vs Profit and Quantity relationships
- Calculated Average Profit and Total Sales by Category and Region
- Engineered a Profit Margin column — `Profit / Sales * 100`
- Analysed Profit Margin by Category and Region
- Plotted Monthly Sales and Profit trends to identify seasonality
- Identified best and worst performing months
- Ranked Top 10 most profitable products
- Built a correlation heatmap across Sales, Profit, Quantity and Month

---

## 📊 Key Findings

- January had the highest overall monthly sales
- April had the lowest overall monthly sales
- Bulk orders do not always generate higher profit

---

## 🧰 Tools & Libraries

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 File Structure
ecommerce-sales-profit-analysis/
│
├── Notebook.ipynb                  # Main analysis notebook
├── data/
│   └── ecommerce_sales.csv         # Raw dataset
└── README.md                       # Project documentation

---

## 💡 Key Learnings

- Month names must be converted to numbers to plot chronologically
- Scatter plots reveal relationships between numeric variables better than line plots
- Grouping before plotting avoids messy spike charts on raw data
- Profit Margin is a better measure of efficiency than raw profit alone

---

## 👤 Author

**Lindokuhle Nyoka**
[GitHub](https://github.com/lk-nyoka) · [LinkedIn](https://linkedin.com/in/lindokuhle-nyoka-982019245)
