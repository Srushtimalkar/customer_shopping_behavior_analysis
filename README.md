# 🛒 Customer Shopping Behavior Analysis

This project analyzes customer shopping patterns using a dataset of **3,900 transactions** across various product categories. The aim is to uncover insights about **spending behavior, product preferences, subscription impact, age-wise revenue, and customer segmentation** to support business decision-making.  
The analysis was done using **Python (EDA), SQL (business queries), and Power BI (dashboard).**

---

## 📂 Project Workflow

### 🔹 1. Exploratory Data Analysis (Python)
- Loaded and cleaned dataset using Pandas
- Treated missing values in `review_rating`
- Converted columns to `snake_case`
- Engineered features like `age_group` and `purchase_frequency_days`
- Stored cleaned data in PostgreSQL for SQL analysis

### 🔹 2. Business Insights using SQL
Queries focused on the following key business metrics:
- Revenue by gender
- Top 5 highest-rated products
- Effect of discounts on spending
- Standard vs Express shipping comparison
- Subscribers vs non-subscribers revenue
- Customer segmentation (New / Returning / Loyal)
- Top 3 products per category
- Revenue contribution by age group
- Subscription likelihood of repeat buyers

### 🔹 3. Power BI Dashboard
The interactive dashboard visualizes:
- Total customers (3.9K)
- Average purchase amount
- Subscription distribution
- Revenue by category
- Revenue by age group
- Review rating analysis

---

## 📌 Key Insights
- **Subscribed customers spend more on average**
- **18–30 age group contributes the highest revenue**
- **Clothing & accessories dominate sales**
- **Express shipping users tend to spend more**
- **Discounts help engagement but require margin balance**

