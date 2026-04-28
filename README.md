# FoodHub Order Analysis Project

This repository contains a full exploratory data analysis (EDA) and business insights report for the **FoodHub Low‑Code Project**, completed as part of the **MIT Applied AI & Data Science Program**. The project analyzes customer behavior, restaurant performance, operational efficiency, and revenue patterns using a dataset of **1,898 food delivery orders** from New York City.

## 📁 Project Overview

FoodHub is a food‑delivery aggregator operating in a high‑demand, high‑density market. This analysis investigates:

- Customer ordering patterns
- Cuisine preferences
- Delivery and preparation time performance
- Rating behavior and missing‑rating patterns
- Restaurant‑level revenue and operational metrics

The goal is to identify **actionable insights** to improve customer satisfaction, operational efficiency, and revenue.

## 🔍 Key Objectives

- Perform structured **univariate and multivariate EDA**
- Identify **top‑performing restaurants** and cuisine trends
- Analyze **delivery time vs. rating** relationships
- Examine **weekday vs. weekend demand**
- Provide **data‑driven recommendations** for FoodHub’s business strategy

## 📈 Highlights & Findings

**Customer & Order Behavior**
- Weekend orders dominate the dataset, nearly **2× higher** than weekday orders.
- American, Japanese, and Italian cuisines account for the majority of orders.
- Most orders fall within the **$10–$15** cost range.

**Operational Insights**
- Average delivery time: **24 minutes**
- Weekend deliveries are faster (**22 minutes**) than weekday deliveries (**28 minutes**)
- About **1 in 10** orders exceed 60 minutes, indicating operational bottlenecks.

**Ratings & Satisfaction**
- **736 ratings** are “Not given,” limiting customer‑satisfaction visibility.
- Ratings of **5** dominate, suggesting strong positive bias among customers who do rate.
- Ratings drop when delivery times exceed **~25 minutes**.

**Revenue Insights**
- A small group of restaurants (e.g., Shake Shack, The Meatball Shop) generates a disproportionate share of revenue.
- Most orders do not exceed **$20**, indicating opportunities for upselling and bundling.

## 🧠 Recommendations
- Launch **loyalty programs** and **upsell bundles** to increase average order value.
- Promote top‑performing restaurants and high‑demand cuisines, especially on weekends.
- Implement **in‑app rating prompts** to reduce “Not given” ratings.
- Improve weekday staffing and optimize delivery routing to reduce delays.
- Introduce **premium subscription tiers** and targeted marketing campaigns.

## 🗂 Project Structure
```plaintext
foodhub-order-analysis/
│
├── GBonilla_FoodHub_Order_Analysis_Low_Code_Methodology_and_Workflow.pdf     # Detailed methodology + workflow document
├── GBonilla_FoodHub_Order_Analysis_Low_Code_Report.pdf     # Full project report
├── GBonilla_FoodHub_Order_Analysis_Low_Code.ipynb   # Solution deliverable
│
└── README.md                                # Project overview and documentation
```

## 🛠 Tools & Technologies
- **Python** (pandas, NumPy, matplotlib, seaborn)
- **Google Colab**
- **Statistical analysis & visualization techniques**
- **Low‑code analytical workflows**

## 📄 Project Report
The full project report (`GBonilla FoodHub Order Analysis Low Code Report.pdf`) includes:
- **Executive Summary**
- **Business Problem and Solution Approach**
- **Data Overview**
- **Exploratory Data Analysis (Univariate & Bivariate)**
  - Univariate Analysis
  - Univariate Analysis - Business Application Insights
  - Bivariate Analysis
  - Bivariate Analysis - Business Application Insights
- **Conclusions and Recommendations**
- **Appendix** (Code Snippets)
