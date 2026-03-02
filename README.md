### GitHub Project Description (Detailed & Structured)
📊 Customer Shopping Behavior Analysis

Tools: Python, SQL (PostgreSQL), Power BI
### Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories.
The main objective is to uncover insights into:

Spending patterns

Customer segmentation

Product preferences

Subscription behavior

These insights help guide strategic business decisions.

### Dataset Summary

Rows: 3,900

Columns: 18

Key Features

Customer Demographics

Age

Gender

Location

Subscription Status

Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size

Color

Shopping Behavior

Discount Applied

Promo Code Used

Previous Purchases

Frequency of Purchases

Review Rating

Shipping Type

Missing Data

37 missing values in the Review Rating column

### Exploratory Data Analysis Using Python

1️⃣ Data Loading

Imported the dataset using pandas.

2️⃣ Initial Exploration

Used df.info() to understand structure and data types.

Used df.describe() for summary statistics.

3️⃣ Missing Data Handling

Identified missing values in the Review Rating column.

Filled missing ratings using the median rating of each product category.

4️⃣ Column Standardization

Renamed columns to snake_case for better readability and documentation.

5️⃣ Feature Engineering

Created an age_group column from customer ages.

Created purchase_frequency_days to capture buying behavior.

6️⃣ Data Consistency Check

Checked redundancy between discount_applied and promo_code_used.

Dropped the promo_code_used column.

7️⃣ Database Integration

Connected Python to PostgreSQL.

Loaded the cleaned data for SQL analysis.

### Data Analysis Using SQL (PostgreSQL)

Key business questions answered using structured SQL queries:

Revenue by gender

High-spending customers who used discounts

Top 5 products by average review rating

Average purchase amount by shipping type

Subscriber vs non-subscriber spending comparison

Products most dependent on discounts

Customer segmentation (New, Returning, Loyal)

Top 3 products per category

Relationship between repeat buyers and subscriptions

Revenue contribution by age group

### Business Recommendations

1.Boost subscriptions by offering exclusive benefits

2.Introduce loyalty programs to convert repeat buyers into loyal customers

3.Review discount policy to balance sales growth and profit margins

4.Promote top-rated and best-selling products in campaigns

5.Target marketing toward high-revenue age groups and express shipping users


