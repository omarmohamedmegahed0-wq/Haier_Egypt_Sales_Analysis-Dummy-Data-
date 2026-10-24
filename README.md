# ❄️ Haier Egypt Sales Analytics & Performance Dashboard

## 📌 Executive Summary
This project demonstrates an end-to-end data analytics workflow applied to a commercial sales scenario for **Haier Egypt**. The analysis transforms public web-scraped product reference data into a comprehensive synthetic transaction dataset (**19,847 order records**) spanning from **January 1, 2025, to October 15, 2026**.

The final deliverable is an interactive **3-Page Microsoft Excel Dashboard** that translates complex operational, financial, and logistical data into actionable business insights for sales strategy, partner management, and regional growth.

---

## 📊 Key Performance Indicators (KPI Snapshot)
- **Total Gross Revenue:** EGP 739.31 M
- **Total Discounts Offered:** EGP 47.64 M
- **Net Sales (Revenue - Discount):** EGP 691.67 M
- **Total Operating Profit:** EGP 291.51 M
- **Overall Profit Margin:** 39.4%
- **Total Units Sold:** 27,069 units
- **Total Orders Recorded:** 19,847 orders (Fulfillment Delivery Success Rate: ~88.9%)
- **Market Footprint:** 59 Product Models | 27 Sales Partners | 4 Distribution Channels | 5 Regions (23 Cities)

---

## 🔍 Key Business Insights & Highlights

### 1. Regional & Distribution Performance
- **Top Generating Regions:** **Greater Cairo** leads regional revenue contribution at **EGP 242.9M**, followed closely by the **Delta region** at **EGP 187.8M**.
- **Distribution Channels:** Evaluated multi-channel performance across Electronics Retailers, Dealers, Direct Stores, and E-commerce platforms.

### 2. Product Category Analysis
- **Air Conditioners:** Highest revenue-generating and volume-leading category (**EGP 222.10M** / **6,542 units sold**).
- **Refrigerators:** Second highest revenue category (**EGP 173.54M** / **5,326 units sold**).
- **Washing Machines:** Generated **EGP 130.91M** across **5,275 units**.
- **Other Categories:** TVs (**EGP 82.06M**), Dishwashers (**EGP 79.46M**), and Freezers (**EGP 51.24M**).

### 3. Operational & Partner Insights
- Analyzed performance metrics across **27 sales partner entities** to highlight top accounts and commercial discount distributions.
- Evaluated delivery lead times, order cancellation drivers, and 30-day return flags.

---

## 🛠️ End-to-End Workflow & Methodology

1. **Web Scraping & Reference Collection:** Gathered public product catalogues, model numbers, and price benchmarks to establish real-world context.
2. **Synthetic Data Engineering:** Generated order-level transaction logs introducing realistic dimensions (`Order_ID`, `Customer_Segment`, `Sales_Partner`, `Payment_Method`, `Promotion_Name`, etc.).
3. **Data Profiling & Quality Control:** Applied cleaning rules to resolve missing values, standardized text casing, handled placeholders ("N/A"), and validated derived formulas.
4. **Calculated Fields & Helper Columns:** Engineered financial formulas (`Order_After_Discount`, `Profit_Per_Order`) and date-helper columns (`Quarter`, `Month Index`, `Year`) for smooth timeline filtering.
5. **Excel Reporting Model:** Structured multi-tab visual dashboards using Pivot Tables, Pivot Charts, and Dynamic Slicers.

---

## 🖥️ Dashboard Architecture
The workbook contains 3 main interactive reporting tabs:
1. **Overview Page:** Executive KPI cards, order fulfillment status distribution (Delivered, Delayed, Cancelled, Returned), and overall monthly trend lines.
2. **Sales Trend Page:** Quarterly performance, regional breakdowns, and Top 10 Sales Partners by revenue.
3. **Products Page:** Revenue and unit volume by category, category margin evaluation, and transaction-level discount scatter analysis.

---

##LinkedIn
-https://www.linkedin.com/in/omar-megahed-b54547326
