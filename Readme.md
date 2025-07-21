# Supply Chain Analysis Project 📦

<div align="center">

![Supply Chain](https://img.shields.io/badge/Supply%20Chain-Analytics-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-EDA-green?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Dashboard-Insights-orange?style=for-the-badge)

</div>

<p align="center">
  <img src="supply flow.png" alt="Web App Sample" width="600"/>
</p>

## 📋 Project Information

**Data Source:** `supply data done.xlsx`  
**Python EDA:** `supply chain (python EDA).py`  
**Dashboards:** Power BI (see insights below)

## 📊 Project Overview

This project delivers a comprehensive analysis of supply chain operations, leveraging Python EDA and interactive dashboards to uncover actionable insights in inventory, suppliers, regional performance, product sales, and logistics. The goal is to optimize supplier management, inventory planning, customer targeting, and shipping efficiency.

## 🔍 Exploratory Data Analysis (EDA) Highlights

<p align="center">
  <img src="categorical data EDA.png" alt="Web App Sample" width="600"/>
</p>

<p align="center">
  <img src="EDA Product Preferences by Customer .png" alt="Web App Sample" width="600"/>
</p>

### Data Quality & Exploration
- **Data Exploration:** Checked for missing values, duplicates, and basic statistics
- **Numerical Analysis:** Used histograms and boxplots to assess distributions and outliers
- **Categorical Analysis:** Count plots for key categorical variables (e.g., shipping carriers, suppliers, locations)

### Pattern & Relationship Analysis
- Boxplots and scatterplots for product type vs. revenue, price vs. sales, availability vs. revenue

### Product Analysis
- Aggregated by product type for sales, revenue, price, and availability
- Identified top products, low stock, quality issues, and high shipping costs

### Supplier & Shipping Analysis
- Assessed supplier performance (lead time, defect rates, revenue)
- Shipping performance by carrier and mode

### Customer Analysis
- Revenue and product preferences by demographic

### Regional Insights
- Performance metrics by location (revenue, lead time, shipping time, defect rate)

## 📈 Dashboard Insights

### 1. 🏭 Inventory & Suppliers Management

#### Key Metrics
- **Production Volumes:** 56.8K units
- **Avg. Manufacturing Lead Time:** 15 days
- **Total Manufacturing Costs:** $4,727
- **Inspection Pass Rate:** 23% (⚠️ potential quality issue)

#### Supplier Performance
- **Top Suppliers:** Supplier 2 and Supplier 1 lead in production, but cost-effectiveness varies
- **Stock Levels:** Several SKUs (esp. in Skincare) are critically low—risk of stockouts
- **Skincare** leads in production and sales, but has the lowest stock-to-sales ratio

#### Action Items
- Negotiate with high-cost suppliers
- Improve quality control processes
- Prioritize replenishment of low-stock SKUs

### 2. 🌍 Regional Insights

#### Revenue by City
- **Top Cities by Revenue:**
  1. Kolkata: $663K
  2. Chennai: $567.5K
  3. Mumbai: $455.6K
  4. Delhi: $375K
  5. Bangalore: $224.6K

#### Customer Demographics
- **Gender Distribution:** 65% Female, 35% Male

#### Product Preferences by Gender
- **Female:** Skincare (top), then Cosmetics and Haircare
- **Male:** Skincare leads, but sales are more evenly distributed

#### Action Items
- Focus marketing and inventory on Kolkata/Chennai
- Tailor offerings to female customers
- Boost sales in Bangalore

### 3. 📊 Product & Sales Key Performance Indicators (KPI)

#### Overall Metrics
- **Total Revenue:** $2.3M
- **Total Products Sold:** 46K
- **Order Quantity:** 4.9K
- **Items:** 100

#### Top Performance
- **Top SKUs:** A few SKUs (e.g., SKU47, SKU11) drive most revenue; many underperform

#### Category Performance
- **Skincare:** $1.06M revenue, 20.7K units sold (dominates market)
- **Haircare:** $632.8K, 13.6K units
- **Cosmetics:** $599.5K, 11.8K units

#### Sales vs. Price Analysis
- **Skincare:** Higher prices = more sales
- **Cosmetics:** Higher prices = fewer sales

#### Action Items
- Prioritize Skincare expansion
- Review Cosmetics pricing strategy
- Optimize product portfolio

### 4. 🚚 Shipping & Logistics Insights

#### Key Metrics
- **Total Shipping Times:** 6
- **Total Shipping Costs:** $555

#### Transport Mode Distribution
- **Road:** 29%
- **Rail:** 28%
- **Air:** 26%
- **Sea:** 17%

#### Cost & Time Analysis
- **Sea:** Most cost-effective and fastest, but underutilized
- **Carrier A/C:** Most cost-effective; Carrier B is more expensive
- **Haircare:** Highest shipping cost
- **Route A:** Longest shipping times

#### Action Items
- Increase use of Sea transport
- Optimize Haircare logistics
- Negotiate with Carrier B
- Address Route A delays

## 💡 Key Recommendations

### Supply Chain Optimization
- **Negotiate with high-cost suppliers and improve quality control**
- **Monitor and replenish low-stock SKUs to avoid lost sales**

### Market Strategy
- **Prioritize inventory and marketing for high-demand cities and demographics**
- **Focus on Skincare for growth; review pricing for Cosmetics**

### Logistics Enhancement
- **Optimize shipping by using Sea transport and addressing bottlenecks**
- **Implement route optimization for improved delivery times**

### Quality Improvement
- **Address the 23% inspection pass rate through enhanced quality control**
- **Implement supplier performance monitoring systems**

---

## 🔮 Next Steps

This analysis provides the foundation for data-driven decision making in supply chain operations. The insights from this comprehensive analysis can be used to:

- Optimize inventory management strategies
- Improve supplier relationships and negotiations
- Enhance regional market penetration
- Streamline logistics and shipping operations
- Drive revenue growth through targeted product focus

---

**Supply Chain Analytics** - Transforming data into operational excellence! 📦📊
