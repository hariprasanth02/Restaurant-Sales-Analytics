# 🍽️ Restaurant Sales Analytics Dashboard
 
[![Live Demo](https://img.shields.io/badge/Power%20BI-Live%20Demo-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiNjM4MGRmNzMtYmY3ZS00Yzc3LTk2OGMtZjExZTFmNjAwODI2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
 
A multi-page **Power BI dashboard** built to analyze restaurant sales performance across products, time periods, and customer ordering patterns — covering **$159K+ in revenue** across **12,234 orders** over a 3-month period (January–March).
 
---
 
## 📊 Dashboard Pages
 
### 1. Overview
High-level KPIs and category-level revenue breakdown.
 
| Metric | Value |
|---|---|
| Total Revenue | $1,59,218 |
| Total Orders | 12,234 |
| Total Items Sold | 12,097 |
| Avg Order Value | $13.01 |
 
- **Category Revenue Distribution** (Donut Chart): Italian leads at 31.07%, followed by Asian (29.34%), Mexican (21.85%), and American (17.74%)
- **Monthly Orders vs Revenue** (Combo Chart): Tracks order volume (bar) and revenue trend (line) across Jan–Mar; February showed a revenue dip to $50.8K before recovering to $54.6K in March
### 2. Product Performance Analysis
Granular product-level insights to identify top performers.
 
| KPI Card | Value |
|---|---|
| Top Revenue Item | Korean Beef Bowl |
| Top Category | Italian |
| Top Selling Item | Hamburger |
 
- **Top Selling Items** (Bar Chart): Hamburger (622), Edamame (620), Korean Beef Bowl (588), Cheeseburger (583), French Fries (571)
- **Total Revenue by Item** (Bar Chart): Korean Beef Bowl ($10.6K), Spaghetti & Meatballs ($8.4K), Tofu Pad Thai ($8.1K)
- **Category Analysis** (Donut Chart): Nearly even split — Italian (28.68%), Asian (24.37%), Mexican (24.34%), American (22.6%)
### 3. Sales Trends & Time Analysis
Revenue behavior across days, hours, weeks, and weekday vs. weekend.
 
| KPI Card | Value |
|---|---|
| Total Revenue | $1,59,218 |
| MoM Growth % | -5.62% |
| Previous Month Revenue | $53.82K |
 
- **Revenue by Day Name**: Monday leads ($26K), Wednesday lowest ($20K)
- **Day Type Revenue**: Weekdays drive 72.12% of revenue ($115K) vs. Weekends at 27.9% ($44K)
- **Revenue by Hour**: Peak revenue windows around hours 12–13 and 18–19
- **Revenue by Week**: Consistent weekly performance ranging $11K–$13K
---
 
## 🛠️ Tools & Technologies
 
| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design, DAX measures, report pages |
| **Power Query** | Data transformation and cleaning |
| **DAX** | KPI calculations (MoM Growth %, Avg Order Value, Weekend %, etc.) |
| **Microsoft Excel / CSV** | Source data format |
 
---
 
## 📁 Project Structure
 
```
restaurant-sales-analytics/
│
├── RestaurantSalesAnalytics.pbix   # Main Power BI file
├── data/
│   └── restaurant_orders.csv       # Raw dataset
├── screenshots/
│   ├── overview.png
│   ├── product_analysis.png
│   └── time_analysis.png
└── README.md
```
 
---
 
## 💡 Key Business Insights
 
- **Italian cuisine** is the highest revenue-generating category (31%), making it the anchor of the menu
- **Korean Beef Bowl** is the single highest-revenue item at $10.6K — priced at a premium and high in demand
- **Hamburger** is the most-ordered item (622 orders) but not the top revenue item, suggesting a lower price point with high volume
- **February dip** in revenue (-5.62% MoM) followed by a March recovery indicates possible seasonal or operational variance worth investigating
- **72% of revenue comes from weekdays**, pointing to a likely lunch/office crowd; weekend traffic remains untapped
- **Monday is the strongest day** ($26K), contradicting the typical assumption that weekends drive restaurant traffic
---
 
## 🔍 Filters Available
 
All pages support cross-filtering via:
- **Month** (January / February / March)
- **Category** (American / Asian / Italian / Mexican)
- **Item Name** (individual menu items)
---
 
## 📸 Screenshots
 
| Overview | Product Analysis | Time Analysis |
|---|---|---|
| ![Overview](<img width="1298" height="728" alt="Screenshot 2026-04-17 193803" src="https://github.com/user-attachments/assets/bc745a79-1d13-493a-bf31-de4d5df9d54d" />)
| ![Product](screenshots/product_analysis.png) | ![Time](screenshots/time_analysis.png) |
 
---
 
## 🚀 How to Use
 
### Option 1 — View Live (no install needed)
👉 **[Open Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjM4MGRmNzMtYmY3ZS00Yzc3LTk2OGMtZjExZTFmNjAwODI2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**
 
### Option 2 — Run Locally
1. Clone or download this repository
2. Open `RestaurantSalesAnalytics.pbix` in **Power BI Desktop**
3. If prompted, update the data source path to point to `data/restaurant_orders.csv`
4. Refresh the data and explore all three report pages
---
 
## 👤 Author
 
**Hari Prasanth**
- 🔗 [LinkedIn](https://www.linkedin.com/in/hariprasanth02)
- 💻 [GitHub](https://github.com/hariprasanth02)
---
 
## 📌 Tags
 
`Power BI` `Data Analytics` `Restaurant Analytics` `DAX` `Business Intelligence` `Sales Dashboard` `Food & Beverage` `Power Query`
