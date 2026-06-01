# 📱 Mobile Sales Analysis Dashboard

## 📌 Project Overview

This Power BI project analyzes mobile phone sales data from 2021 to 2023 across different brands, cities, mobile models, payment methods, and customer ratings.

The objective of this dashboard is to help stakeholders monitor sales performance, identify trends, analyze customer behavior, and support data-driven decision-making.

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling
- Microsoft Excel

---

## 📂 Dataset Information

### Sales_Data
Contains transactional sales information:

- Transaction ID
- Brand
- Mobile Model
- Units Sold
- Price Per Unit
- Customer Name
- City
- Payment Method
- Customer Rating
- Date
- Day Name
- Rating Status

### Custom_Calendar
Date table used for time intelligence calculations.

---

## 📊 Dashboard Pages

### 1. Executive Dashboard

Provides an overview of:

- Total Sales
- Total Quantity Sold
- Total Transactions
- Average Selling Price
- Sales by City
- Sales by Mobile Model
- Sales by Day Name
- Transactions by Payment Method
- Customer Rating Analysis

---

### 2. Month-To-Date (MTD) Report

Tracks cumulative sales performance throughout the month.

Key Metric:

- MTD Sales

---

### 3. Same Period Last Year (SPLY)

Compares current sales with the same period from the previous year.

Key Metrics:

- Total Sales
- Same Period Last Year Sales
- Year-over-Year Comparison

---

## 📈 Key DAX Measures

### Total Sales

```DAX
Total_Sales =
SUMX(
    Sales_Data,
    Sales_Data[Units Sold] * Sales_Data[Price Per Unit]
)
```

🔍 Business Insights
Identified top-performing cities based on revenue.
Compared sales across multiple mobile brands.
Analyzed customer payment preferences.
Monitored monthly sales trends.
Evaluated customer satisfaction through rating analysis.
Performed year-over-year sales comparison.

🚀 Future Improvements
Forecasting using Power BI Forecasting.
Customer segmentation analysis.
Profitability analysis by brand.
Integration with SQL Database.

👨‍💻 Author
Abhishek Mishra

LinkedIn:
https://linkedin.com/in/abhishek-mishra-90a60031a

GitHub:
https://github.com/MishraJiAbhishek
