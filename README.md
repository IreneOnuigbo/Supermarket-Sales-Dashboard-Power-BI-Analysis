# Supermarket-Sales-Dashboard--Power-BI-Analysis


## Project Overview
This project analyzes supermarket sales data using Power BI to uncover insights across branches, product lines, customer types, time patterns, and payment methods. It includes a clean, interactive dashboard designed to help stakeholders understand sales performance and customer behavior at a glance. The dashboard was built with a modern pink theme, fully interactive slicers, and multiple custom visuals. 


## Table of Contents
- [Objectives](#objectives)
- [Goal](#goal)
- [Dataset Overview](#dataset-overview)
- [ Data Preparation](#data-preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Key Insights](#key-insights)
- [Power BI Dashboard Overview ](#power-bi-dashboard-overview )
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)


## Objectives  
1.**What is the total revenue and number of transactions?**  
2. **Which product lines generate the most sales?**  
3. **How do customer types behave across genders?**  
4. **Which branch performs best in terms of revenue?**  
5. **What are the peak hours and days for shopping?**  
6. **Which payment methods are most preferred?**       
7. **What is the average customer rating?**   



## Goal
The primary goal of this project was to analyze supermarket sales data to uncover business insights and customer behavior patterns. It focused on understanding sales performance across time, branches, and product lines, while identifying peak sales hours and top-performing product categories.

## Dataset Overview
**Source:**
 Kaggle ([Supermarket Sales Dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales))
   
The dataset, sourced from Kaggle, contains 1000 transactions, for a period of 3 months. Key Columns Used:
- Invoice ID 
- Branch
- Gender (Male/Female)
- Product Line
- Gender
- Customer Type
- Date
- Time
- Total
- Rating
- Payment Method



 ## Data Preparation  
- Loaded the dataset into **Power BI**  
- Verified and corrected column data types  
- Renamed and cleaned columns for clarity
- Replaced branch codes with full names
- Extracted Hour of Sale and Day of Week columns
- Added weekday sort column (DayOfWeekNum)
- Created 12-hour formatted Hour Label column using DAX


## Exploratory Data Analysis (EDA)
- Analyzed total revenue, transactions, average rating
- Grouped sales by product line, branch, customer type, and gender
- Examined sales patterns by hour and day of the week
- Assessed payment method usage across customer segments
- Used **slicers** dynamically break down data   


## Key Insights
- Sales peaked at 7 PM, indicating high evening traffic
- Female customers generated slightly more revenue than males
- Normal customers contributed more to total sales than members
- E-wallet was the most used payment method
- Yangon branch consistently led in revenue

##  Power BI Dashboard Overview  
The interactive dashboard is organized into three main insight areas:

**Sales Performance**
- Total Sales, Transactions, Avg. Rating.
- Daily Sales Trend

**Customer & Product Insights**
- Revenue by Branch, Customer Type by Gender
- Top Product Lines by Revenue
- Sales by Payment Method

**Time-Based Patterns**
- Sales by Hour of the Day, Sales by Day of the Week


## Recommendations
1.	Schedule promotions around 7 PM, the peak sales hour, to maximize revenue during high-traffic times.
2.	Convert high-spending normal customers into members by offering loyalty rewards or exclusive member benefits.
3.	Focus inventory and marketing on top-performing product lines, such as Food & Beverages and Fashion Accessories, to increase profitability.
4.	Encourage use of e-wallets through limited-time discounts or faster checkout perks, reinforcing the most preferred payment method.
5.	Engage female members more effectively, as female normal customers currently contribute more revenue. Indicating an opportunity to increase member spending through targeted offers or communication.



  



