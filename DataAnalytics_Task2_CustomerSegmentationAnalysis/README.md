# Customer Segmentation Analysis (Task_2)

## Objective
The objective of this project is to analyze customer data and divide customers into meaningful groups based on their characteristics and purchasing behaviour. The analysis aims to identify distinct customer segments that can help businesses understand their customers better, target the right customer groups, and make data-driven marketing and business decisions.

## Dataset
The **Online Retail Sales Dataset** was used for this analysis. It contains transaction-level information related to online retail purchases, which was processed to understand individual customer purchasing behaviour and calculate RFM metrics.

## Steps Performed
### 1. Data Loading and Exploration
The customer dataset was loaded and its structure, dimensions, data types, and basic statistics were examined to understand the available information.

### 2. Data Cleaning and Preprocessing
The dataset was checked for missing values, duplicate records, and data inconsistencies. The required preprocessing was performed to prepare the data for further analysis.

### 3. Exploratory Data Analysis
Customer characteristics and purchasing behaviour were explored using statistical analysis and visualizations to identify patterns and relationships within the data.

### 4. Feature Selection
Relevant customer attributes were selected for segmentation so that the clustering process could focus on meaningful customer characteristics.

### 5. Data Scaling
The selected numerical features were scaled to ensure that variables with different ranges contributed appropriately to the clustering process.

### 6. Customer Segmentation
A clustering technique was applied to group customers with similar characteristics and purchasing behaviour into distinct segments.

### 7. Segment Analysis and Visualization
The identified customer groups were analyzed and visualized to understand the characteristics and behaviour of each segment.

### 8. Business Insights
The customer segments were interpreted from a business perspective to identify opportunities for targeted marketing, personalized offers, customer retention, and improved customer engagement.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Outcome
- The analysis identified 4,338 unique customers for RFM-based segmentation.
- Customers were segmented into 3 distinct groups using K-Means clustering.
- Cluster 0 represents customers who are relatively inactive and require re-engagement strategies.
- Cluster 1 represents the largest group of active and regular customers who can be targeted through loyalty, cross-selling, and upselling strategies.
- Cluster 2 represents a small group of highly valuable and frequent customers.
- These high-value customers can be retained through VIP benefits, exclusive offers, and personalized experiences.
- The segmentation provides a clear understanding of different customer purchasing behaviors.
- The results can help businesses design targeted marketing strategies, improve customer retention, and focus resources on high-value customers.

Overall, the project demonstrates how customer data can be transformed into actionable segments and business insights using Python and machine learning techniques.
