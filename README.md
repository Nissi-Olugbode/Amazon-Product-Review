# Amazon-Product-Review
This is an excel project done as part of my final assessment for the Data Analysis course for Data Skillup Africa by The Incubator Hub. A data analysis project using excel for e-commerce analysis to guide product improvement, marketing strategies and customer engagement.
## Project Topic: Amazon Product Review Analysis
### Project Overview
This project focuses on deriving actionable insights from Amazon product and customer review data. The goal is to support business decisions related to product development, marketing, and customer engagement by uncovering trends and patterns from the data.
### Data Source
The dataset was scraped from Amazon product pages and contains information on:
Product details: name, category, price, discount, ratings
Customer engagement: review titles and content
Each row represents a unique product with aggregated review data stored in comma-separated format
Total Records: 1,465
Total Fields: 16 columns
### Objectives
- Identifying average discount percentages by category
- Determining the number of products per category
- Analyzing total and average reviews by category
- Highlighting top-rated and most-reviewed products
- Comparing actual vs. discounted prices across categories
- Examining rating distribution and how it correlates with discounts
- Estimating potential revenue by category
- Categorizing products based on price ranges and review counts
- Ranking the top 5 products based on combined ratings and review volume

### Tools used
- Microsoft Excel (for data cleaning, transformation, pivot tables, and dashboard creation)
- Excel Charts & PivotTables (for visual analytics)

### MS Excel cleaning
1. Removed duplicate records
2. Filled in null cells with numerical value "0"
3. Splitted the category column to 5 different colums uning a delimeter
4. Split and normalized comma-separated values in key columns
5. Converted price and discount fields to numeric data types
6. Extracted review counts and parsed text fields
7. Handled outliers in price and discount percentages
8. Created calculated columns for metrics like potential revenue and price range buckets
   
### Exloratory Data Analysis
Using Excel PivotTables and formulas, the following analyses were performed:
- Calculated average discounts and prices by category
- Aggregated total reviews and unique product counts
- Created discount Ranges (e.g 10-20%, 30-30%)
- Segmented products by discount thresholds (e.g., ≥50%)
- Bucketed products into price ranges (e.g $1000-2000)
- Computed total potential revenue as (actual_price × rating_count)
- Investigated correlation between discount level and rating
- calculated a column in terms of rating and number of reviews combined.
  
### Excel Dashboard
An interactive Excel dashboard was created to summarize and visualize the findings:
- Slicers and filters for dynamic analysis by category and price range
- Bar and pie charts showing product distribution, discounts, and ratings
- KPI cards displaying average prices, total reviews, and top-rated products
- PivotTable summaries for quick lookup and comparison
- Highlight visuals for top 5 performing products by rating and reviews
  
### Insights
- Certain categories consistently offer higher discounts (≥50%)
- High product ratings do not always correlate with high review counts
- Products priced between ₹200–₹500 dominate in both count and revenue potential
- A significant number of products have fewer than 1,000 reviews, indicating room for growth
- Top 5 products were identified based on a combined metric of rating and review count
- Revenue potential is highest in categories with both moderate pricing and high engagement
