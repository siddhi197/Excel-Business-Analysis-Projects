# 📊 Excel Business Analysis Projects

This repository is a centralized portfolio showcasing **business analysis projects built using Microsoft Excel**.  
Each project demonstrates how raw data can be cleaned, analyzed, and transformed into **actionable business insights** that support informed decision-making.

---

## 📑 Table of Contents

- [Projects](#projects)
  - [Bike Sales Dashboard](#bike-sales-dashboard)
  - [Retail Sales and Customer Insights Analysis](#2-retail-sales-and-customer-insights-analysis)

---

## 📁 Projects

---

## 1. Bike Sales Dashboard

<img width="883" height="643" alt="Bike Sales Dashboard" src="https://github.com/user-attachments/assets/dbd5fe5c-8f4d-46a2-82d5-e6b80244f78f" />

### 📌 Project Overview
This project analyzes bike sales data to understand how **customer demographics, income levels, and commute distance** influence purchasing behavior.  
The goal is to identify **key customer segments** and generate insights that support **data-driven marketing and sales decisions**.

The interactive dashboard allows users to explore trends using filters such as **region, marital status, and education level**.

---

### 🧹 Data Cleaning & Preparation
Before analysis, the dataset was cleaned and standardized to ensure consistency and accuracy:

- Standardized gender values (`M`, `F`) to **Male** and **Female**
- Standardized marital status values to **Married** and **Single**
- Created **Age Brackets** for demographic segmentation:
  - **Adolescent:** Age < 31  
  - **Middle Age:** Age 31–53  
  - **Old:** Age 54+  


**Excel formula used to create age brackets:**
```excel
=IF(L2 < 31, "Adolescent", IF(L2 < 54, "Middle Age", "Old"))
```

### 📊 Key Insights from the Dashboard

#### 1️⃣ Income & Purchase Behavior
- Customers who purchased bikes (**Yes**) have a higher average income than those who did not.
- Male customers show a higher average income per purchase compared to female customers.

**Business Insight:**  
Higher-income customers are more likely to purchase bikes. Marketing strategies focused on professionals and higher-income households could improve conversion rates and overall sales performance.

---

#### 2️⃣ Customer Age Bracket Analysis
- Middle-aged customers represent the largest group of bike purchasers.
- Adolescent and older age groups show lower purchase counts.

**Business Insight:**  
Middle-aged customers are the most engaged and valuable segment. Tailored promotions and targeted messaging for this group could maximize sales impact.

---

#### 3️⃣ Commute Distance & Buying Patterns
- Customers with short commute distances (**0–1 miles**) show the highest number of bike purchases.
- Purchase likelihood decreases as commute distance increases, particularly beyond **10 miles**.

**Business Insight:**  
Bikes are most appealing to short-distance commuters. Marketing campaigns emphasizing convenience, fitness, and short daily commutes may increase customer engagement and sales.

---

#### 4️⃣ Demographic & Regional Filtering
- Filters for **region, marital status, and education level** reveal variations in purchasing behavior.
- These variations highlight the importance of demographic-based segmentation.

**Business Insight:**  
Region-specific and demographic-focused marketing strategies can help align products and messaging with customer needs.

---

### 📈 Conclusion
This dashboard demonstrates how sales and customer data can be transformed into **actionable insights** using data cleaning, segmentation, and visualization techniques.  
The analysis supports **data-driven decision-making** by identifying high-value customer segments and opportunities to optimize marketing strategies.

---


## 2. Retail Sales and Customer Insights Analysis

![Retail sales dashboard showing revenue trends, product categories, and customer demographics](https://github.com/user-attachments/assets/a27b1446-544c-4d48-9d48-c571c65ad969)

---

### 📌 Project Overview

**Objective**  
Analyze retail sales data to identify revenue drivers, customer purchasing patterns, and opportunities to improve sales performance and customer experience.

**Tools Used**
- Microsoft Excel
- Pivot Tables
- Charts and Dashboards
- Data Cleaning and Aggregation

**Key Focus Areas**
- Product category performance
- Monthly sales trends
- Customer demographics (age and gender)

---

### Business Questions and Findings

### 1. Which product categories generate the highest total sales?
Electronics is the highest revenue-generating category.  
This suggests that prioritizing inventory availability and promotions in Electronics could significantly impact overall revenue.

---

### 2. How do sales vary by month?
Sales exhibit significant seasonal fluctuations:
The Peak: May is the strongest month by far, reaching $53,150.
Secondary Peaks: October ($46,580) and December ($44,690) also show strong performance, likely due to autumn shopping and the holiday season.
The Low Point: September is the weakest month of the year ($23,620), representing a sharp drop-off after the summer.

---

### 3. Are there differences in purchasing behavior by gender?
Female customers contribute a slightly higher share of total revenue compared to male customers.  
This insight can support more targeted marketing strategies and product positioning.

---

### 4. Which age groups contribute the most to revenue?
The 50+ age group generates the highest revenue at $52,965.  
While revenue remains relatively consistent across the 20–40 age range (approximately $48,000–$49,000), customers aged 40 and above represent the most valuable segments.

---

### 5. What insights can improve sales or customer experience?

  A. Seasonal Performance
  - Insight: May is the highest-performing month, while September has the lowest sales.
  - Action: Replicate strategies used in May and introduce targeted promotions such as back-to-business or end-of-summer campaigns.

  B. High-Value Customers (Age 50+)
  - Insight: Customers aged 50+ are the highest spenders.
  - Action: Tailor marketing efforts, loyalty programs, and premium offerings to increase retention and lifetime value.

  C. Category Cross-Selling Opportunities
  - Insight: Electronics and Clothing are the two top-performing categories.
  - Action: Test bundled promotions such as wearable technology paired with fitness apparel.

  D. Gender-Neutral Marketing
  - Insight: Spending is nearly evenly split between genders.
  - Action: Focus on interest-based segmentation rather than gender-specific messaging.

---

### Skills Demonstrated

- Data cleaning and preparation
- Pivot table analysis
- Dashboard creation and visualization
- Trend analysis
- Customer segmentation
- Business insight generation

---

