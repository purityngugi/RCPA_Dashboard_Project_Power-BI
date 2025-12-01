
# 🎯 Power BI RCPA Dashboard Project
### 🚀 Project Overview

This project involved creating a dynamic Power BI dashboard based on Retail Chemist Prescription Audit (RCPA) data. The aim was to implement a full ETL process, establish meaningful relationships between datasets, and provide actionable insights into:
- Doctor prescription performance
- Doctor conversion trends
- Brand competition across regions

### 📊 Dataset Summary

The project utilized the following datasets:

- RCPA Reporting Form - Raw prescription audit data captured by doctors
- Product Master - Details about products, including brand and category
- Brand Targets	- Expected prescription volumes per brand
- Expected Transformation - Guidelines for cleaning and structuring the data

## ✨ Key Contributions
### 🔄 Data Preparation & ETL
- Cleaned and transformed raw RCPA and competitor data following the Expected Transformation guide.
- Integrated with the Product Master dataset and aggregated prescription volumes.
- Generated RCPA Data and Competitor RCPA Data tables, ready for analysis.

### 🗂️ Data Modeling
- Established relationships between RCPA Data, Competitor Data, Product Master, and Brand Targets.
- Configured correct cardinality and cross-filter directions to ensure precise aggregations and filtering.


### 📈 Dashboard & Visualizations
- Doctor Prescription Performance: Compared actual prescriptions against brand targets by medical rep and region.
- Doctor Conversion Trends: Identified doctors consistently meeting targets over multiple periods.
- Brand Competition by Region: Compared market share of our brands against competitors.

### 🧮 Business Logic with DAX
- Developed custom DAX measures to calculate doctor conversion rates and track prescription trends over time.

### 💡 User Experience
- Designed an interactive and intuitive dashboard enabling stakeholders to drill down into key metrics and uncover growth opportunities.

### 🎨 Visualizations Overview

- Doctor Rx Performance	- Bar and line charts showing prescriptions versus targets
- Doctor Conversion Status - Status indicators highlighting doctors meeting prescription goals
- Brand Competition by Region - Stacked charts comparing our brands with competitors across regions

### 🛠️ How to Use

- Open the Power BI report file (.pbix).
- Use the slicers to filter by Medical Reps, Regions, Doctors, Brands, or Time Periods.
- Explore the dashboard to monitor prescription trends, doctor performance, and brand competition.

### 🧰 Tools & Technologies

- Power BI Desktop
- Power Query Editor for ETL tasks
- DAX for custom calculations and measures
- Excel for initial data exploration