# 📊 Customer Shopping Behavior Analysis

## Overview

This project analyzes 3,900 customer transactions to understand spending behavior, customer segments, and revenue drivers.

The goal was simple: turn raw transactional data into clear business insights using a structured analytics workflow — from data cleaning in Python to SQL-based analysis and an interactive Power BI dashboard.

---

## 📂 Dataset

- 3,900 records | 18 features  
- Customer demographics (Age, Gender, Location, Subscription Status)  
- Purchase details (Category, Item, Purchase Amount, Season, etc.)  
- Behavioral metrics (Discount usage, Review Rating, Shipping Type, Purchase Frequency)

---

## 🧹 Data Preparation

- Handled 37 missing values in `review_rating`  
- Standardized column names  
- Removed redundant field (`promo_code_used`)  
- Created derived features such as `age_group`  
- Segmented customers into **New, Returning, and Loyal**

---

## 🛠 Tools & Technologies

- **Python (Pandas, NumPy)** – Data cleaning, EDA, feature engineering  
- **PostgreSQL** – Business analysis using SQL  
- **Power BI** – Interactive dashboard & KPI reporting  

---

## ❓ Business Questions Solved

Using SQL, the following key questions were answered:

- Which gender generates more revenue?  
- Do subscribers spend more than non-subscribers?  
- Which products have the highest ratings?  
- Does shipping type impact purchase value?  
- Which products depend heavily on discounts?  
- Which age groups contribute the most revenue?  
- Are repeat buyers more likely to subscribe?  

---

## 📊 Dashboard Highlights

The Power BI dashboard presents:

- 3.9K total customers  
- ~$60 average purchase value  
- 3.75 average review rating  
- Revenue by category  
- Revenue by age group  
- Subscription distribution (~27% subscribers, ~73% non-subscribers)  
- Customer segmentation insights  

Interactive filters allow analysis by Gender, Category, Subscription Status, and Shipping Type.

---

## 🔎 Key Insights & Outcomes

After analyzing the data, several clear patterns emerged:

- The customer base is predominantly **male (~68%)**, compared to ~32% female customers. Revenue difference is largely driven by customer volume rather than spending gap.  

- Only **~27% of customers are subscribers**, but this segment shows stronger and more stable revenue contribution — highlighting an opportunity to improve subscription conversion.  

- The average purchase value is around **$60**, indicating consistent mid-range spending behavior.  

- **Clothing is the top revenue-generating category**, significantly outperforming other categories.  

- **Young Adults contribute the highest share of revenue**, making them a key target segment.  

- Some products show high dependency on discounts, suggesting room to optimize pricing strategies while protecting margins.  

- Loyal and repeat customers contribute a meaningful share of total revenue, reinforcing the importance of retention strategies.  

---

## 💡 Business Recommendations

- Improve subscription conversion through targeted benefits  
- Focus marketing efforts on high-performing categories like Clothing  
- Strengthen loyalty programs to retain repeat customers  
- Explore targeted campaigns to expand the female customer base  
- Optimize discount strategies to balance sales growth and profitability  

---

## ▶️ How to Run

1. Clean and preprocess data using Python  
2. Load cleaned dataset into PostgreSQL  
3. Execute SQL queries for business analysis  
4. Connect Power BI to database or CSV and build dashboard  

---

## 🚀 Skills Demonstrated

✔ Data Cleaning & Feature Engineering  
✔ Exploratory Data Analysis  
✔ SQL Business Querying  
✔ Customer Segmentation  
✔ Dashboard Development  
✔ Translating data into actionable business insights  


