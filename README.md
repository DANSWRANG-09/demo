# 📊 Sales Performance Analytics Dashboard

An interactive **Microsoft Excel Sales Analytics Dashboard** designed to analyze sales performance, profitability, customers, products, regions, and monthly trends.

This project demonstrates practical **Data Analyst skills** including data preparation, KPI analysis, business-focused visualization, and interactive dashboard design.

---

## 📌 Dashboard Preview

![Sales Performance Analytics Dashboard](./sales_dashboard_preview.svg)

> The dashboard provides an interactive view of sales and profitability performance across products, categories, regions, and customer segments.

---

## 🎯 Business Problem

A retail business needs a simple way to understand its sales performance and identify the key factors driving revenue and profit.

The objective of this project is to analyze sales data and build an interactive dashboard that helps identify:

- Which products generate the most revenue?
- Which categories perform best?
- Which regions generate the highest sales?
- How do sales change throughout the year?
- How much profit is generated from sales?
- Which areas may require further business attention?

---

## 🎯 Project Objectives

- Analyze overall sales and profitability.
- Track important business KPIs.
- Identify top-performing products and categories.
- Compare sales performance across regions.
- Analyze monthly sales trends.
- Understand customer segment performance.
- Create an interactive business dashboard.

---

## 📂 Dataset

The project uses a **synthetic retail sales dataset** created specifically for portfolio and learning purposes.

### Dataset Details

- **800 orders**
- **160 customers**
- **12 months of sales data**
- **4 regions**
- **3 customer segments**
- **3 product categories**
- Product-level sales and profit information

### Main Columns

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date of the order |
| Customer | Customer identifier |
| Region | Sales region |
| Customer Segment | Customer type |
| Category | Product category |
| Product | Product name |
| Quantity | Units purchased |
| Discount | Discount applied |
| Sales | Revenue generated |
| Profit | Profit generated |

---

## 🧹 Data Preparation

The dataset was prepared before creating the dashboard.

### Data preparation steps

- Checked data types
- Standardized categorical values
- Checked duplicate Order IDs
- Created **Order Month**
- Created **Order Year**
- Calculated **Profit Margin**
- Validated sales and profit calculations
- Prepared summarized tables for dashboard analysis

---

## 📊 Key KPIs

The dashboard tracks the following business metrics:

| KPI | Result |
|---|---:|
| Total Sales | **$539,629** |
| Total Profit | **$188,402** |
| Total Orders | **800** |
| Total Customers | **160** |
| Average Order Value | **$675** |
| Profit Margin | **34.9%** |

---

## 📈 Dashboard Features

### KPI Cards

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Average Order Value
- Profit Margin

### Interactive Filters

Users can explore the dashboard using:

- Region
- Category
- Customer Segment

### Visualizations

- 📈 Monthly Sales & Profit Trend
- 📊 Sales by Category
- 🌎 Sales by Region
- 🏆 Top 10 Products by Sales
- 💡 Key Business Insights

---

## 🔍 Key Insights

### 1. Technology leads revenue

Technology is the highest-revenue category, generating approximately **$318.7K** in sales.

### 2. South is the strongest region

The South region generates the highest sales at approximately **$161.6K**.

### 3. Laptops are the top product

Laptops are the highest-revenue product, generating approximately **$187.5K**.

### 4. July records the highest monthly sales

July is the strongest sales month with approximately **$62.0K** in revenue.

### 5. Profitability matters alongside revenue

The dashboard compares sales with profit to avoid evaluating business performance based only on revenue.

---

## 💡 Business Recommendations

Based on the analysis:

1. **Focus on high-performing technology products** while monitoring their profit margins.
2. **Investigate the South region** to understand what is driving its stronger performance and replicate successful strategies elsewhere.
3. **Maintain strong laptop sales** while exploring opportunities to increase sales of complementary products.
4. **Use monthly sales patterns** to improve inventory planning and promotional campaigns.
5. **Review discount strategies** to ensure increased sales are translating into healthy profits.

---

## 🛠️ Tools Used

- **Microsoft Excel**
- Excel Formulas
- Excel Charts
- Data Validation / Dropdown Filters
- Dashboard Design
- Data Analysis

---

## 📁 Project Structure

```text
Sales-Performance-Analytics/
│
├── Sales_Performance_Analytics_Dashboard.xlsx
├── sales_dataset.csv
├── sales_dashboard_preview.svg
└── README.md
