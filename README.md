# 🛒 E-commerce Data Analysis(Target)

## 📌 Overview
This Jupyter Notebook provides a comprehensive analysis of e-commerce data, focusing on customer behavior, sales performance, and product trends. It uses:

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- MySQL (for querying and managing data)

---

## 🧱 Table of Contents
- [Setup](#setup)
- [Data Loading](#data-loading)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
  - Unique Customer Cities
  - Orders in 2017
  - Sales per Category
  - Payments Analysis
  - Customer State Distribution
  - Monthly Orders (2018)
  - Avg. Products per Order
  - Seller Revenue
  - Cumulative Monthly Sales
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)

---

## ⚙️ Setup

### ✅ Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - matplotlib
  - seaborn
  - numpy
  - mysql-connector-python

### 🧪 Installation
```bash
pip install pandas matplotlib seaborn mysql-connector-python numpy
```

---

## 📂 Data Loading
Data is loaded from the following CSV files:
- customers.csv
- geolocation.csv
- order_items.csv
- orders.csv
- payments.csv
- products.csv
- sellers.csv

These are imported and stored in a **MySQL database** for efficient querying.

📥 **Dataset Source**:  
🔗 [Click here to download the dataset from Kaggle](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv)

---

## 🧹 Data Cleaning
- Handled missing values
- Renamed columns for consistency
- Converted data types for analysis

---

## 📊 Data Analysis

### ✅ Basic Queries
- Unique customer cities
- Total orders in 2017
- Sales by product category
- % of installment payments
- Customers per state

### 🔄 Intermediate Queries
- Monthly orders in 2018
- Avg. products per order by city
- Revenue % per category
- Correlation between price & purchase count (via NumPy)
- Seller revenue ranking

### 🚀 Advanced Queries
- Moving avg. of order values per customer
- Cumulative monthly sales
- Year-over-year sales growth
- Customer retention rate (6-month window)
- Top 3 spending customers per year

---

## 📈 Visualizations
- Bar charts (customer distribution, revenue)
- Line graphs (monthly trends)

---

## 💡 Key Insights

1. **Top Customer Cities**  
   Most customers are from São Paulo, Rio de Janeiro, and Belo Horizonte.

2. **Sales Growth**  
   2017 and 2018 were peak years for order volume.

3. **Revenue by Category**  
   Electronics and fashion led in revenue generation.

4. **Installment Payments**  
   A large portion of customers used installments, showing a preference for flexible payments.

5. **Top Sellers**  
   A small group of sellers generated most of the revenue.

6. **Price vs. Purchase Correlation**  
   Weak-to-moderate correlation observed using NumPy — price alone doesn’t drive purchase volume.

7. **Seasonal Sales Trends**  
   Strong spikes observed in Q4 months, aligning with holiday periods.

8. **Low Retention Rate**  
   Many customers did not make another purchase within 6 months — room for better re-engagement.

---

## 📌 Conclusion
This analysis reveals deep insights into customer behavior, sales performance, and operational trends in an e-commerce context. It supports smarter marketing, inventory, and pricing strategies.

---

## 🙌 Contributions
Feel free to fork this repo and submit pull requests.

## 📞 Contact +233 551411848 / +233 502990126
- 📧 paakwesiprah20@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/prince-paakwesi-prah/)

