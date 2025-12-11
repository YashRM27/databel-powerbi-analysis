# Databel Telecom – Customer Churn Analysis (Power BI)

## Introduction  
Subscription-based businesses consistently face one strategic challenge: minimizing customer churn. In this project, I analyze a real-world telecom-style dataset from **Databel**, a fictional telecommunications provider. The objective was not only to measure churn but also to understand the underlying factors driving customer attrition and identify actionable opportunities to improve retention.

This case study involved end-to-end Power BI development: data cleaning, modeling, DAX measures, and the creation of clear and interactive dashboard pages. The final report highlights customer behavior patterns, service usage, demographics, contract types, and performance across states—helping stakeholders interpret churn behavior and develop targeted retention strategies.

---

## Project Objectives  
- Quantify Databel’s customer churn rate  
- Identify customer segments contributing most to churn  
- Analyze drivers such as demographics, contract types, service usage, and monthly charges  
- Build interactive Power BI dashboards for business storytelling  
- Deliver actionable recommendations to reduce churn

---

## Dataset  
Source: **Databel Telecom (Fictional Dataset)**  
Key dataset fields include:  
- Customer demographics (age, gender, state)  
- Subscription details (contract type, tenure, total charges)  
- Service usage metrics  
- Churn status (Yes/No)

A cleaned dataset is available in the `/data` folder.

---

## Power BI Workflow  

### 1. Data Transformation  
Executed in **Power Query**:  
- Removed duplicates and handled null values  
- Standardized column naming  
- Created calculated fields (age groups, tenure groups, etc.)

### 2. Data Modeling  
- Configured a star-schema model  
- Designed fact and dimension tables  
- Created relationships based on customer and subscription fields

### 3. Key DAX Measures  
Examples include:  
- `Churn Rate`  
- `Total Customers`  
- `Active Customers`  
- `Average Monthly Charges`  
- `Churn by Contract Type`  
- `Customer Tenure Category`

---

## Dashboard Overview  
This Power BI report consists of multiple pages:

1. **Executive Summary** – KPIs, churn insights, revenue overview  
2. **Customer Demographics** – Age, gender, tenure, churn segmentation  
3. **Geographical View** – State-level churn comparisons  
4. **Service Usage Analysis** – Product adoption, usage vs. churn  
5. **Contract & Billing Insights** – Impact of charges, contract duration, account age  

Screenshots can be found in the `/dashboard` folder.

---

## Folder Structure  
```
Databel-PowerBI-Analysis/
│
├── data/
│     └── Databel - Data.csv
│
├── dashboard/
│     ├── img1_Churn_Demographics.png
│     ├── img2 group and categories.png
│     ├── img3 unlimited plan.png
│     ├── img4 international calls.png
│     └── img5 contract type.png
│     └── img6 Overview.png
│     └── img7 Age Groups.png
│     └── img8 payment and contract.png
│     └── img9 extra charges.png
│     └── img10 Insights.png
│
├── pbix/
│     └── Databel_Report.pbix
│
└── README.md
```
