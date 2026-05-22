# Flipkart Interactive Sales Performance & Deep-Dive Dashboard

## 🚀 Project Overview
This project focuses on building an enterprise-grade, multi-page Business Intelligence (BI) tool using a highly polished dark-theme UI style. The goal was to transform raw retail transaction data into an interactive executive command center that balances high-level financial tracking with advanced, root-cause analytical capabilities.

---

## 📊 Dashboard Previews

### Page 1: Executive Summary
![Executive Summary](page1.png)

### Page 2: Advanced Performance Deep-Dive
![Performance Deep-Dive](page2.png)

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI Desktop
* **Data Modeling:** Star Schema design, managing multi-table data relationships, and implementing cross-page synced slicers.
* **Data UX/UI Design:** Custom dark-themed presentation, conditional formatting text triggers, custom color hex-mapping, and scannable visual hierarchies.
* **Data Engineering/Prep:** Data cleaning, format normalization, and handling display units.

---

## 📈 Dashboard Architecture & Insights

### Page 1: Executive Summary (High-Level Performance)
* **Unified KPI Grid:** Displays critical business health metrics: Total Revenue ($1.64M), Total Orders (88), Total Units Sold (270), and Avg Customer Rating (3.06).
* **Total Sales vs. Net Profit Margin Trends:** A dual-axis line and clustered column chart tracking profitability over time to spot performance anomalies chronologically.
* **Market Dynamics:** Dual donut charts tracking *Market Share by Customer Segment* and *Transaction Volume by Payment Method* (highlighting digital wallet and UPI penetration).
* **Outlier & Flow Trackers:** A waterfall chart charting *Revenue Accumulation Flow* by product groupings alongside a scatter plot showing *Discount Impact vs. Revenue Generation*.

### Page 2: Advanced Performance Deep-Dive (Granular Analysis)
* **Financial Performance Matrix:** A dense pivot grid crossing Regions, Months, and Product Categories with custom conditional text coloring that highlights negative profit vectors in crimson.
* **AI Decomposition Tree:** An interactive root-cause engine analyzing `Total Profit` branches dynamically across Region, Category, and Payment Method.
* **Ribbon Chart:** An ultra-fluid stream graph visualizing *Category Sales Rank Trends Over Time*, allowing stakeholders to immediately track rank shifts.

---

## 💡 Key Design & Optimization Implementations
1. **Slicer Synchronization:** Synced the `Month` and `Region` filters in the background, allowing user selections on Page 1 to seamlessly update the dense matrices on Page 2 without creating visual clutter.
2. **Chart Clutter Elimination:** Removed redundant default elements, gridlines, and repeating category titles to ensure a high data-to-ink ratio.
3. **Data Uniformity:** Normalized uneven numeric formatting and fixed display settings to guarantee numbers are clean and easily readable for business users.

---

## 📂 Repository Contents
* `flipkart_sales_dashboard_2026.pbix` - The primary, fully interactive Power BI workbook.
* `page1.png` & `page2.png` - High-resolution dashboard page screenshots for rapid evaluation.

---
*Feel free to explore the file or reach out if you have any questions or feedback regarding this implementation!*
