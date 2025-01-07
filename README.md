# E-commerce-Sales-Dashboard
This project is an E-commerce dataset  which provide  insight into customer demographics, purchasing patterns, and user engagement.
## Project Overview
This is a synthetic dataset which simulates a large-scale e-commerce platform with 100,000 records. This dataset contains 100,000 rows with details on users, products, and transactions, as well as user engagement and transaction attributes. I’m going to be carrying out user behavior analysis, sales trends, and product performance looking at insight into customer demographics, purchasing patterns, and user engagement.
## Problem statement
Analyze user purchase behaviour to identify trends and patterns in product sales, total amount and customer demography over time . The goal is to understand which product generate the most revenue, the product with the highest review, how user purchase pattern vary by age range, transaction quantity and product pricing, the referral source that generate the most revenue.
## Data cleaning process
* Remove Duplicate:
I check for duplicate and remove them so as to ensure that the UserName are unique and not repeated. 
* Handing missing Value:
I filtered each column of the dataset to check for blanks or missing value and discovered there was none.
* Checking for outliers and anomaly in the data:
using the scattered plot chart I use the age column to check if there are outliers but discovered there was none.
* Correct Data types:
I ensure all columns are of the correct data types. Where I have the TotalAmount I changed the data type from General to currency, and also use the appropriate data type for other columns with the wrong data types. 
* Mismatch of ProductName to Category:
I noticed there was mismatched on the Category column as against the ProductName. I used VLOOKUP to correct and match the ProductName with the right Category.
## Exploratory Data Analysis
The exploratory data analysis provides insight into customer demographics, most popular products, and sales distribution across various referral sources. It examines key customer characteristics such as age, gender, location, and income, identifying the primary segments to better focus their marketing strategies. The analysis also highlights the bestselling products, enabling businesses to optimize inventory and improve sales performance. 
## Insight and Analysis
![E-commerce dBoard 1](https://github.com/user-attachments/assets/0b68dcd5-5bc2-44b3-8cc4-5b3dcd49ca6f)

The E-commerce sales dashboard provides a comprehensive view of business performance across the year 2021 and January 2022. Key insights derived from the data include the following:
Overall Performance: The company achieved $126 million in total revenues, selling 249,569 products through a total of 100,000 purchases. These figures reflect strong sales performance over the year.
* Top-performing Products: T-shirts, books, and smartphones are the top product that generate the highest revenue, whereas, Laptops, books, and t-shirts has the highest number of quantities sold. However, there is a visible drop in sales performance for Headphones and Smartphones, which could indicate areas needing attention.
* Sales Trends: Monthly revenue shows a steady growth followed by a drop in February, but the sales however reach its peak in December, which is likely driven by holiday shopping.
* Demographic Insights: Customer demographics are evenly split, with 34% female, 33% male, and 33% non-binary buyers, this balanced customer base highlights the company's inclusive market reach.
* Geographic Insights: Canada and USA contributed to the highest sales with the total amount of $15,880,191 and $15,878,050 respectively, followed by the UK, while countries like India and Germany show lower contributions, indicating opportunities for targeted campaigns to boost performance in these regions.
* Sales Channels: Referral sources such as ad campaigns and email marketing drive the most sales, outperforming organic search and social media.

![E-commerce dBoard 2](https://github.com/user-attachments/assets/9f881eec-0c9a-4cb6-8fe8-f381bc3cf335)

* Sales Distribution by Gender: Male and non-binary customers contributed similarly across most product categories, with a slight edge for males in smartphones and laptops whereas, female customers have consistently strong purchases across books and clothing.
* Sales by Age Range: The 44–56 age group generated the highest revenue, followed by 31–43. Younger age groups (18–30) show potential but lag behind which indicate a more targeted campaign among the younger age group.
* Device Preference: Mobile devices dominate customer purchases, followed by tablets and desktops, reflecting the growing preference for mobile shopping.
* Top-reviewed Products: T-shirts have the highest reviews, significantly outpacing other products like headphones and books.
* Product Sales by Age: Books and smartphones are evenly distributed across age groups, while laptops and shoes resonate more with younger and middle-aged demographics.
## Recommendation And Conclusion
* Target Marketing: Focus campaigns on the 44–56 age group, leveraging their high purchasing power, and create targeted ads for the 31–43 group by leveraging social media and influencer to reach them.
* Enhance Mobile Experience: Optimize the mobile shopping platform to retain its preference and explore additional features like personalized recommendations, prioritize mobile-friendly shopping experiences and optimize the website for mobile devices. Also consider developing a dedicated mobile app for enhanced user experience.
* Product Strategy: Offer discounts on high-demand categories (smartphones and books) and pair them with underperforming products to drive bundled sales. Consider introducing new product lines to cater to specific customer segment. Also focus on improving product quality customer experience so as to maintain high rating.
* Customer Reviews: Highlight positive reviews for T-shirts and encourage customers to leave feedback on other products to build credibility. Also, focus on improving product quality and customer experience to maintain high ratings.
* Referral and Loyalty Programs: Implement referral programs to encourage customer acquisition and retention. Also, we can offer loyalty rewards to incentivize repeat purchases and build brand loyalty.


