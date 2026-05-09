# 📊 Customer Behavior Analysis Dashboard

<div align="center">

**Unlocking insights from retail data to drive business growth**

</div>

---

## 📌 Project Overview

This project analyzes retail / e-commerce customer transaction data to uncover purchasing behavior, discount effectiveness, subscription impact, product performance, and revenue patterns.  
The workflow includes **data cleaning in Python**, **SQL analysis in MySQL Workbench**, and **interactive visualization in Power BI**.  
The dashboard helps businesses make data-driven decisions to improve revenue, retention, and customer targeting.  

---

## 🎯 Business Problem

How can a retail company understand customer purchasing behavior to increase revenue, improve customer retention, and optimize marketing strategies?

This project focuses on:
- Low customer retention
- Ineffective marketing campaigns
- Product demand analysis
- Payment behavior insights
- Seasonal sales variation
- Customer segmentation

---

## 🗂️ Dataset Information

- **Dataset Type:** Retail / E-commerce
- **Structure:** Structured tabular data
- **Level:** Customer transaction level
- **Purpose:** Customer behavior analysis and business decision-making

### Data Mix
- **Numerical:** Age, Purchase Amount, Previous Purchases
- **Categorical:** Category, Payment Method, Season

---

## 🧾 Data Dictionary

### Customer Information
- Customer ID
- Age
- Gender
- Location
- Subscription Status
- Previous Purchases

### Purchase Details
- Item Purchased
- Category
- Purchase Amount
- Season
- Payment Method

### Product Attributes
- Size
- Color
- Review Rating

### Transaction Details
- Discount Applied
- Shipping Type
- Frequency of Purchases

---

## 🧹 Data Cleaning Process

The dataset was cleaned and prepared before analysis using Python.

### Steps performed:
1. **Data Loading**  
   Imported the dataset into a pandas DataFrame.

2. **Initial Exploration**  
   Checked data structure, data types, summary statistics, and missing values.

3. **Category Correction**  
   Fixed inconsistencies between `Item Purchased` and `Category` using a mapping dictionary.

4. **Missing Value Handling**
   - Filled `Size` based on product category logic
   - Imputed `Review Rating` using product-level logic
   - Replaced missing `Purchase Amount` values with mean
   - Replaced missing `Previous Purchases` with `0`

5. **Duplicate Removal**  
   Removed duplicate rows using `Customer ID`.

6. **Column Standardization**  
   Converted column names into clean, SQL-friendly format.

7. **Export to SQL**  
   Exported the cleaned data to **MySQL Workbench** for further analysis.

---

## 🧠 SQL Analysis

The cleaned data was analyzed in **MySQL Workbench** to answer business questions such as:

- Which category generates the highest revenue?
- Do discounts increase purchase value?
- What is the revenue by gender?
- Which customers spent more even after using discounts?
- Which products have the highest and lowest review ratings?
- Do subscribed customers spend more?
- Which products are most purchased in each category?
- Are repeat buyers more likely to subscribe?
- Which age group contributes the most revenue?

---

## 🔍 Key Insights

- **Electronics** generated the highest revenue among all categories.
- Customers who used **discounts** spent more on average than customers who did not.
- **Subscribed customers** spent more on average than non-subscribers.
- The **51+ age group** contributed the largest share of total revenue.
- **Male customers** contributed the highest revenue among gender groups.
- Products like **Gloves, Sandals, Boots, Hat, and Skirt** had strong customer ratings.
- Products like **Phone, Headphones, Watch, Bag, and Laptop** appeared among the lower-rated items in the analysis.

---

## 📈 Power BI Dashboard Highlights

The Power BI dashboard includes:
- Total customers
- Unique items
- Average review rating
- Average spend
- Total spend
- Revenue by gender
- Revenue by category
- Shipping type analysis
- Revenue by season
- Revenue by age distribution
- Revenue by payment method
- Top 5 items by rating
- Top 5 items by revenue
- Top and bottom locations by revenue

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **MySQL Workbench**
- **Power BI**
- **Power Query**

---

## 🚀 How to Use

1. Open the cleaned dataset in **MySQL Workbench** or **Power BI Desktop**
2. Use filters such as gender, category, subscription status, discount applied, and age group
3. Explore the dashboard visuals and SQL outputs
4. Export the report as PDF if needed

---

## 📌 Key Findings & Takeaways

- **Electronics Lead** — highest revenue-generating category
- **Discounts Work** — discount users spent more on average
- **Subscribers Spend More** — subscribed customers showed higher average spending
- **Age Matters** — the 51+ group contributed the highest revenue share

---

## 🔮 Future Improvements

- Add forecasting for revenue and product demand
- Include customer lifetime value prediction
- Build churn or retention analysis
- Add more drill-through pages in Power BI
- Compare multiple time periods for trend analysis

---

## 👨‍💻 Created By

- **Project Author:** Prabhat Kumar
- **Email:** kumarprabhat94317@gmail.com
- **Role:** Data Analyst / Student

---

## 💬 Feedback

Feel free to suggest improvements, add new visuals, or extend the analysis with deeper customer segmentation.

---

## ⭐ If you like this project

Give it a star and feel free to fork it for your own analysis.
