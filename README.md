# ☕ Coffee Sales Dashboard – End-to-End Excel Analytics Project

This project demonstrates an end-to-end data analytics workflow using **Microsoft Excel**, starting from raw data extraction and transformation to building an **interactive sales dashboard** using Pivot Tables, Pivot Charts, Slicers, and Timelines.

The dashboard provides insights into coffee sales performance across time, countries, customers, and product attributes.

---

## 📊 Project Overview

**Objective:**  
To analyze coffee bean sales data and build a dynamic, interactive Excel dashboard that allows users to explore sales trends and customer behavior efficiently.

**Industry Context:**  
Financial Services / Retail Sales Analytics (Coffee Products)

---

## 🗂 Dataset Description

The project uses three main datasets:

- **Orders Table**
  - Order ID
  - Order Date
  - Customer ID
  - Product ID
  - Quantity
  - Sales (calculated)

- **Customers Table**
  - Customer Name
  - Email
  - Country
  - Loyalty Card Status

- **Products Table**
  - Coffee Type
  - Roast Type
  - Package Size
  - Unit Price
  - Profit

---

## 🛠 Tools & Features Used

- Microsoft Excel
- XLOOKUP
- INDEX & MATCH (dynamic lookup)
- IF statements (data standardization)
- Data formatting (dates, currency, units)
- Excel Tables (structured references)
- Pivot Tables
- Pivot Charts (Line & Bar charts)
- Slicers & Timeline filters
- Dashboard design using Shapes & Formatting

---

## 🔄 Data Processing Steps

1. **Data Gathering**
   - Customer details retrieved using `XLOOKUP`
   - Product details retrieved using dynamic `INDEX + MATCH`

2. **Data Transformation**
   - Created calculated fields (Sales)
   - Converted abbreviations to readable values (Coffee Type, Roast Type)
   - Applied proper date, currency, and unit formatting
   - Removed duplicate records
   - Converted raw data range into an Excel Table for scalability

3. **Analysis**
   - Total Sales over Time by Coffee Type
   - Sales Distribution by Country
   - Top 5 Customers by Total Sales

---

## 📈 Dashboard Features

The interactive dashboard includes:

- 📉 **Line Chart:** Total Sales Over Time (by Coffee Type)
- 🌍 **Bar Chart:** Sales by Country
- 🏆 **Bar Chart:** Top 5 Customers by Sales
- ⏱ **Timeline:** Filter sales by date range
- 🎛 **Slicers:**
  - Roast Type
  - Package Size
  - Loyalty Card Status

All visuals are fully interconnected, enabling dynamic filtering across the dashboard.

---

## 🎯 Key Insights Enabled

- Identify best-performing coffee types over time
- Compare sales performance across countries
- Analyze high-value customers
- Understand the impact of roast type, size, and loyalty programs on sales

---

## 📁 Files in This Repository

- `Coffee_Sales_Dashboard.xlsx` – Complete Excel project with dashboard
- `README.md` – Project documentation

---

## 🚀 How to Use

1. Download the Excel file
2. Open in Microsoft Excel (Excel 365 recommended)
3. Navigate to the **Dashboard** sheet
4. Use slicers and timeline to interact with the data

---

## 💡 Future Enhancements

- Add profit-based analysis
- Introduce KPI cards (Total Sales, Avg Order Value, Profit Margin)
- Automate data refresh using Power Query
- Export insights to Power BI

---

