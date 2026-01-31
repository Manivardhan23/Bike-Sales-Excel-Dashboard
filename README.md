# Bike Sales Dashboard (Excel Project)

## 📌 Project Overview
This project analyzes a dataset of bike buyers to identify key demographics and purchasing trends. The goal was to transform raw sales data into an interactive dashboard that answers the question: **"Who is the ideal customer for a new bike?"**

## 📂 Dataset Description
The dataset includes details on customer demographics, income, education, and commute distance.
* **Source:** Excel Data Analysis Tutorial (Alex The Analyst)
* **File Structure:**
    * `bike_buyers`: The original raw dataset.
    * `working_sheet`: The cleaned dataset used for analysis.
    * `pivot_table`: The pivot tables generated to summarize the data.
    * `Dashboard`: The final interactive visual interface.

## 🛠️ Process & Methodology
### 1. Data Cleaning
Before analysis, the data required significant preparation to ensure accuracy:
* **Removed Duplicates:** Identified and deleted duplicate records to prevent skewed results.
* **Standardized Values:** Corrected inconsistencies in the `Marital Status` (M/F → Married/Single) and `Gender` (M/F → Male/Female) columns for better readability.
* **Currency Formatting:** Applied currency formatting to the `Income` column.

### 2. Feature Engineering (New Metrics)
* **Age Brackets:** Created a new conditional column `Age Group` to categorize customers into three segments:
    * **Adolescent:** (<31)
  
    * **Middle Aged:** (31 - 54)
    * **Old:** (55+)
    * *Reasoning:* analyzing purchasing habits by generation is more actionable than individual ages.

### 3. Analysis & Visualization
Used Pivot Tables to aggregate data and created the following charts for the dashboard:
* **Average Income per Purchase:** Compared income levels between male and female buyers.
* **Customer Age Group:** Visualized which age bracket purchases the most bikes.
* **Customer Commute:** Analyzed the relationship between commute distance and the likelihood of buying a bike.

## 📊 Key Insights
* **Middle-Aged Customers are King:** The "Middle Aged" group accounts for the vast majority of bike purchases, significantly outperforming adolescents and older customers.
* **Short Commutes = More Sales:** Customers with a commute of **0-1 Miles** are the most likely to purchase a bike. As commute distance increases, purchase likelihood generally decreases.
* **Income Disparity:** Male customers generally have a slightly higher average income than female customers across both "Yes" and "No" purchase categories.

## 🧰 Tools Used
* **Microsoft Excel:**
    * Pivot Tables
    * Slicers (for interactive filtering)
    * Data Cleaning & Formulas (Nested IFs)
    * Dashboard Design

---
*Created by [Manivardhan23]*
