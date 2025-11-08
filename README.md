# 🛍️ E-commerce Sales Dashboard – Power BI Project
**Project by Poornima**

---

## 📄 Project Overview
This project analyzes **real-world e-commerce sales data** to uncover key business insights using **Microsoft Power BI** and **Excel**.  
The goal is to help business owners and decision-makers understand:
- Which products are best-selling 📦  
- When sales peak during the year 📆  
- Which categories, regions, or customers drive the most revenue 💰  

The final output is an **interactive Power BI dashboard** with filters, KPIs, and visualizations that tell a compelling business story.

---

## 🎯 Objectives
- Clean and transform raw sales data (Excel/CSV format).  
- Analyze key patterns such as:
  - Monthly sales trends
  - Category-wise performance
  - Customer purchasing behavior
- Create a visually engaging Power BI dashboard.
- Present actionable insights and recommendations for the business.

---

## 🧩 Dataset Description
**Dataset Name:** E-commerce Sales Data  
**Source:** Kaggle – E-commerce Dataset (UK-based Online Retailer)  
**File Format:** `.csv`  
Data covers transactions from 2009–2011

**Columns typically include:**

| Column Name | Description |
|-------------:|-------------|
| InvoiceNo    | Unique transaction number |
| StockCode    | Product/item code |
| Description  | Product name |
| Quantity     | Number of units sold |
| InvoiceDate  | Date and time of the transaction |
| UnitPrice    | Price per unit |
| CustomerID   | Unique customer identifier |
| Country      | Customer location |

---

## 🧹 Step 1: Data Cleaning (in Excel / Power BI)
- Remove duplicates and blank rows.  
- Handle missing values (especially `CustomerID`).  
- Format dates correctly (`InvoiceDate`).  
- Create calculated columns (e.g., `TotalSales = Quantity * UnitPrice`).  
- Remove transactions with negative quantities (returns).

---

## 📊 Step 2: Data Analysis
Analyze:
- **Top 10 Best-Selling Products**  
- **Monthly and Weekly Sales Trends**  
- **Revenue by Country / Region**  
- **Customer Lifetime Value**  
- **Product Category Contribution**

---

## 🖥️ Step 3: Dashboard Development (in Power BI)
Include:
- **KPIs Cards:** Total Sales, Total Orders, Avg. Order Value  
- **Line Chart:** Monthly Sales Trend  
- **Bar Chart:** Top 10 Products by Sales  
- **Map Visualization:** Sales by Country  
- **Pie/Donut Chart:** Category Contribution  
- **Slicers/Filters:** Year, Month, Country, Category
  
---

## 💡 Step 4: Insights & Recommendations
**Insights:**
- November–December often show peak sales (holiday season).  
- Categories like Others, Decorations, and Bags & Accessories contribute the highest revenue.  
- Repeat customers may account for a major share of revenue.

**Recommendations:**
- Launch seasonal promotions before peak months.  
- Focus marketing on top-performing categories.  
- Offer loyalty rewards to frequent customers.

---

![Dashboard Preview](https://github.com/Poornima044/FUTURE_DS_01/blob/main/screenshots.png)

---

## 🧰 Tools Used
- Microsoft Power BI  
- Microsoft Excel  
- Power Query  
- DAX (Data Analysis Expressions)  
- GitHub

---

## 🧠 Skills Gained
- Data Cleaning & Transformation  
- Time-Series Trend Analysis  
- DAX Calculations (KPIs & Measures)  
- Business Storytelling using Visuals  
- Power BI

E-commerce-Sales-Dashboard/
├── README.md
├── data/
│   └── ecommerce_sales.csv              # raw dataset (download from Kaggle)
├── analysis/
│   └── cleaned_data.xlsx                # cleaned sample dataset
├── reports/
│   └── PowerBI_Dashboard.pbix           # your Power BI file
└── screenshots/
    └── dashboard_preview.png            # dashboard preview image







