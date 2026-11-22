# Excel---Ecommerce-Sales-Analytics-Dashboard
# Ecommerce Sales Analysis Dashboard (Excel)

An interactive Excel dashboard analyzing four years of US retail sales data (2011–2014). The project explores sales, profit, quantity, order volume, and profit margins across different time periods, product categories, sub-categories, regions, and states.

## **Project Objective**

The objective of this project was to develop an interactive sales analytics dashboard in Excel, practice data analysis and visualization techniques, and translate raw retail data into actionable business insights.

## **Dashboard Preview**

<!-- Add your dashboard screenshot here -->
![Ecommerce Sales Dashboard](dashboard-preview.png)

## **Project Overview**

The `Ecommerce_Sales_Analysis.xlsx` workbook contains two versions of the dashboard, both built using the same underlying dataset:

- **Pivot Table Dashboard:** Built using Pivot Tables and Pivot Charts.
- **Formula-Driven Dashboard:** Recreated using Excel formulas, with interactive dropdown filters for Year, Region, and Segment.

## **Workbook Structure**

| Worksheet | Description |
|:---|:---|
| `Data` | Raw dataset containing 9,994 rows and 22 columns, including order details, customers, locations, products, sales, quantity, discounts, and profit. |
| `combo chart`, `waterfall chart`, `pie chart`, `map chart`, `top 5 categories`, `KPI`, `KPI YoY` | Supporting Pivot Tables and Pivot Charts used to build the dashboard. |
| `layout` | Background layout used for the dashboard design. |
| `dashboard` | Final Pivot Table dashboard featuring KPI cards and interactive visualizations. |

## **Dashboard Features**

### **Key Performance Indicators (KPIs)**

- Total Sales
- Total Profit
- Total Quantity Sold
- Number of Orders
- Profit Margin
- Monthly trends and Year-over-Year (YoY) growth

### **Sales & Profit Analysis**

- Monthly sales and profit trends
- Category-wise profit breakdown using a waterfall chart
- Category-wise sales distribution using a doughnut chart
- US state-level sales visualization using a map chart
- Top 5 sub-categories ranked by sales

### **Interactive Filters**

The formula-driven dashboard includes three dropdown filters:

- Year
- Region
- Segment

All KPIs and charts dynamically update based on the selected filters.

## **Key Business Insights**

The following findings are based on the complete dataset across all years and regions.

### **Overall Performance**

| Metric | Result |
|:---|---:|
| Total Sales | $2.30M |
| Total Profit | $286.4K |
| Total Quantity | 37,873 |
| Total Orders | 5,009 |
| Profit Margin | 12.47% |

### **Sales & Profit Trends**

- Sales declined by 2.8% in 2012.
- Sales recovered with 29.3% growth in 2013.
- Sales increased another 20.6% in 2014.
- Profit grew by 14.4% in 2014, while profit margin declined slightly from approximately 13.4% to 12.7%.

### **Category Performance**

- Technology generated approximately $145.5K in profit.
- Office Supplies generated approximately $122.5K in profit.
- Both categories maintained profit margins of approximately 17%.
- Furniture generated only $18.5K in profit, despite having sales comparable to Office Supplies, with a significantly lower profit margin of 2.5%.

### **Loss-Making Products**

- Tables generated approximately $207K in sales but resulted in a loss of $17.7K.
- Bookcases and Supplies also recorded negative profits.

### **Top-Performing Sub-Categories**

- Phones: $330.0K in sales.
- Chairs: $328.4K in sales.

### **Regional Performance**

- West generated the highest sales at approximately $725.5K and achieved the strongest profit margin at 14.9%.
- Central recorded the weakest profit margin at 7.9%.

### **State-Level Performance**

- California generated approximately $457.7K in sales.
- New York generated approximately $310.9K in sales.
- Together, these two states accounted for roughly one-third of total sales.

## **Tools & Techniques**

**Tools Used:**

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Excel Formulas
- Conditional Formatting
- Data Visualization
- Interactive Dropdown Filters

**Analytical Techniques:**

- Year-over-Year (YoY) Growth Analysis
- Monthly Sales & Profit Trend Analysis
- Profit Margin Analysis
- Category & Sub-Category Performance Analysis
- Regional & State-Level Analysis
- KPI Reporting

**Note:** YoY growth calculations compare the selected year against the preceding year. The dashboard's functionality and formatting are best experienced in the desktop version of Microsoft Excel.

---
