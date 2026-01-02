# 📊Global Electronics Retailer Sales Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-Desktop-yellow?style=for-the-badge&logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 🖼️ Dashboard Preview
<a href="https://i.imghippo.com/files/vDyh3378Xs.png" target="_blank" rel="noopener"><img src="https://i.imghippo.com/files/vDyh3378Xs.png" alt="Uploaded image on Imghippo" border="0"></a>
## 📝 Project Overview
This project involves a comprehensive analysis of the **Global Electronics Retailer Dataset**, focusing on international sales performance, customer demographics, and product profitability.

The goal was to develop an interactive **Power BI Dashboard** that enables stakeholders to monitor financial health, identify high-growth geographic regions, and understand consumer buying patterns.  
The analysis highlights how revenue and profit margins vary across different product categories and age groups to support data-driven inventory and marketing strategies.

**Dataset Source:**  
[Maven Analytics - Global Electronics Retailer](https://mavenanalytics.io/data-playground/global-electronics-retailer)

---

## 🎯 Key Business Questions Answered
1. **Financial Health:** What is the overall revenue and profit margin, and how is year-over-year growth trending?
2. **Product Performance:** Which product categories (e.g., Computers, Cell Phones) are the primary drivers of revenue?
3. **Geographic Distribution:** Which continents and countries exhibit the highest store density and sales volume?
4. **Customer Demographics:** How do age groups and gender influence purchasing behavior for electronics?

---

## 📊 Dashboard Features & Insights

### 1. KPI Header
- **Total Revenue:** $92K  
- **Total Profit:** $54K  
- **Quantity Sold:** 342 Units  
- **Profit Margin:** 0.58%  
- **YoY Revenue Growth:** -0.85% (Indicating a need for market stabilization)

### 2. Temporal Analysis
- **Total Profit and Revenue by YearMonth:**  
  A trend line showing a significant decline from early 2021 through the end of the year.
- **Insight:**  
  Despite falling volume, profit margins remained consistent as revenue and profit lines tracked closely together.

### 3. Geographic Performance
- **Store Revenue Density Map:**  
  Visualizes global store distribution and sales concentration.
- **Insight:**  
  **North America** is the dominant market, accounting for 61.42% of the customer base, followed by Europe at 25.85%.

### 4. Product & Category Insights
- **Revenue by Category:**  
  A bar chart ranking product performance.
- **Insight:**  
  **Computers** are the top-performing category by a significant margin, followed by Cell Phones and Cameras.

### 5. Demographic Breakdown
- **Revenue by Age Group:**  
  Analysis of buyer segments.
- **Insight:**  
  Excluding unspecified data, the **"50+ (Mature)"** segment is the most active purchasing group, making them a primary target for high-value electronics.

---

## 🛠️ Technical Implementation
- **Data Pre-processing:**  
  Utilized **Power Query** to clean blank values in demographic fields and organize date hierarchies.
- **DAX Measures:**  
  Developed custom expressions for financial tracking:
  - `Total Revenue` = $92K  
  - `Total Profit` = $54K  
  - `Profit Margin %` = 0.58%  
  - `YoY Revenue Growth` = -0.85%
- **Data Visualization:**  
  Integrated scatter plots for subcategory margin analysis and treemaps for geographic store density.

---

## 🚀 Future Scope
1. **Predictive Analytics:**  
   Forecasting sales for the upcoming year based on 2021 historical trends.
2. **Churn Analysis:**  
   Investigating the causes behind negative YoY growth to retain at-risk customers.
3. **Live Connectivity:**  
   Transitioning to a SQL database for real-time monitoring.

---

## 👤 Author
**Sravanesh Desu**  
**LinkedIn:** https://www.linkedin.com/in/sravanesh-desu
