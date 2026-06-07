# 📊 RETAIL PROFITABILITY & OPERATIONAL INTELLIGENCE DASHBOARD – Power BI Project

## 📌 Project Overview
This Power BI project provides a comprehensive business intelligence solution using the Superstore dataset. The dashboard analyzes sales performance, profitability, customer behavior, operational inefficiencies, product demand, logistics performance, and future sales forecasting.

The project was designed to simulate a real-world enterprise analytics environment where management requires both high-level strategic insights and detailed operational analysis for decision-making.

The dashboard covers multiple business domains including:

- Executive performance monitoring
- Profitability analysis
- Profit leakage investigation
- Customer and service intelligence
- Product performance and forecasting
- Enterprise-level security implementation using Dynamic Row-Level Security (RLS)

The analysis transforms raw transactional data into actionable business insights that support data-driven decision-making across sales, operations, logistics, customer management, and strategic planning.

---

# 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall sales and profitability performance
- Monitor business KPIs and operational efficiency
- Identify profit-driving and loss-making categories/products
- Detect profit leakage caused by discounts and operational inefficiencies
- Evaluate regional and category-level performance
- Analyze customer behavior and customer lifetime value
- Perform customer segmentation using RFM analysis
- Evaluate logistics and delivery performance
- Identify high-demand and high-value products
- Forecast future sales trends using predictive analytics
- Implement secure region-based data access using Dynamic Row-Level Security

---

# 🧰 Tools & Technologies

- **Power BI** – Dashboard development and data visualization
- **DAX (Data Analysis Expressions)** – Measures, KPIs, calculated columns, and RLS logic
- **Power Query** – Data cleaning and transformation
- **Excel / CSV** – Data source and documentation
- **Dynamic Row-Level Security (RLS)** – Enterprise-level access control implementation

---

# 📊 Dashboard Pages Overview

## 1️⃣ Executive Overview

This page acts as a high-level business summary dashboard designed for executives and decision-makers.

### Key Features

#### KPI Cards
- Total Sales
- Total Profit
- Profit Margin %
- Orders
- Quantity Sold
- Average Order Value (AOV)

### Visuals Included
- Monthly Sales Trend (Line Chart)
- Region Performance Map
- Category Contribution Treemap
- Sales vs Profit Scatter Plot

### Business Value
Provides a quick understanding of:
- Business growth trends
- Regional profitability
- Category contribution
- Revenue vs profitability relationship

---

## 2️⃣ Sales & Profit Analysis

This page focuses on deep profitability and operational performance analysis.

### Visuals Included
- Matrix Report with hierarchical drill-down
- Profit Contribution Waterfall Chart
- State vs Category Profitability Heatmap
- Profit Decomposition Tree

### Business Value
Helps identify:
- Profitable and loss-making categories
- Margin performance
- Regional weaknesses
- Profit drivers and operational inefficiencies

---

## 3️⃣ Profit Leakage Analysis

This page was designed to identify hidden financial inefficiencies and profitability erosion.

### Visuals Included
- Discount vs Profit Scatter Plot
- Bottom 10 Loss-Making Products
- Loss by State Column Chart
- Profit Margin Gauge KPI

### Business Value
Supports:
- Pricing optimization
- Discount strategy evaluation
- Loss reduction
- Margin improvement initiatives

---

## 4️⃣ Customer & Service Intelligence

This page combines customer analytics with service and logistics intelligence.

### Customer Analytics
- Customer Segmentation Analysis
- Top Customers by Revenue
- Customer Lifetime Value Analysis
- RFM Segmentation:
  - High Value Customers
  - Loyal Customers
  - At Risk Customers

### Service & Logistics Analysis
- Average Delivery Time by Ship Mode
- Delivery Performance Analysis
- On-Time vs Delayed Deliveries

### Business Value
Supports:
- Customer retention strategies
- Customer experience improvement
- Delivery optimization
- Service quality monitoring

---

## 5️⃣ Product & Forecast Intelligence

This page combines product performance analysis with predictive analytics.

### Visuals Included
- 6-Month Sales Forecast
- Top 5 Products by Order Volume
- Top 10 Products by Quantity Sold
- Top Products by Sales / Profit
- Bookmark-Based Toggle Between Sales & Profit Views
- Custom Tooltip Page for Product Insights

### Business Value
Supports:
- Inventory planning
- Demand forecasting
- Product portfolio optimization
- Strategic sales planning

---

# 📐 Key Metrics & Calculations

The project includes multiple DAX measures and calculated columns such as:

## Sales & Profit Metrics
- Total Sales
- Total Profit
- Profit Margin %
- Average Order Value (AOV)

## Operational Metrics
- Orders Count
- Quantity Sold
- Delivery Days
- Average Delivery Time

## Customer Intelligence Metrics
- Customer Lifetime Value
- RFM Segmentation Logic
- Customer Frequency Analysis

## Profit Leakage Metrics
- Loss Only Measure
- Discount Impact Analysis

## Forecasting & Product Metrics
- Product Order Volume
- Product Profitability Analysis
- Sales Forecasting

All calculations and business logic are documented separately in a Data Dictionary file.

---

# 🔐 Dynamic Row-Level Security (RLS)

This project includes enterprise-level Dynamic Row-Level Security implementation.

## Security Implementation
- Created a User Security Mapping table
- Mapped user email IDs to assigned business regions
- Applied dynamic filtering using:
  ```DAX
  USERPRINCIPALNAME()
  ```

## Functionality
Each user can only access data related to their assigned region.

### Example
- West Region Manager → West region data only
- South Region Manager → South region data only

### Business Value
- Enhances data security
- Supports enterprise reporting standards
- Eliminates need for multiple dashboards
- Enables centralized secure reporting

---

# 💡 Key Business Insights

- High sales do not always translate into high profitability
- Excessive discounting negatively impacts profit margins
- Certain states consistently generate losses despite strong sales
- Technology category contributes the highest overall profit
- Customer purchasing behavior varies significantly across segments
- Delivery delays can negatively impact customer experience and retention
- A small number of products drive a large percentage of sales volume
- Forecasting indicates seasonal sales trends and future growth opportunities

---

# 🚀 Business Impact

The insights generated from this dashboard can help businesses:

- Improve pricing and discount strategies
- Reduce operational and regional losses
- Optimize inventory and supply chain management
- Improve customer retention and loyalty
- Enhance delivery performance
- Support strategic forecasting and budgeting
- Enable secure enterprise-wide reporting

---

# 📁 Project Structure

```bash
RETAIL PROFITABILITY & OPERATIONAL INTELLIGENCE DASHBOARD/
│
├── Dataset/
│   ├── Superstore_Data.csv
│
├── Dashboard/
│   ├── RETAIL PROFITABILITY & OPERATIONAL INTELLIGENCE DASHBOARD.pbix
│
├── Screenshots/
│   ├── Executive_Overview.png
│   ├── Sales_Profit_Analysis.png
│   ├── Profit_Leakage_Analysis.png
│   ├── Customer_Service_Intelligence.png
│   ├── Product_Forecast_Intelligence.png
│
├── Documentation/
│   ├── Data_Dictionary.xlsx
│   ├── DAX_Measures.xlsx
│
└── README.md
```

---

# 📊 Advanced Power BI Features Used

- Dynamic Row-Level Security (RLS)
- Bookmark Navigation
- Custom Tooltip Pages
- Drill-Down Functionality
- Conditional Formatting
- Forecasting
- Decomposition Tree
- Interactive Slicers
- KPI Indicators
- Dynamic Measures

---

# 📌 Disclaimer

This project uses sample/simulated retail data for learning and portfolio purposes only. The analysis and insights are intended to demonstrate business intelligence, data visualization, and analytical capabilities using Power BI.

---
