# 🏦 Bank Customer Churn Analysis & Dashboard
![Link] ( https://www.kaggle.com/datasets/sharanharsoor/bank-customers-and-their-churn-behavior)
![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)
![Data](https://img.shields.io/badge/Dataset-10%2C000%20Customers-blue)

## 📌 Executive Summary
This project analyzes customer churn for a retail bank using **Excel only**. The analysis reveals a **20.4% churn rate** (2,037 out of 10,000 customers). The strongest predictors are **geography, number of products, gender, and age**. Notably, **high-value customers are churning** — the average balance of churned customers ($91,108.54) is higher than the overall average ($76,485.89). Based on these findings, I recommend targeted retention campaigns for **German customers**, **senior professionals (56+ years)**, **female customers**, and a review of **multi‑product offerings** (3+ products show extreme churn). Implementing these could retain millions in customer balances.

## 🎯 Business Problem
Customer churn directly impacts revenue and increases acquisition costs. Understanding *who* churns and *why* allows the bank to take proactive retention actions. This project answers:  
- What is the overall churn rate?  
- Which customer segments are most at risk?  
- What actionable steps can reduce churn?

## 📊 Dataset
- **Source:** Bank Customer Churn Dataset (public)  
- **Records:** 10,000 customers  
- **Key Features:** Credit Score, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary  
- **Target:** `Exited` (1 = churned, 0 = retained)  
- **Irrelevant columns:** RowNumber, CustomerId, Surname

## 🛠 Tools & Techniques
- **Microsoft Excel:** Data cleaning, PivotTables, PivotCharts, Slicers, Dashboard design  
- **Techniques:** Exploratory Data Analysis (EDA), segmentation, cohort analysis  
- **Design:** KPI cards, interactive slicers, conditional formatting

## 🔍 Methodology
1. **Data Cleaning:** Removed duplicates, handled missing values, standardized categories.  
2. **Feature Engineering:** Created age bands, balance segments, and product groups.  
3. **Analysis:** Used PivotTables to compare churn across demographics, geography, and product usage.  
4. **Dashboard:** Built an interactive Excel dashboard with KPI cards, charts, and slicers for dynamic filtering.

## 📈 Key Findings & Visuals

| Segment | Churn Rate | Insight |
|--------|------------|---------|
| **Overall** | **20.4%** (2,037) | 1 in 5 customers leave |
| **Germany** | **32.44%** | Double the rate of France (16.15%) and Spain (16.67%) |
| **3 Products** | **82.71%** | Extreme churn; 100% of 4‑product customers leave |
| **Female** | **25.07%** | vs Male 16.46% |
| **Senior Professionals (56+)** | **50.57%** | Highest age‑group churn; Retired/Senior 36.75% |
| **Inactive Members** | **26.85%** | vs Active 14.27% |
| **High‑Value Customers** | Avg balance **$91,108.54** | Churned customers have a higher average balance than the overall average ($76,485.89) |

![Dashboard Screenshot](images/dashboard.png)  
*Interactive Excel dashboard with slicers for Geography, Gender, Age, and No. Of Products.*

## 💡 Recommendations
1. **Investigate Germany immediately:** Conduct local market research, compare competitor pricing/services, and improve regional offerings. Germany’s 32.44% churn is double that of other countries.  
2. **Target senior professionals (56+):** Offer retirement‑friendly products, wealth management, and loyalty perks to reduce their 50.57% churn.  
3. **Address female churn:** Tailor products and communication to female customers (25.07% vs 16.46% male).  
4. **Review multi‑product strategy:** Customers with 3+ products churn at 82–100%. Simplify bundles, re‑evaluate pricing, or add value to retain them.  
5. **Re‑engage inactive members:** Launch email/SMS campaigns with incentives to increase activity (26.85% churn vs 14.27% for active).  
6. **Protect high‑value customers:** Since churned customers have above‑average balances, prioritise retention offers for affluent segments.

## 🚀 Business Impact (Estimated)
Assuming a **5% relative reduction in churn** (retaining 5% of current churners), the bank could retain approximately **102 customers**. Based on the average balance of churned customers (**$91,108.54**), this represents about **$9.29 million in retained balances**.  
*Assumption: average balance of retained customers equals the average balance of current churned customers.*

## 🔎 Assumptions & Next Steps
Based on the data, I formed these hypotheses:
- German customers may be leaving due to better competitor services, pricing, or lack of local relevance.
- Older customers may churn due to retirement or reduced need for banking products.
- Female customers may have different service expectations.

**Next step:** Collect qualitative feedback (surveys, exit interviews) from German and senior customers to validate these assumptions.

## 📂 Repository Structure
