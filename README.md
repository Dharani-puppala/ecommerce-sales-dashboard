# E-commerce Sales Dashboard

## Project Objective
This E-commerce Sales Dashboard provides critical insights into business performance, customer behavior, and operational efficiency. 
By analyzing metrics such as revenue, profit, customer retention, and regional performance, stakeholders can identify growth opportunities, address inefficiencies, and enhance overall strategy.  

## Key Features

1. **Interactive Dashboard**:  
   - Track and analyze online sales data in real-time.  
   - Drill-down functionality for granular insights.  
   - Dynamic filters and slicers for user-driven exploration.  

2. **Data Preparation and Modeling**:  
   - Established connections and joined multiple tables to ensure a comprehensive dataset.  
   - Created new columns and performed calculations to manipulate data for analysis.  
   - Enabled user-driven parameters to enhance visualization flexibility.  

3. **Customized Visualizations**:  
   - Bar charts, pie charts, donut charts, clustered bar charts, and slicers for detailed representation.  
   - Conditional formatting to highlight trends and anomalies.  

4. **Complex Parameters**:  
   - Designed custom parameters to filter, drill down, and enable focused analysis across multiple dimensions like regions, time periods, and customer demographics.  

---

## Steps Followed

### **Data Preparation**
1. Imported datasets (`csv`, `xlsx`) into Power BI Desktop.  
2. Cleaned and transformed data:
   - Addressed missing or null values in key columns.  
   - Verified data quality using Power Query's column profiling tools.
3.Created connections between tables
   -![tables](https://github.com/user-attachments/assets/5b8ce762-2a14-4e76-b595-78d678c046ee)  
4. Created new calculated columns and DAX measures for analysis:  
   - **Total Revenue**: `SUM(Sales[Amount])`  
   - **Profit Margin**: `DIVIDE([Total Profit], [Total Revenue])`  
   - **Customer Segmentation**: Grouped by demographics, purchase frequency, and region.
   - **Average Order Value**: 'Details[Amount]/Details[Quantity]'

### **Dashboard Design**
1. Developed an intuitive layout to represent key metrics:  
   - **Profict Trends**: Visualized with Stacked column charts by month.
   - **Profict Trends over subcategory**: used Stacked bar chart.
   - **Customer Segmentation**: Represented with Stacked column charts.  
   - **Regional Performance**: Mapped through geo charts for visual impact in Stacked bar             chart.
   - **PaymentMode,Categorry Segmentation**: evaluted with quantity in donut chart.
2. Added slicers and filters for dynamic exploration:  
   - Filter by product category, region, time period, and customer type.  
   - Drill-down functionality for granular insights.  
3. Customized color schemes and formatting to improve readability and engagement.  

---

## Key Metrics

### **Financial Metrics**
 - **Total Revenue**: $438K
 - **Total Profit**: $37K 
 - **Total Quantity**: 5615 
 - **Total Average Order**: $121K
 - **Highest ordered month**: November

### **Category Metrics**
- **Highest Quantity Ordered**: 63%(Clothing)
- **Lowest Quantity Ordered**: 17%(Furniture)
- **Most Profited Sub-Category**:Printers($8606)

### **Customer Insights**
- **Total Customers**: 356  
- **Highest paid customer**: Harivansh($9902) 

### **Regional Insights**
- **Highest Revenue Region**: Maharashtra ($102K)  
- **Lowest Revenue Region**: Sikkim ($5276)  
  
### **Payemnt Mode**
- **Most Paid**: COD(44%) 
 
---

## Insights & Recommendations

1. **Revenue Growth**  
   - Prioritize marketing for top-selling categories like Electronics and Apparel.  
   - Increase promotions in regions with lower performance such as South America.  

2. **Customer Engagement**  
   - Enhance loyalty programs to improve the retention rate (currently 41.3%).  
   - Focus on converting first-time buyers to returning customers.  

3. **Operational Strategies**  
   - Optimize logistics to maintain an average delivery time of 3.2 days or lower.  
   - Continue improving order fulfillment rates (currently at 97.8%).  

4. **Future Opportunities**  
   - Explore untapped regions with potential growth.  
   - Develop targeted campaigns for age groups and demographics showing high engagement.  


