# 🛒 Retail Sales Performance Analysis | Excel, Power Query & Power BI

## 📌 Project Overview

This project focuses on analysing retail sales data to understand business performance, customer purchasing behaviour, product performance, regional trends, discounts, product returns and delivery efficiency.

Using **Microsoft Excel, Power Query and Power BI**, I transformed raw sales data into meaningful business insights through data cleaning, exploratory analysis, data modelling, DAX calculations and interactive dashboards.

The project also applies the four major types of business analytics: **Descriptive, Diagnostic, Predictive and Prescriptive Analysis**.

## 🎯 Project Objectives

- Analyse overall sales and order performance.
- Identify top- and low-performing products, customers and regions.
- Understand the impact of discounts on purchase quantity and order value.
- Analyse delivery time, shipping costs and product return patterns.
- Examine historical sales trends and estimate future sales performance.
- Provide data-driven recommendations to improve business operations.

## 📂 Dataset Information

| Description | Details |
|---|---|
| Dataset | Product Sales by Region |
| Source | [Excelx – Retail Sales Practice Dataset](https://excelx.com/practice-data/sales-retail/) |
| Domain | Retail and Sales Analytics |
| Data Period | January 2023 – June 2025 |
| Total Records | 1,500 |
| Original Attributes | 19 |
| Regions | 5 |
| Stores | 4 |
| Products | 7 |

The dataset contains sales transactions, customer details, product information, store details, discounts, shipping costs, delivery dates and return status.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data inspection, cleaning, calculated columns, PivotTables and descriptive statistics |
| Power Query | Data transformation and preparation |
| Power BI | Data modelling, DAX calculations and interactive dashboards |
| DAX | Calculated columns, measures and time-intelligence analysis |
| GitHub | Project documentation and portfolio presentation |

## 🔄 Project Workflow

### 1. Data Cleaning and Preparation – Excel

- Checked duplicate records and missing values.
- Standardised date, numerical, currency and percentage formats.
- Created a calculated Delivery Time column using Order Date and Delivery Date.
- Applied filters, sorting and conditional formatting.
- Converted the dataset into a structured Excel table.

### 2. Data Transformation – Power Query

- Loaded the cleaned Excel workbook into Power BI.
- Prepared the Sales Fact and dimension tables.
- Checked data types and column consistency.
- Organised the data for analysis.

### 3. Data Modelling – Power BI

Created a **Star Schema** consisting of one fact table and four dimension tables, along with a Date table.

| Table | Purpose |
|---|---|
| Sales Fact | Stores transaction-level sales information |
| Customer Dim | Customer name and customer type |
| Product Dim | Product identification and product name |
| Store Dim | Store identification and location |
| Region Dim | Region and region manager |
| Date Table | Date, year, month and year-month information |

Established one-to-many relationships between the fact table and dimension tables.

### 4. DAX Calculations

Created calculated columns, calculated tables and measures to support business analysis.

**Key calculated columns:**
- Gross Sales
- Discount Amount
- Discount Category
- Return Status
- Delivery Status
- Sales Category
- Shipping Category
- Order Since

**Key measures:**
- Total Sales
- Total Gross Sales
- Total Orders
- Total Quantity
- Total Discount
- Return Rate
- Returned Orders
- Average Order Value
- Average Delivery Days
- Unique Customers
- Total Shipping Cost
- Previous Month Sales
- Month-over-Month Growth
- Sales MTD and YTD
- Same Period Last Year
- Rolling 3-Month Sales

### 5. Dashboard Development

Developed interactive Power BI report pages using KPI cards, charts, tables, matrices and slicers.

**Report pages include:**

1. Retail Sales Performance Overview
2. Sales Time Intelligence Overview
3. Retail Sales Analysis Dashboard 1
4. Retail Sales Analysis Dashboard 2

**Key visualisations:**
- KPI cards for sales, orders, discounts and returns.
- Product-wise and store-wise sales charts.
- Region-wise sales contribution.
- Monthly and yearly sales trends.
- Discount impact analysis.
- Delivery time and return rate analysis.
- Salesperson performance comparison.
- Store shipping cost and return rate analysis.
- Product sales distribution using a treemap.

**Interactivity:**
- Year and month slicers.
- Region and store filters.
- Product-level filtering.
- Cross-filtering between visuals.

## 📊 Four Types of Business Analysis

### 1. Descriptive Analysis – What Happened?

- Total sales reached **₹4.38 million** from 1,500 orders.
- Tablet, Laptop and Printer were the top-performing products, with approximately ₹684K each.
- North recorded the highest regional sales at approximately ₹968K.
- Store D recorded the highest store sales at approximately ₹1.21 million.
- Wholesale and Retail customers contributed almost equally to total sales.
- The overall return rate was 24.8%.

### 2. Diagnostic Analysis – Why Did It Happen?

- Higher discount levels did not significantly increase average purchase quantity.
- Average order value decreased from ₹3,067 at 0% discount to ₹2,686 at 15% discount.
- North had the slowest average delivery time but the lowest regional return rate.
- Returned and non-returned orders had almost identical average delivery times.

### 3. Predictive Analysis – What Is Likely to Happen?

- Sales increased by approximately 4% from 2023 to 2024.
- January–June 2025 sales were almost equal to the same period in 2024.
- Based on the observed trend, estimated 2025 full-year sales are approximately ₹1.77 million.
- North and East showed positive regional growth, while South and West experienced declines.

### 4. Prescriptive Analysis – What Should Be Done?

Based on the findings, the following business recommendations were identified:

- **Reward:** Recognise Bob and Alice for their strong sales performance.
- **Training:** Provide additional training to Diana and Carlos.
- **Shipping:** Review the South region to identify opportunities to reduce shipping costs.
- **Returns:** Investigate Store B because it recorded the highest return rate.
- **Discount Strategy:** Review discount levels to avoid reducing order value without a meaningful increase in purchase quantity.

## 💡 Key Business Insights

| Area | Key Finding |
|---|---|
| Overall Sales | ₹4.38M |
| Total Orders | 1,500 |
| Return Rate | 24.8% |
| Top Product | Tablet |
| Lowest-Selling Product | Phone |
| Top Region | North |
| Lowest Region | South |
| Top Store | Store D |
| Highest Return Rate | Store B – 27% |
| Average Delivery Time | 6.04 days |

## 📈 Business Value

This project demonstrates how data analytics can help businesses:

- Monitor sales performance.
- Identify growth opportunities.
- Understand customer purchasing patterns.
- Evaluate product and regional performance.
- Monitor operational costs and product returns.
- Make informed business decisions using data.

## 📁 Project Files

The repository can be organised as follows:

```text
Retail-Sales-Performance-Analysis/
│
├── Dataset/
│   └── Retail_Sales_Data.xlsx
│
├── PowerBI/
│   └── Retail_Sales_Performance_Analysis.pbix
│
├── Documentation/
│   └── Retail_Sales_Performance_Analysis_Report.pdf
│
├── Screenshots/
│   ├── Sales_Overview.png
│   ├── Time_Intelligence.png
│   ├── Dashboard_1.png
│   └── Dashboard_2.png
│
└── README.md
```

*Replace the example filenames with the actual filenames you upload.*

## 🚀 Skills Demonstrated

- Data Cleaning and Data Preparation
- Exploratory Data Analysis
- Microsoft Excel and PivotTables
- Power Query and Data Transformation
- Star Schema and Data Modelling
- DAX Calculated Columns and Measures
- Time Intelligence Analysis
- Power BI Dashboard Development
- Business Insights and Data-Driven Recommendations

## 👩‍💻 About Me

I am an **Aspiring Data Analyst** interested in transforming raw data into meaningful insights and supporting better business decisions.

This project represents my practical learning in Excel, Power Query and Power BI, with a focus on business-oriented data analysis and visualisation.

**Thank you for visiting my project!**
