# 📊 Customer & Sales Insights from a Retail Discount Campaign

## 📌 Project Overview
This project analyzes customer behavior, sales performance, and the effectiveness of a year-end discount email campaign for a boutique retail company. The goal is to transform raw business data into meaningful insights that support data-driven decision-making.

The analysis focuses on understanding:
- Who the customers are
- What products sell the most
- Which regions contribute higher sales
- Whether discount campaigns influence purchasing behavior

---

## 🎯 Objectives
- Evaluate overall sales performance during Q1 2025  
- Analyze customer behavior and spending patterns  
- Identify sales trends across product categories  
- Assess the effectiveness of the discount email campaign  
- Support business and marketing decisions using data insights  

---

## 🗂️ Datasets Used

| Dataset | Description |
|------|------------|
| Customer_Information.csv | Customer demographics (name, age, gender, address, email) |
| Product_Information.xlsx | Product details including name, category, and price |
| Purchase_Information.xlsx | Transaction-level purchase data |
| Discount_Information.xlsx | Email campaign data with discount codes and percentages |

---

## 🧹 Data Cleaning & Preprocessing

### Customer Data
- Created full names by combining first and last name  
- Removed duplicate customer records  
- Standardized address spellings (e.g., *delhii → Delhi*)  
- Removed invalid age values (negative ages)

### Product Data
- Extracted product category and gender from product names  
- Standardized product prices into numeric format  

### Purchase Data
- Converted all transaction dates to a single standard format  
- Replaced missing discount codes (`.`) with **No Discount**  
- Created a **Discount_Flag** column  
- Standardized purchase amount values  

### Discount Data
- Engineered features from email dates (weekday vs weekend)  
- Prepared data for campaign reach and conversion analysis  

All datasets were joined only where logically required to maintain data integrity.

---

## 🔍 Key Analyses Performed

### Customer Analysis
- Unique purchasing customers  
- Average spend per customer  
- Regional distribution of customers  

### Sales Analysis
- Total sales revenue  
- Product and category-level sales trends  

### Campaign Analysis
- Campaign reach and conversion  
- Comparison of spending with and without discounts  
- Effectiveness of individual discount codes  

### Advanced Analysis
- Boxplots for prices, quantities, discount percentages, and customer spend  
- Outlier detection for unusual purchase behavior  
- Correlation analysis between:
  - Discount percentage and purchase amount  
  - Product price and quantity purchased  

---

## 📈 Key Insights
- Sales are concentrated in specific product categories such as skirts and trousers  
- Customer demand varies significantly across regions  
- Discounted purchases show a slightly higher average spend, but the effect is marginal  
- Correlation between discount percentage and purchase amount is very weak  
- Product pricing across most categories is standardized with limited variation  

---

## 🧠 Tools & Technologies
- Python (Pandas, Matplotlib)  
- Orange Tool  
- Google Sheets  
- Google Colab / Jupyter Notebook  
- NotebookLM (used as a support tool for structuring and presentation clarity)

---

## 📌 Conclusion
The analysis indicates that the year-end discount email campaign had a **moderate positive impact**, primarily influencing customer conversion rather than significantly increasing transaction value. Product category and regional insights provide clear direction for inventory planning and targeted marketing strategies.

---

## 🚀 Future Scope
- Customer lifetime value (CLV) analysis  
- Time-series sales analysis over multiple quarters  
- Improved demographic data collection  
- Long-term campaign performance evaluation  

---

## 📬 Feedback
Feedback, suggestions, and discussions are welcome.  
This project focuses on clarity, logical analysis, and real-world business understanding.
