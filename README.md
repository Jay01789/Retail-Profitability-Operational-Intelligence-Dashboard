# 📊 Retail Profitability & Operational Intelligence Dashboard



## 📌 Project Overview



The **Retail Profitability & Operational Intelligence Dashboard** is an end-to-end Power BI Business Intelligence project built using the Superstore dataset. The dashboard transforms raw retail transaction data into actionable insights that help management monitor business performance, identify profitability drivers, understand customer behavior, optimize product performance, and support strategic decision-making.



The project follows a business-driven approach by answering three key questions:



* **How is the business performing?**

* **Why is profitability changing?**

* **What actions should the business take to improve performance?**



---



# 🎯 Project Objectives



* Monitor overall sales and profitability performance.

* Analyze profitability across products, regions, and customer segments.

* Identify loss-making products and the impact of discounting.

* Understand customer behavior using RFM Segmentation and Customer Lifetime Value (CLV).

* Evaluate product performance and forecast future sales.

* Analyze operational efficiency through delivery performance.

* Implement secure region-based reporting using Dynamic Row-Level Security (RLS).



---



# 🧰 Tools & Technologies



* **Power BI**

* **DAX (Data Analysis Expressions)**

* **Power Query**

* **Excel / CSV**

* **Dynamic Row-Level Security (RLS)**



---



# 📊 Dashboard Pages



## 1️⃣ Executive Overview



Provides a high-level summary of overall business performance for management and decision-makers.



### KPIs



* Total Sales

* Total Profit

* Profit Margin %

* Orders Count

* Average Order Value (AOV)



### Visuals



* Monthly Sales Trend

* Sales vs Profit Scatter Plot

* Sales by Category (Treemap)

* Profit by State (Map)



### Business Value



* Monitor overall business performance

* Track sales trends

* Compare regional profitability

* Understand category contribution

* Identify products with strong sales and profit



---



## 2️⃣ Profitability & Root Cause Analysis



Focuses on understanding the factors influencing profitability and identifying improvement opportunities.



### Visuals



* Sales, Profit & Margin Matrix

* State × Category Profitability Heatmap

* Profit Decomposition Tree

* Discount vs Profit Scatter Plot

* Loss-Making Products Analysis



### Business Value



* Identify profitable and underperforming products

* Analyze the impact of discounts on profit

* Perform root-cause analysis of profitability

* Detect regional performance gaps

* Support pricing and product optimization decisions



---



## 3️⃣ Customer & Product Intelligence



Analyzes customer behavior, product performance, operational efficiency, and future sales trends.



### Visuals



* RFM Segmentation

* Customer Lifetime Value (CLV) Analysis

* Top Products (Bookmark Toggle: Sales ↔ Profit)

* 6-Month Sales Forecast

* Average Delivery Days by Ship Mode



### Business Value



* Identify high-value and at-risk customers

* Improve customer retention strategies

* Compare product sales and profitability

* Forecast future demand

* Improve inventory planning and logistics efficiency



---



# 📐 Key Metrics & Calculations



### Sales & Profit



* Total Sales

* Total Profit

* Profit Margin %

* Average Order Value



### Operational Metrics



* Orders Count

* Average Delivery Days



### Customer Intelligence



* Customer Lifetime Value (CLV)

* RFM Segmentation



### Product Intelligence



* Product Sales & Profit Analysis

* Sales Forecast



All business calculations and DAX measures are documented separately.



---



# 🔐 Dynamic Row-Level Security (RLS)



The dashboard implements **Dynamic Row-Level Security (RLS)** to provide secure region-based access.



### Implementation



* User Security Mapping Table

* USERPRINCIPALNAME() based filtering

* Region-specific data access



### Business Value



* Secure enterprise reporting

* Centralized dashboard

* Controlled access for different regional managers



---



# 💡 Key Business Insights



* High sales do not always generate high profit.

* Excessive discounting reduces overall profitability.

* Some products consistently generate losses and require pricing or portfolio review.

* Profitability varies significantly across regions and product categories.

* High-value customers contribute a significant share of business revenue.

* Sales forecasting supports proactive inventory and resource planning.

* Delivery performance directly impacts operational efficiency and customer satisfaction.



---



# 🚀 Business Impact



The dashboard enables businesses to:



* Improve pricing and discount strategies

* Increase overall profitability

* Reduce losses from underperforming products

* Retain high-value customers

* Optimize inventory planning

* Improve delivery performance

* Support data-driven strategic decision-making



---



# 📁 Project Structure



```text

Retail Profitability & Operational Intelligence Dashboard/

│

├── Dataset/

│   └── Retail_Sales_Data.csv

│

├── Dashboard/

│   └── RETAIL PROFITABILITY & OPERATIONAL INTELLIGENCE DASHBOARD.pbix

│

├── Screenshots/

│   ├── RETAIL PROFITABILITY & OPERATIONAL INTELLIGENCE DASHBOARD PDF.pdf

│

├── Documentation/

│   ├── Data_Dictionary.xlsx

│   └── DAX_Measures.xlsx

│

└── README.md

```



---



# 📊 Advanced Power BI Features Used



* Dynamic Row-Level Security (RLS)

* Bookmarks

* Custom Tooltips

* Drill-Down Matrix

* Decomposition Tree

* Forecasting

* Conditional Formatting

* Interactive Slicers

* Advanced DAX Measures



---



# 📌 Conclusion



This project demonstrates an end-to-end Business Intelligence solution that transforms retail sales data into meaningful business insights. By combining profitability analysis, customer intelligence, product analytics, forecasting, and operational monitoring, the dashboard supports data-driven decision-making and helps improve profitability, operational efficiency, and long-term business growth.



---



# 📌 Disclaimer



This project uses the Superstore sample dataset for learning and portfolio purposes. The dashboard is intended to demonstrate Power BI, data modeling, DAX, and business intelligence capabilities.
