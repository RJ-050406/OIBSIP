# E-Commerce Sales Analysis(Task_1)

## Author
**Riddhima Jaiswal**

**Track:** Data Analytics  
**Organization:** Oasis Infobyte  
**Task:** E-Commerce Sales Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of an E-Commerce Sales dataset. The objective is to analyze customer demographics, product performance, revenue patterns, and sales trends to identify meaningful business insights and provide actionable recommendations.
The project was completed as part of the **Oasis Infobyte Data Analytics Internship**.

## Dataset Overview

The dataset contains e-commerce transaction records covering customer information, product details, pricing, quantity, revenue, shipping information, and order dates.
The dataset contains the following 12 columns:

| Column | Description |
|---|---|
| Customer ID | Unique identifier assigned to each customer |
| Gender | Gender of the customer |
| Region | Geographic region associated with the customer |
| Age | Age of the customer |
| Product Name | Name of the purchased product |
| Category | Category of the purchased product |
| Unit Price | Price of one unit of the product |
| Quantity | Number of units purchased |
| Total Price | Total value of the transaction |
| Shipping Fee | Shipping cost associated with the order |
| Shipping Status | Status of the shipment |
| Order Date | Date on which the order was placed |

## Objectives

The main objectives of this analysis are:

- Analyze customer demographics based on age and gender.
- Understand the distribution of customers across different age groups.
- Identify the top-selling products.
- Analyze revenue contribution by product category.
- Examine relationships between numerical variables.
- Analyze revenue across age groups and gender.
- Identify monthly sales trends.
- Analyze quarterly sales performance.
- Generate actionable business insights and recommendations.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preparation

The following data preparation steps were performed before analysis:

- Inspected the dataset structure and column information.
- Checked for missing values.
- Checked for duplicate records.
- Reviewed and corrected data types where required.
- Converted the `Age` column from float to integer.
- Converted `Order Date` into datetime format.
- Created age groups for customer segmentation.
- Created monthly sales summaries.
- Created quarterly sales summaries.
- Prepared grouped datasets for revenue and customer analysis.

## Descriptive Statistics

Descriptive statistical analysis was performed to understand the central tendency and distribution of the numerical variables.

The analysis included:
- Mean
- Median
- Mode
- Standard deviation
- Minimum value
- Maximum value
The following numerical variables were analyzed:
- Age
- Unit Price
- Quantity
- Total Price
- Shipping Fee
These statistics provide an overall understanding of customer age, product pricing, purchasing quantity, transaction values, and shipping costs.

## Exploratory Data Analysis

### 1. Monthly Sales Trend

Monthly sales were analyzed using a line chart to understand changes in sales performance throughout the year.
The analysis shows noticeable fluctuations in monthly sales, with **January and November showing particularly strong sales performance**, while March records comparatively lower sales.

### 2. Quarterly Sales Trend

Sales were grouped into four quarters to identify broader seasonal patterns.
The analysis shows that **Q4 records the highest quarterly sales**, while Q1 records the lowest quarterly sales performance.

### 3. Customer Age Group Distribution

Customers were divided into four age groups:
- 18–30
- 31–45
- 46–60
- 60+
The analysis shows that the **46–60 age group has the highest number of customers**, making it an important customer segment.

### 4. Gender Distribution

The customer base was analyzed by gender to understand the demographic composition of customers and identify differences in customer representation.

### 5. Top-Selling Products

Products were analyzed based on quantity sold to identify products with the highest customer demand.
The analysis helps identify high-demand products that may require closer inventory monitoring.

### 6. Revenue by Product Category

Total revenue was analyzed across product categories.
**Electronics** is the highest revenue-generating product category, indicating its significant contribution to overall sales.

### 7. Correlation Analysis

A correlation heatmap was created to examine relationships between numerical variables:
- Age
- Unit Price
- Quantity
- Total Price
- Shipping Fee
The analysis shows a strong positive correlation between **Unit Price and Total Price (0.824)**. This indicates that higher unit prices are strongly associated with higher transaction values.
Other variables show relatively weak correlations with Total Price.

### 8. Revenue by Age Group and Gender

Revenue was analyzed across different age groups and genders to identify high-value customer segments.
The **46–60 age group contributes the highest revenue**, while male customers contribute slightly higher revenue than female customers across the analyzed age groups.

## Outcome

The major findings from the analysis are:

- The **46–60 age group** has the highest customer representation.
- The **46–60 age group also generates the highest revenue**.
- Male customers contribute slightly higher revenue than female customers across the analyzed age groups.
- **Electronics** is the highest revenue-generating product category.
- **Monitor** is the top-selling product based on quantity sold.
- **Unit Price and Total Price have a strong positive correlation (0.824)**.
- Monthly sales show noticeable fluctuations throughout the year.
- **Q4 records the highest quarterly sales performance**.
- Customer demographics and seasonal sales patterns provide useful opportunities for targeted business strategies.

## Business Recommendations

### 1. Focus on the High-Value Customer Segment
The business should focus targeted marketing campaigns, personalized offers, and loyalty programs on customers aged **46–60**, as this segment has the highest customer representation and revenue contribution.

### 2. Strengthen the Electronics Category
Since Electronics generates the highest revenue, the business should prioritize product availability, promotional campaigns, product bundles, and cross-selling opportunities within this category.

### 3. Optimize Inventory for High-Demand Products
High-demand products such as **Monitors, Laptops, Keyboards, Smartphones, and Mice** should be monitored closely to maintain adequate inventory and reduce the risk of stock-outs.

### 4. Prepare for Seasonal Demand
Since **Q4 has the highest sales**, the business should increase inventory preparation, promotional campaigns, and marketing activities before the fourth quarter to maximize seasonal demand.

### 5. Use Customer Segmentation for Personalized Marketing
Age and gender insights can be used to develop more targeted marketing campaigns and personalized product recommendations based on customer segments and purchasing behavior.

