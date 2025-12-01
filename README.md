# Marketing Campaign Dashboard – Power BI

This project analyzes and visualizes marketing campaign performance using **Power BI**.  
It helps understand customer behavior, campaign success, and return on investment (ROI).

---

## Objective
To build an interactive dashboard that answers:
- How well did the campaign perform?  
- Which customers responded the most?  
- What is the Click-Through Rate (CTR) and ROI?  

---

## Tools Used
- **Power BI** – for data visualization  
- **Excel / CSV** – for data cleaning  
- **DAX** – for creating measures  

---

## Dataset
**File:** `marketing_data.csv`  
**Source:** Kaggle – Marketing Campaign Dataset  

Contains fields like:  
`Income`, `MntWines`, `MntFruits`, `MntFishProducts`, `MntGoldProds`, `NumWebPurchases`, `Response`, `Complain`, `Education`, `Marital_Status`, `Country`.

---

## DAX Measures
- **Total_Spending** = sum of all product amounts  
- **Average_Income** = average of income  
- **CTR** = web purchases / web visits  
- **Campaign_Response_Rate** = total responses / total customers  
- **Complaint_Rate** = total complaints / total customers  
- **ROI** = (Total_Spending – (Income × 0.1)) / (Income × 0.1)  
- **Web_Purchase_Percentage** = web purchases / total spending  

---

## Dashboard Overview
**Page 1 – Customer Overview**  
Shows key KPIs and customer demographics.  

**Page 2 – Campaign Insights**  
Displays purchase and response patterns.  

**Page 3 – ROI & Deep Analysis**  
Includes ROI by education level and interactive filters.

---

## Key Insights
- Married and graduated customers spend the most.  
- CTR around 15% shows good engagement.  
- ROI ≈ 28%, indicating profit.  
- Complaint rate is low (<5%).  

---

## Author
SANDHOSHIVANY G N
## LinkedIN Profile: https://www.linkedin.com/in/sandhoshivany-g-n-0381b2333?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
