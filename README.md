# Shopping Data Analysis Project




📊 Project Overview
This project analyzes customer shopping behavior using a comprehensive dataset of 3,900 customer transactions. The analysis focuses on understanding purchase patterns, customer demographics, and identifying data quality issues through exploratory data analysis and outlier detection.
🎯 Objectives

Data Quality Assessment: Identify and handle missing values, duplicates, and outliers
Customer Behavior Analysis: Understand purchasing patterns across different demographics
Outlier Detection: Use statistical methods to identify unusual transactions
Data Preprocessing: Clean and prepare data for further analysis or modeling

📋 Dataset Description
The dataset contains 3,900 records with 18 features:
Numerical Variables

Age: Customer age (int64)
Purchase Amount (USD): Transaction amount in USD (int64)
Review Rating: Product rating (float64, scale 1-5)
Previous Purchases: Number of previous purchases (int64)

Categorical Variables

Gender: Customer gender
Item Purchased: Specific item bought
Category: Product category
Location: Customer location
Size: Product size
Color: Product color
Season: Purchase season
Subscription Status: Customer subscription status
Payment Method: Payment method used
Shipping Type: Shipping option selected
Discount Applied: Whether discount was applied
Promo Code Used: Whether promo code was used
Preferred Payment Method: Customer's preferred payment method
Frequency of Purchases: How often customer purchases

🛠️ Technologies Used

Python 3.x
pandas: Data manipulation and analysis
numpy: Numerical computations
matplotlib: Data visualization
seaborn: Statistical data visualization
jupyter notebook: Interactive development environment



🚀 Getting Started
Prerequisites
bashpip install pandas numpy matplotlib seaborn jupyter
Installation

Launch Jupyter Notebook:

bashjupyter notebook
📈 Analysis Workflow
1. Data Exploration

Load and inspect the dataset structure
Check data types and missing values
Generate basic statistical summaries
Examine unique values in categorical columns

2. Outlier Detection

Box Plot Analysis: Visual identification of outliers in numerical variables
IQR Method: Statistical outlier detection using Interquartile Range
Outlier Impact Assessment: Evaluate the effect of outliers on analysis

3. Data Preprocessing

Missing Value Treatment: Handle any missing data points
Outlier Treatment: Remove or transform outliers based on business logic
Feature Engineering: Create new relevant features if needed
Data Type Optimization: Ensure appropriate data types for analysis

4. Visualization

Distribution plots for numerical variables
Count plots for categorical variables
Correlation analysis between variables
Customer segmentation visualizations

🔍 Key Findings
Data Quality

✅ Complete Dataset: No missing values across all 18 variables
✅ Consistent Data Types: Appropriate data types for all columns
⚠️ Outliers Detected: Statistical outliers identified in purchase amounts and other numerical variables

Customer Insights

Age Distribution: Customer age ranges and concentration points
Purchase Patterns: Seasonal trends and category preferences
Payment Preferences: Most common payment methods and shipping types
Review Patterns: Distribution of customer satisfaction ratings

📊 Outlier Analysis Results
Using the IQR (Interquartile Range) method:

Age: X% outliers detected
Purchase Amount: X% outliers detected
Review Rating: X% outliers detected
Previous Purchases: X% outliers detected

🧹 Data Cleaning Process

Outlier Treatment:

Applied IQR method with 1.5 × IQR rule
Removed extreme outliers that could skew analysis


Column Optimization:

Removed redundant columns (e.g., duplicate payment method fields)
Kept essential variables for analysis


Data Export:

Cleaned dataset saved as cleaned_shopping_data.csv
Maintained data integrity and relationships
