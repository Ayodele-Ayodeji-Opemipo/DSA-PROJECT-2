# DSA-PROJECT-2
# Palmora Group HR Gender Analysis

##  Company Background
Palmora Group, a manufacturing company in Nigeria, recently came under public scrutiny over gender inequality across its operations. The CHRO, Mr. Yunus Shofoluwe, in response to media backlash and regulatory pressure, initiated a gender-focused HR analysis to uncover and resolve these internal issues.
This project was executed by a Junior HR Analytics consultant to:

* Detect and analyze gender disparities in staffing, pay, and performance
* Provide actionable insights to improve diversity, equity, and inclusion (DEI)
* Aid compliance with new wage regulations

##  Dataset Overview

The main dataset (`Palmoria Group emp-data.11.xlsx`) includes employee-level information such as:

* Gender, Region, Department
* Salary, Performance Rating, and Employment Status

## Data Cleaning Steps:

* Employees with **missing salaries** were excluded (no longer with the company)
* Employees with **“NULL” departments** were filtered out
* Employees with **undisclosed gender** were grouped under a general **"Others"** category

A second dataset (bonus rules) was also used to compute bonus pay based on employee performance ratings.

##  Key Analytical Tasks

### 1. Gender Distribution

* Organization-wide gender balance
* Gender breakdown by **region** and **department**

### 2. Performance Ratings

* Comparison of average performance ratings by gender
* Visual analysis of rating patterns

### 3. Salary Structure & Gender Pay Gap

* Gender-based salary comparison
* Departmental and regional analysis of pay disparities
* Identification of departments with potential **gender-based salary gaps**

### 4. Regulatory Salary Compliance

* Regulatory threshold: **Minimum \$90,000 annual pay**
* Detection of employees **below the threshold**
* Salary **distribution grouped in \$10,000 bands**, visualized per region

### 5. Bonus Allocation (Using Performance Rating)

* Bonus computation using predefined rules
* Total compensation (salary + bonus)
* Aggregated payouts by **region** and **company-wide**

---

## Visualizations & Dashboard

All analyses were visualized using:

* **Bar Charts** (Gender distribution, Pay bands, Bonus by region)
* **Pie Charts** (Gender share, Regulatory compliance)
* **Pivot Tables** (Departmental and regional summaries)
* **Conditional Formatting** (Salary gap indicators)

The final **Excel dashboard** includes:

* Gender equity KPIs
* Salary band filters
* Bonus allocation summary
* Regional performance comparisons

---

## Key Insights

* A **significant gender imbalance** exists in some regions and departments
* **Gender pay gaps** were observed in key departments like Production and Admin
* About **69% of employees** earn below the \$90,000 regulatory threshold (precise % based on data)
* **Male employees** generally have higher average salaries despite similar performance ratings
* Regions like **Kaduna** have the **largest bonus payouts**

---

##  Files Included

* `Palmoria Group emp-data.11.xlsx`: Raw and cleaned data, plus analysis sheets

---

## Project Status

Completed

##  Author

### Ayodele Ayodeji Opemipo
HR Analytics Consultant – Palmora Project
