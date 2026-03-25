# 📊 Customer Behavior Analysis Dashboard (Power BI + SQL + Python)

## 📌 Project Overview

This project focuses on analyzing customer purchasing behavior using data analytics and visualization techniques. The goal is to uncover meaningful insights related to revenue, customer segments, and purchasing patterns to support data-driven decision-making.

The project follows an **end-to-end workflow** including data cleaning (Python), data querying (SQL), and dashboard creation (Power BI).

---

## 🎯 Objectives

* Analyze customer purchasing trends across product categories
* Identify top revenue-generating segments
* Understand customer behavior based on subscription status
* Evaluate shipping preferences
* Analyze revenue distribution by age group and location

---

## 🧾 Dataset Description

The dataset contains transactional customer data with the following fields:

* Customer ID
* Gender
* Age Group
* Product Category
* Quantity
* Price
* Payment Method
* Shipping Type
* Subscription Status
* Location

---

## 📊 Key Performance Indicators (KPIs)

* 👥 Total Customers: **3.9K**
* 💰 Total Revenue: **233K**
* ⭐ Average Rating: **3.75**
* 🧾 Average Order Value: **59.76**

---

## 📈 Dashboard Features

* Revenue by Category
* Customers by Subscription Status
* Revenue by Location
* Customers by Shipping Type
* Revenue by Age Group
* Interactive Filters:

  * Gender
  * Category
  * Payment Method

---

## 🐍 Python (Data Cleaning & Analysis)

* Cleaned and preprocessed raw dataset using **Pandas**
* Handled missing values and corrected data types
* Created new feature:

  * **Revenue = Quantity × Price**
* Performed exploratory data analysis (EDA)
* Used **NumPy** for numerical operations

---

## 🗄️ SQL (PostgreSQL – Data Querying)

* Extracted and analyzed data using SQL queries
* Used **GROUP BY** for aggregations (category, location, age group)
* Calculated total revenue:

  ```sql
  SELECT location, SUM(quantity * price) AS revenue
  FROM sales_data
  GROUP BY location;
  ```
* Filtered and transformed data for dashboard usage
* Ensured data consistency and validation

---

## 📊 Power BI (Data Visualization)

* Built an interactive dashboard with key KPIs
* Created calculated measures (Revenue, Average Order Value)
* Used slicers for dynamic filtering
* Designed a clean and user-friendly layout
* Focused on storytelling through visuals

---

## 🧠 Key Insights

* Clothing category generates the highest revenue
* 73% of customers are non-subscribers → growth opportunity
* Top locations contribute a major share of total revenue
* Free and standard shipping are most preferred
* Young Adults are the highest revenue-generating segment

---

## 💡 Business Recommendations

* Focus on high-performing categories like Clothing
* Convert non-subscribers into subscribers through offers
* Target high-revenue locations with personalized campaigns
* Optimize shipping strategies based on customer preferences
* Design marketing campaigns for Young Adults

---

## 📁 Project Structure

```
Customer-Behavior-Analysis/
│
├── 📊 Dashboard.pbix
├── 📄 Customer_Behavior_Analysis_Report.pdf
├── 📷 dashboard_screenshot.png
└── 📜 README.md
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use filters to explore insights

---

## 🙌 Conclusion

This project demonstrates how raw data can be transformed into actionable insights using analytics and visualization tools. It highlights key customer behavior trends and supports better business decision-making.

---

## 📬 Connect With Me

If you found this project interesting or have any suggestions, feel free to connect with me!
