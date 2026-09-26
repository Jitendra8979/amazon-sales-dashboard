# 🛒 Amazon Sales & Delivery Performance Dashboard

## 📌 Project Overview
This project transforms raw e-commerce transaction data into an interactive Excel dashboard. The objective was to analyze sales performance, evaluate regional profitability, and track delivery fulfillment metrics to uncover operational bottlenecks. 

By utilizing advanced Excel functions (XLOOKUP, PivotTables) and dynamic KPI formatting, this dashboard provides stakeholders with an immediate, clear view of business health.

## 🛠️ Tech Stack & Tools
* **Microsoft Excel:** Data Cleaning, Data Modeling, and Dashboarding
* **Functions & Features Used:** `XLOOKUP`, `IFERROR`, PivotTables, PivotCharts, Data Validation, Slicers, and Conditional Formatting

## 🔍 Methodology
1. **Data Structuring:** Consolidated multiple data points including product masters, customer masters, and regional goals into a unified relational data model.
2. **Metrics Calculation:** Engineered calculated fields to determine Total Cost, Profit Margins, and Delivery Lead Times (Days).
3. **Status Tracking:** Built a delivery performance tracker categorizing orders as 'Fast', 'Slow', 'In-Transit', 'Delivered', or 'Cancelled'.
4. **Dashboard Design:** Developed an interactive, user-friendly interface controlled by slicers (by Month, Customer Type, and Region) for dynamic executive reporting.

## 📈 Key Business Insights
Based on the analysis of the latest 100 transaction records (Total Sales Volume: **$35,258**), the following insights were uncovered:

* **The Cancellation Bottleneck:** While 34% of orders were successfully delivered (capturing **$13,656** in realized revenue) and 36% remain in transit, the business faces a staggering **30% cancellation rate**. *Recommendation: Investigate logistics and fulfillment partners (DHL, UPS, Amazon Logistics) causing these drop-offs.*
* **Category Dominance:** **Electronics** is the flagship category, driving the highest total sales (**$15,209**) and the highest finalized delivered sales (**$6,126**), followed closely by Home goods. 
* **Regional Profitability:** The **North** region is the most profitable market, generating **$748** in net profit, dwarfing the East region's $222.
* **Customer Value:** Interestingly, while *Prime* members generated the highest initial checkout volume ($12,387), **Business (B2B)** customers yielded the highest volume of *successfully delivered* sales ($6,793), making them the most reliable customer segment.

## 📁 Repository Contents
* `MINI PROJECT.xlsx`: The complete Excel workbook containing the raw data, relational master sheets, pivot tables, and the final interactive dashboard.

---
**Author:** Jitendra Kumar  
*Data Analyst | Master of Statistics*
