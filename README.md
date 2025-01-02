# Supply Chain Analytics Dashboard

## Overview
The Supply Chain Analytics Dashboard is an interactive and comprehensive data visualization project built using **Tableau**, **MySQL**, and **Google Sheets**. It visualizes key performance indicators (KPIs), trends, and bottlenecks in delivery performance, supplier reliability, and regional operations. This project demonstrates data storytelling and analytical skills to optimize supply chain operations.

---

## Key Features
### Dashboard Tabs
1. **Delivery Trends**
   - Analyze delivery efficiency and identify delays.
   - Visualizations: Line charts, funnel charts, heatmaps, and KPI tiles.

2. **Supplier Performance**
   - Evaluate supplier reliability using RFM analysis.
   - Visualizations: Scatterplots, pie charts, line charts, and heatmaps.

3. **Regional Analysis and Inventory Management**
   - Explore regional trends and optimize inventory performance.
   - Visualizations: Choropleth maps, bar charts, and line charts.

---

## Tools and Technologies
- **Tableau**: Interactive dashboards and data visualizations.
- **MySQL**: Data preprocessing and cohort analysis.
- **Google Sheets**: Initial data cleaning and feature engineering.
- **GitHub**: Version control and project sharing.
- **Tableau Public**: Hosting the dashboard for public access.

---

## Datasets
The project uses four datasets:
1. **Supply_Chain_dataset**: Contains metrics like delivery times, risk statuses, and supplier information.  
   **Key Columns**: `Region`, `Supplier Name`, `SKU`, `Delivery Success Rate (%)`, `Risk Status`, `Revenue Generated`.

2. **Cohort_Analysis**: Aggregated dataset for cohort-based trends.  
   **Key Columns**: `Cohort`, `Total Orders`, `Total Revenue`.

3. **Calculate RFM Metrics**: Supplier-level data for Recency, Frequency, and Monetary analysis.  
   **Key Columns**: `Supplier Name`, `Recency`, `Frequency`, `Monetary`.

4. **Assign RFM Scores**: Segmentation dataset based on RFM scoring.  
   **Key Columns**: `Supplier Name`, `Recency_Score`, `Frequency_Score`, `Monetary_Score`.

---

## Insights and Recommendations
### Insights
1. **Delivery Trends**
   - Regions with higher delivery success rates can serve as benchmarks for underperforming areas.
   - Average shipping times and defect rates highlight inefficiencies in specific routes or suppliers.

2. **Supplier Performance**
   - Suppliers with high RFM scores contribute significantly to total revenue. They should be prioritized for partnerships.
   - Low-frequency or low-monetary suppliers could be reevaluated for potential replacement.

3. **Regional Analysis**
   - Regions with high stockout rates require better inventory management strategies.
   - Revenue trends by region can guide resource allocation and marketing efforts.

### Recommendations
1. Focus on improving shipping times and reducing defect rates by identifying root causes through supplier and regional analysis.
2. Strengthen relationships with high-performing suppliers based on RFM metrics while addressing issues with lower-performing ones.
3. Implement predictive analytics to manage stock levels and reduce stockout rates in underperforming regions.
4. Use delivery trend insights to optimize routes and streamline logistics operations.

---

## Visualizations
### Delivery Trends
- KPI Tiles: Total Orders, Average Delivery Time, Delivered vs. Delayed Orders.
- Line Chart: Delivery time trends by month and region.
- Funnel Chart: Orders Placed → Delivered → Delayed.
- Heatmap: Delivery times by region and supplier.
- Stacked Bar Chart: Success rates (on-time vs. delayed) by region.

### Supplier Performance
- Scatterplot: RFM metrics (Recency, Frequency, Monetary).
- Pie Chart: Supplier category distribution.
- Line Chart: Delivery trends over time by supplier cohorts.
- Heatmap: Supplier performance across regions.

### Regional Analysis and Inventory Management
- KPI Tiles: Total Regions, Fastest Delivery Region, Region with Most Delays.
- Choropleth Map: Delivery success rates by region.
- Bar Chart: Order quantity and revenue by region.
- Line Chart: Order volume trends by month.

---

## How to Use
1. **View the Dashboard**: Access the Tableau Public link below to explore the interactive dashboard.
2. **Clone the Repository**: Download the datasets and Tableau workbook for local use.
3. **Publish**: Open the Tableau workbook (`.twbx`) and connect it to the datasets.

---

## **How to Access the Dashboard**
The interactive dashboard is published on Tableau Public. [View Dashboard Here](https://public.tableau.com/views/SupplyChainAnalysis_17356428410530/RegionalAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Credits
- **Author**: *(Sourav Kumar Bhagat)*
- **Contact**: *(https://www.linkedin.com/in/souravkumarbhagat/)*

---

Feel free to explore, provide feedback, or contribute to the project!
