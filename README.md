# E-commerce-Sales-Dashboard
This project is an E-commerce dataset  which provide  insight into customer demographics, purchasing patterns, and user engagement.
## Project Overview
This is a synthetic dataset which simulates a large-scale e-commerce platform with 100,000 records. This dataset contains 100,000 rows with details on users, products, and transactions, as well as user engagement and transaction attributes. I’m going to be carrying out user behavior analysis, sales trends, and product performance looking at insight into customer demographics, purchasing patterns, and user engagement.
## Problem statement
Analyze user purchase behaviour to identify trends and patterns in product sales, total amount and customer demography over time . The goal is to understand which product generate the most revenue, the product with the highest review, how user purchase pattern vary by age range, transaction quantity and product pricing, the referral source that generate the most revenue.
## Data cleaning process
### Remove Duplicate:
I check for duplicate and remove them so as to ensure that the UserName are unique and not repeated. 
### Handing missing Value:
I applied filtered to each column of the dataset to check for blanks or missing value and discovered there was none.
### Checking for outliers and anomaly in the data:
using the scattered plot chart I use the age column to check if there are outliers but discovered there was none.
### Correct Data types:
I ensure all columns are of the correct data types. Where I have the TotalAmount I changed the data type from General to currency, and also use the appropriate data type for other columns with the wrong data types. 
### Mismatch of ProductName to Category:
I noticed there was mismatched on the Category column as against the ProductName. I used VLOOKUP to correct and match the ProductName with the right Category.
### Exploratory Data Analysis
The exploratory data analysis provides insight into customer demographics, most popular products, and sales distribution across various referral sources. It examines key customer characteristics such as age, gender, location, and income, identifying the primary segments to better focus their marketing strategies. The analysis also highlights the bestselling products, enabling businesses to optimize inventory and improve sales performance. 



