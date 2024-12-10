# AdventureWorks-Bike-Shop-Analysis
### Project Overview
This project focuses on analyzing sales, customer behavior, product returns, and geographical trends for the AdventureWorks Bike Shop. The analysis, carried out in Power BI, leverages a multi-dimensional dataset to build an interactive dashboard that provides comprehensive insights into business performance. With eight interrelated tables, the project required rigorous data cleaning, modeling, and visualization to deliver actionable results.
### View the Report:
You can view the live Power BI report here: [View the Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTUyZTM1NDgtNDM3ZC00MDIxLTgyYjctZTU2ZTY0MDUzY2ExIiwidCI6ImRmOTI5NDEzLWVjNjQtNDQyMS1hYjIzLTUyNWZmNGY2ZTRhYyIsImMiOjEwfQ%3D%3D)
### Objectives
- Understand sales performance across regions, products, and time periods.
- Analyze product return trends and identify areas for improvement.
- Segment customers to discover valuable patterns in purchasing behavior.
- Enable data-driven decisions through intuitive visualizations.
### Dataset Details
- The dataset consists of the following tables:
- Calendar Lookup: Dates and time-based attributes for temporal analysis.
- Customer Lookup: Demographics and other customer information.
- Fact Sales: Detailed sales transactions.
- Fact Return: Product returns and related details.
- Product Lookup: Individual product information.
- Product Category: Broader product groupings.
- Product Subcategory: More granular product classifications.
- Territory Lookup: Geographic regions for sales and returns
### Tools and Technologies
- Power BI: For data cleaning, modeling, and dashboard creation.
- Excel/CSV Files: Used as the primary data source for import and processing.
### Process Overview
1. Data Cleaning

- Removed duplicate records and inconsistencies in key fields (e.g., CustomerID, ProductID).
- Standardized date formats using the Calendar Lookup table.
- Addressed missing values by applying appropriate imputation techniques.
3. Data Modeling
  
- Designed a star schema with Fact Sales and Fact Return as the core tables, connected to lookup tables via unique identifiers.
- Optimized relationships between tables to enhance query performance in Power BI.
- Created calculated columns and measures for metrics like revenue, return rate, and sales growth.
4. Visualizations
  
- Built an interactive Power BI dashboard with the following key features:
- Sales Overview: Yearly, quarterly, and monthly trends with a focus on top-performing products and regions.
- Returns Dashboard: Return analysis by product categories, subcategories, and regions.
- Customer Analytics: Insights into customer demographics and purchasing behavior.
- Territory Analysis: Regional breakdown of sales and returns.
5. Metrics and KPIs
  
- Total Revenue and Return Amount
- Average Sales per Customer
- Return Rate (%) per Product Category
- Sales Growth (%) Year-over-Year
### Key Findings  

- Sales were concentrated during certain seasons, reflecting a potential for targeted marketing campaigns.
- A few product subcategories accounted for the majority of returns, indicating possible quality or fit issues.
- High-performing territories highlighted growth opportunities in underperforming regions.
### Project Deliverables  
- Power BI Dashboard: AdventureWorks_BikeShop.pbix file
- Sample Dataset: A processed and anonymized version of the AdventureWorks data.
- Documentation: Includes methodology, data model design, and analytical findings.
### Next Steps  

- Integrate machine learning to predict customer churn and product return likelihood.
- bAutomate data refresh using Power BI service for up-to-date analytics.
- Expand customer segmentation with advanced clustering techniques.
### Acknowledgments   

Grateful to AdventureWorks for providing the dataset and fostering opportunities for real-world analytical exploration.

