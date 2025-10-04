
# 📱 Mobile Sales Data Analysis & Performance Dashboard

## ✨ Project Overview

This is an end-to-end business intelligence project focused on analyzing mobile sales transactional data to derive actionable insights into **product performance, market share, and customer behavior**. The resulting interactive dashboard provides retail management with a centralized view for strategic decision-making related to inventory, marketing, and pricing.

* **Business Problem:** How to effectively track performance across various brands, mobile models, and cities to identify revenue drivers and areas for sales optimization.
* **Key Deliverable:** A comprehensive Power BI dashboard that segments performance by product, geography, and customer.

## 🛠️ Technology Stack

| Component | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Data Source** | **CSV / Excel** | Raw transactional data for mobile sales. |
| **Data Modeling & Transformation** | **Power Query (M Language)** | Initial data cleaning, defining relationships, and shaping the data model within Power BI. |
| **Business Intelligence** | **Power BI** | Visualization, dynamic reporting, and implementation of complex **DAX measures**. |

---

## 📊 Key Performance Indicators (KPIs)

The dashboard's core focus is on these essential retail metrics, displayed prominently for immediate monitoring:

| KPI | Calculation / Insight |
| :--- | :--- |
| **Total Sales (Revenue)** | Sum of `Units Sold` $\times$ `Price Per Unit`. The ultimate financial measure. |
| **Total Units Sold** | Volume of mobile devices sold, indicating market demand. |
| **Total Customers** | Measures market penetration and reach. |
| **Avg. Price Per Unit (ASP)** | Indicator of the general price point of devices being sold (budget vs. premium mix). |
| **Avg. Customer Rating** | Links sales performance directly to **customer satisfaction and product quality.** |

---

## 🔍 Analytical Features & Insights

The Power BI dashboard is segmented to provide detailed analysis across multiple dimensions, allowing for effective root-cause analysis:

### 1. Product Performance Analysis
* **Sales by Brand:** Identifies market share leaders (e.g., Xiaomi, Vivo, Samsung) and informs supplier negotiation and marketing budget allocation.
* **Sales by Mobile Model:** Pinpoints the best-selling specific models, guiding **inventory management** and stock levels to prevent overstocking or stockouts.

### 2. Market & Geographic Analysis
* **Sales by City:** Geospatial breakdown showing where the highest and lowest revenue is generated, enabling targeted regional sales campaigns.
* **Sales Trend over Time:** Line chart used to identify seasonality, track performance against historical data, and forecast future demand.

### 3. Customer & Transaction Insights
* **Sales by Payment Method:** Reveals customer preference (Cash, UPI, Credit Card, etc.), providing insights for optimizing checkout processes and transaction fee management.
* **Sales by Customer Age:** If available, this allows for the creation of targeted marketing segments based on demographic spending habits.


## 🚀 How to Replicate the Project

1.  **Data Source:** Load the `Mobile Sales Data - PROJECT 1.xlsx - Sheet1.csv` file into Power BI Desktop.
2.  **Calculations (DAX):** Recreate the key measures, including `Total Sales = SUM('Table'[Units Sold] * 'Table'[Price Per Unit])` and measures for the Average Price and Average Rating.
3.  **Visualization:** Build the KPI cards, line charts, and segmented bar charts as shown in the screenshots, using Brand, Mobile Model, and City as dimensions.
