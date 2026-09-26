# 🛒 E-Commerce Sales Analysis

## 📌 Project Overview

This project performs an exploratory analysis of an e-commerce sales dataset using Python.

The analysis focuses on sales, profit, quantity sold, categories, sub-categories, cities, states, payment modes, and monthly sales trends.

The goal is to identify meaningful patterns and generate data-driven business insights.

---

## 🎯 Objectives

- Analyze overall sales and profit
- Identify high-sales categories and sub-categories
- Analyze monthly sales trends
- Compare sales and profit across states and cities
- Analyze different payment modes
- Identify areas with negative or low profitability
- Generate business-oriented insights using data

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains two files:

- `Orders.csv` — Order information such as order date, customer, state and city
- `Details.csv` — Sales details such as amount, profit, quantity, category, sub-category and payment mode

The two datasets were merged using `Order ID`.

---

## 🔄 Data Preparation

The following preprocessing steps were performed:

1. Loaded the Orders and Details datasets.
2. Converted the Order Date column into datetime format.
3. Merged both datasets using `Order ID`.
4. Created additional fields for monthly analysis.
5. Performed aggregation and exploratory analysis.

---

## 📊 Analysis Performed

### Category Analysis

Compared:

- Sales
- Profit
- Quantity
- Profit Margin

across different product categories.

### Monthly Sales Analysis

Analyzed monthly sales trends to understand changes in sales over time.

### State-wise Analysis

Compared sales, profit and quantity sold across different states.

### City-wise Analysis

Identified cities with high sales and profit.

### Sub-Category Analysis

Analyzed individual product sub-categories based on sales, profit and quantity.

### Payment Mode Analysis

Compared sales, profit and activity across different payment modes.

---

## 💡 Key Insights

- Total sales were ₹4,37,771 and total profit was ₹36,963.
- Electronics generated the highest sales among the categories.
- Clothing recorded the highest profit margin among the categories.
- Indore recorded the highest sales among the cities analyzed.
- Indore also recorded the highest total profit among the cities shown.
- Mumbai generated high sales but comparatively low total profit.
- Electronic Games recorded negative aggregate profit despite generating substantial sales.
- COD recorded the highest sales among the payment modes.

---

## 📈 Visualizations

The project includes visualizations for:

- Sales vs Profit by Category
- Monthly Sales Trend
- Top Cities by Sales
- Top Cities by Profit
- Sales by Payment Mode
- Profit Margin by Category

---

## 🚀 Future Improvements

- Build an interactive Power BI dashboard
- Add customer-level analysis
- Perform customer segmentation
- Analyze product profitability in greater detail
- Develop sales forecasting models
- Add advanced statistical analysis

---

## 👨‍💻 Author

**Yuvraj**

BTech AI/ML Student

GitHub: [yuvraj1160](https://github.com/yuvraj1160)**
