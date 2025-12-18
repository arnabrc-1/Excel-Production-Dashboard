# Excel-Production-Dashboard
This project was created as part of my data analytics portfolio to demonstrate skills in data visualization, financial analysis, and storytelling through Excel dashboards.
# Overview
 This project analyzes production performance across regions, managers, and product categories using Microsoft Excel. It includes data cleaning, transformation, and dashboarding to generate business insights based on Units Produced, Cost, Region, and Manager demographics.
 
# Dataset Details
- Total historical production entries
- Fields include:
- Production Date
- Region
- Manager
- Product Type
- Units Produced
- Total Cost
- Age & Gender demographics Discount – Applied discount percentage

# Data Cleaning & Issue Fixing
- The raw dataset contained inconsistencies, including managers with multiple age values, which is a data quality issue since a person can have only one age.
  - Cleaning logic applied:
  - Sort data by Production Date (ascending)
  - For each manager, use the first available age value as the true age
  - Standardize age across all entries
  - Added new calculated fields to improve analysis
 
# Dashboard Features
- The Excel dashboard offers:
    - Units produced by product type
    -   Cost insights and trends
    -   Manager performance analytics
    -   Region-wise production summary
    -   Slicers for interactive filters (Region, Manager, Product Type)
      
# Insights
- Production varies significantly by region and manager
- Product categories show uneven volume and cost performance
- Demographics influence work allocation and efficiency levels

# Skills Demonstrated
- Pivot Tables & Pivot Charts
- Power Query
- Dashboard Design & Visualization
- KPI Development & Business Analysis
- Analytical Thinking & Attention to Detail

# Tools Used
- Microsoft Excel (Pivot Tables, Charts)
