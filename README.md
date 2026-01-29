#  E-Commerce Sales Analytics Project

##  Project Overview
The **E-Commerce Sales Analytics Project** analyzes customer shopping behavior for a retail business to uncover trends that drive revenue growth and customer loyalty.  
This project follows a complete data analytics workflow using **Python for data preparation**, **MySQL for analysis**, and **Power BI for visualization**, delivering actionable business insights for decision-makers.

---

##  Business Objectives
The core business question addressed in this project is:

> **How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?**

Key objectives include:
- Analyzing purchasing patterns across demographics and product categories  
- Understanding the impact of discounts, ratings, shipping, and payment methods  
- Evaluating customer loyalty through subscription behavior  
- Identifying high-performing products and revenue drivers  

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|--------|
| **Python (Pandas, NumPy)** | Data cleaning, transformation, and feature engineering |
| **MySQL** | Data storage and complex SQL analysis |
| **Power BI** | Interactive dashboards and KPI visualization |
| **SQLAlchemy** | Python–MySQL database integration |
| **GitHub** | Version control and project documentation |

---

##  Data Preparation Workflow (Python)

The raw dataset was cleaned and transformed to ensure accuracy and consistency before analysis.

### Missing Value Imputation
- Null values in the `review_rating` column were filled using the **median rating per product category**.

### Column Standardization
- Column names were converted to **snake_case** for SQL compatibility.

### Feature Engineering
- **Age Groups** created by binning customer ages into:
  - Young Adult  
  - Adult  
  - Middle-aged  
  - Senior  

- **Purchase Frequency Mapping**
  - Text-based frequency values were converted into numeric form in `purchase_frequency_days`.

### Data Consistency Checks
- Redundant columns such as `promo_code_used` were removed after confirming overlap with `discount_applied`.

### Database Integration
- Cleaned data was loaded into **MySQL** using **SQLAlchemy**.

---

##  SQL Analysis & Key Insights

SQL queries were used to answer critical business questions:

- **Revenue by Gender:**  
  Compared total spending across male and female customers.

- **Customer Segmentation:**  
  - New Customers: 1 purchase  
  - Returning Customers: 2–10 purchases  
  - Loyal Customers: 10+ purchases  

- **Subscription Impact:**  
  Non-subscribers generate higher total revenue, while subscribers show higher purchase frequency.

- **Product Performance:**  
  - Top-selling categories: Clothing and Accessories  
  - Top-rated products: Gloves and Sandals  

- **Shipping & Discounts:**  
  Compared average spend between Standard and Express shipping options.

---

##  Visualization (Power BI)

An interactive **Customer Behavior Dashboard** was created to communicate insights effectively.

### Key KPIs
- **Total Customers:** 3.9K  
- **Average Purchase Amount:** $59.76  
- **Average Review Rating:** 3.75  

### Dashboard Features
- Revenue trends by product category and age group  
- Customer distribution by gender and subscription status  
- Purchase behavior comparison between subscribers and non-subscribers  

---

##  Key Recommendations

- **Targeted Marketing:**  
  Focus on high-revenue categories like Clothing and Accessories.

- **Subscription Conversion:**  
  Introduce personalized offers to convert the 73% non-subscriber customer base.

- **Product Quality Improvement:**  
  Use lower-rated product insights to trigger quality control reviews.

---
**Satyam Pandey**  
**B.Tech – Electronics & Communication Engineering**
