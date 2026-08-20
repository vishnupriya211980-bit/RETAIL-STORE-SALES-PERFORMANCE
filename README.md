# RETAIL-STORE-SALES-PERFORMANCE
Retail Store Sales Data Analysis

📊 Project Overview

This project focuses on analyzing Retail Store Sales Data to understand sales performance, customer activity, spending, discounts, and profitability.

The project includes data cleaning using Python, data analysis using Excel, and interactive dashboard creation using Power BI.

🎯 Objectives

- Clean and prepare raw retail sales data.
- Handle missing and inconsistent data.
- Calculate total spending, discounts, and net profit.
- Analyze sales and profit by category, item, location, and month.
- Understand customer purchasing patterns.
- Create an interactive Power BI dashboard.
- Generate meaningful business insights from the data.

🛠️ Tools & Technologies

- Python
  - Pandas
  - Data cleaning and transformation
- Excel / LibreOffice Calc
  - Data validation
  - Calculations and summaries
- Power BI
  - Data visualization
  - Interactive dashboard
  - Filters and slicers
  - KPI cards
- GitHub
  - Project documentation and version control

🔄 Project Workflow

Raw Data
   ↓
Data Cleaning
   ↓
Data Validation
   ↓
Data Transformation
   ↓
Data Analysis
   ↓
Power BI Dashboard
   ↓
Business Insights

🧹 Data Cleaning

Python and Pandas were used to prepare the dataset for analysis.

The cleaning process included:

- Identifying missing values.
- Removing unnecessary records.
- Checking important fields such as Quantity and Total Spent.
- Preparing the cleaned dataset for further analysis.
- Exporting the cleaned data into Excel format.

Example Python operations used:

import pandas as pd

df = pd.read_excel("clean_data.xlsx")

df = df.dropna(subset=["Quantity", "Total Spent"])

df.to_excel("cleaned_data.xlsx", index=False)

📈 Analysis Performed

The project analyzes:

- Total Sales
- Total Spent Amount
- Net Profit
- Total Quantity
- Customer Count
- Average Discount
- Sales by Category
- Profit by Category
- Profit by Month
- Sales by Location
- Customer-level spending
- Item-level performance

📊 Power BI Dashboard
<img width="898" height="507" alt="Screenshot 2026-08-20 150340" src="https://github.com/user-attachments/assets/ce957a4e-22bb-4284-a682-820406e461c0" />
<img width="876" height="427" alt="Screenshot 2026-08-20 150124" src="https://github.com/user-attachments/assets/70968581-9e05-4793-88a1-65079747c5fa" />
<img width="876" height="427" alt="Screenshot 2026-08-20 150124" src="https://github.com/user-attachments/assets/19c953fe-062b-435e-b7db-1f88c0bf0e0e" />



The Power BI dashboard contains KPI cards and interactive visualizations.

Key KPIs

- Net Profit: 320.98K
- Total Net Sales: 1.55M
- Customers: 25
- Total Orders: 12K
- Total Quantity: 66K
- Average Discount: 0.03

Dashboard Visualizations

- Sales by Category
- Profit by Location
- Net Profit by Category
- Discount Amount vs Spent Amount
- Profit by Month
- Sales by Location and Customer ID
- Category and Item-level summary tables

Interactive Filters

Users can filter the dashboard using:

- Year
- Month
- Location
- Payment Method
- Date/Month

💡 Key Insights

The dashboard helps identify:

- Which categories generate higher sales.
- Which categories contribute more to profit.
- Monthly changes in profitability.
- Customer purchasing behavior.
- Location-wise sales performance.
- Items with higher spending and profit.
- The relationship between discounts and spending.

📁 Project Structure

Retail-Store-Sales-Analysis/
│
├── data/
│   ├── raw_data.xlsx
│   └── cleaned_data.xlsx
│
├── python/
│   └── data_cleaning.py
│
├── powerbi/
│   └── retail_sales_dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── README.md

🚀 Project Outcome

This project demonstrates the complete data analytics workflow from raw data to business insights.

It helped apply practical skills in:

Python → Data Cleaning → Excel → Data Analysis → Power BI → Data Visualization → Business Insights

👩‍💻 Skills Demonstrated

- Data Cleaning
- Data Analysis
- Python Pandas
- Excel
- Power BI
- Dashboard Development
- Data Visualization
- Business Intelligence
- Analytical Thinking

📌 Conclusion

The Retail Store Sales Data Analysis project provides a clear view of sales, spending, discounts, customers, and profitability. The interactive Power BI dashboard makes it easier to explore the data and identify useful business insights for decision-making.
