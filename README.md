# 🛒 ShopSphere E-Commerce Sales Performance Analysis

## 📌 Project Overview

This project presents an end-to-end analysis of the ShopSphere India e-commerce dataset containing **200,000 orders** across **2024–2025**.

The objective was to analyze sales performance, profitability, customer behavior, product performance, geographic trends, and identify actionable business insights.

The project was completed using **Python, SQL, and Power BI**.

---

## 📊 Dataset Overview

- **Rows:** 200,000
- **Columns:** 24
- **Unique Orders:** 200,000
- **Unique Customers:** 49,054
- **Duplicate Rows:** 0
- **Missing Values:** 0
- **Date Range:** January 2024 – December 2025

### Columns

`Order_ID`, `Order_Date`, `Customer_ID`, `Customer_Name`, `Age`, `Gender`, `City`, `Product_ID`, `Product_Name`, `Brand`, `Category`, `Quantity`, `Unit_Price`, `Discount`, `Revenue`, `Discount_Amount`, `Final_Sales`, `Cost`, `Profit`, `Profit_Margin`, `Payment_Method`, `Order_Status`, `Shipping_Days`, `Rating`

---

## 🛠️ Tools & Technologies

- **Python** — Data cleaning, analysis and visualization
- **Pandas & NumPy** — Data manipulation and calculations
- **Matplotlib & Seaborn** — Exploratory data visualization
- **SQL** — Business analysis and querying
- **Power BI** — Interactive dashboard and business reporting
- **Jupyter Notebook** — Analysis workflow

---

## 🔍 Analysis Performed

### 1. Data Quality Analysis

- Checked dataset structure and data types
- Checked missing values
- Checked duplicate records
- Validated sales and profit calculations
- Converted and validated date fields

### 2. Sales Performance Analysis

- Overall sales and profit
- Monthly sales trends
- 2024 vs 2025 comparison
- Year-over-year sales growth
- Average Order Value (AOV)
- Category performance

### 3. Customer Analysis

- Customer purchasing behavior
- Repeat vs one-time customers
- Customer revenue contribution
- Top customers
- Customer concentration analysis

### 4. RFM Customer Segmentation

Customers were segmented using:

- **Recency**
- **Frequency**
- **Monetary Value**

Segments included:

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Hibernating
- New Customers
- Others

### 5. Product & Profitability Analysis

- Product sales performance
- Product profitability
- Profit margins
- Revenue-driving products
- High-performing products
- Product segmentation

### 6. Geographic Analysis

Sales performance was analyzed across major Indian cities to identify:

- High-performing cities
- Declining cities
- Category-level geographic trends
- Product-level contributors to sales changes

---

## 📈 Key Business Findings

### Overall Performance

- **Total Sales:** ₹4.11B
- **Total Profit:** ₹1.23B
- **Total Orders:** 200K
- **Total Customers:** 49K
- **Average Order Value:** ₹20.55K
- **Overall Profit Margin:** 30.0%

### Sales Trend

Overall sales declined slightly in 2025 compared with 2024, with approximately **-0.73% YoY growth**.

February 2025 recorded the largest monthly decline compared with February 2024.

### Category Performance

**Electronics** was the dominant category, generating approximately **68.75% of total sales**.

Electronics and Home & Kitchen together contributed approximately **84% of total sales**.

### Customer Insights

Approximately **92.5% of customers were repeat customers**, demonstrating strong customer retention.

Repeat customers generated approximately **98.1% of total revenue**.

### RFM Insights

Champions generated the largest revenue contribution at approximately **28.2% of total historical revenue**.

At Risk and Hibernating customers together represented approximately **30.1% of historical revenue**, highlighting a significant group that could be targeted through retention campaigns.

### Product Insights

Stars and Revenue Driver products together generated approximately **90.9% of total sales and profit**.

### Geographic Insights

Sales performance varied across cities, with some cities showing growth while others experienced declines.

Electronics was a major contributor to declines in several underperforming cities.

---

## 💡 Business Recommendations

1. **Protect the Electronics category**  
   Electronics contributes the majority of revenue, so inventory, pricing, and product availability should be closely monitored.

2. **Target At Risk and Hibernating customers**  
   Use personalized offers, reminders and reactivation campaigns to encourage repeat purchases.

3. **Strengthen high-performing products**  
   Maintain inventory and marketing support for Star and Revenue Driver products.

4. **Investigate declining cities**  
   Analyze pricing, inventory, competition and product availability in cities experiencing sales declines.

5. **Improve customer retention**  
   Continue loyalty programs and personalized recommendations for repeat customers.

6. **Monitor monthly performance**  
   Track periods with significant YoY declines and investigate the underlying product and geographic drivers.

---

## 📊 Power BI Dashboard

The project includes an interactive Power BI dashboard covering:

- Sales
- Profit
- Orders
- Customers
- AOV
- Profit Margin
- Monthly Sales Trends
- Sales by Category
- Sales by City
- 2024 vs 2025 comparison

---

## 📁 Project Files

| File | Description |
|---|---|
| `shopsphere_ecommerce_200k.csv` | Original dataset |
| `Ecommerce_Sales_Customer_Analytics.ipynb` | Python analysis notebook |
| `ecommerce_dashboard.pbix` | Power BI dashboard |
| `ShopSphere-E-Commerce-Data-Analysis.pptx` | Project presentation |
| `ShopSphere_Ecommerce_Final_Report.pdf` | Detailed project report |

---

## 🎯 Conclusion

The analysis shows that ShopSphere has a strong repeat-customer base and a healthy overall profit margin, but overall sales experienced a slight decline in 2025.

The business is highly dependent on Electronics and a relatively concentrated group of high-performing products. At the same time, a significant portion of historical revenue is associated with At Risk and Hibernating customers.

The analysis therefore highlights opportunities around **customer retention, electronics performance, product prioritization, and targeted geographic interventions**.

---

## 👤 Author

**Vivek Gupta**

Data Analytics Portfolio Project
