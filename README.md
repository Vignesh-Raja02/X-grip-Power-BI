# X-grip Sales Dashboard Project
**DashBoard Link**: https://app.powerbi.com/view?r=eyJrIjoiMzM0MThiNDYtNjFlZi00NTFjLTkwZDctN2Q4NGQ2YTU1OWNiIiwidCI6IjViZjM1ZTgxLWEzNDgtNDlhNS1iNTNmLWMyMjdjNTUxYjcyMyJ9

This dashboard is designed for "XGRIP - Next Gen Case Company" and showcases various performance metrics such as total revenue, profit, orders, return rate, and customer targets. It includes visual representations like line graphs, bar charts, radar charts, and pie charts to provide a clear and detailed overview of the company's performance over time and across different regions and platforms. Additionally, the dashboard features a product analysis page and a map section for better understanding of the data.
## Key Features

- **Integrated Diverse Data Sources**: Consolidated datasets from  MySQL (local), Excel, CSV, and PDF formats using Power Query for seamless analysis.
- **Standardized Multi-Currency Data**: Converted country-specific sales data to a unified USD currency using exchange rates, ensuring consistency in reporting.
- **Enhanced Profitability Analysis**: Merged datasets to incorporate Cost of Goods Sold (COGS) and discounts, enabling precise calculation of profit margins and key performance indicators (KPIs).
- **Designed Interactive Dashboards**: Developed multi-page dashboards with light/dark modes, incorporating slicers, custom panes, and in-depth product and return analysis.
- **Optimized User Experience**: Created a clean, user-friendly layout tailored to end-user requirements, utilizing map charts, product analysis visuals, and advanced DAX calculations.
- **Automated Data Refresh**: Configured Power BI gateway and scheduled data refresh to support continuous updates with new data streams.
- **Implemented Advanced Security**: Applied Row-Level Security (RLS) to ensure data accessibility compliance for different user roles.

## Technologies Used

- **Power BI**: For creating interactive dashboards and visualizations.
- **Power Query**: For data consolidation and transformation.
- **SQL**: For creating a local data base to connect with power bi.
- **Excel**: For initial data analysis and preparation.

## Dashboard Pages

### Dashboard
Provides an overview of key metrics:
- **Total Revenue**,**Total Profit**:,**Total Orders**:,**Return Rate**: (Generated using DAX measures and visualized as KPI)
- **Monthly Revenue vs. Target**: Line chart showing revenue trends from Jan 2023 to Oct 2024
- **Total Revenue by Country**: Bar chart showing revenue distribution across countries
- **Total Revenue by Region**: Radar chart showing revenue distribution across regions
- **Total Orders by Platform**: Pie chart showing order distribution across platforms
- **Total Customers vs. Target**: Gauge showing the number of customers against the target

### Map
Provides an interactive map showing the geographical distribution of orders and revenue.

### Products
- Gives over view of Orders and return count in gauge chart
- Total revenue by category
- Orders and return , Revenue and profit by category
- Highest selling and Highest returned products
- Martix to dispaly product wise orders,revenue, profit, and return rate.

### Darker Dashboard
Provides the same information as the main dashboard but with a darker color scheme for better visibility in low-light conditions.

## Outcomes

- Ensured consistency in multi-currency data reporting.
- Provided precise profitability analysis through comprehensive data integration.
- Enhanced user experience with interactive dashboards.
- Maintained data accuracy and integrity with automated data refresh processes.
- Ensured data security and compliance with advanced security measures.

**Snap Of DashBoard**
![image](https://github.com/user-attachments/assets/39bbae17-2b89-4986-8a83-9f45f03c8fed)

**Snap Of Products Page**


