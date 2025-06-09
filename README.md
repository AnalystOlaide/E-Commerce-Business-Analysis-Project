# E-Commerce-Business-Analysis-Project

## Project Overview

This Power BI dashboard provides a comprehensive analysis of an e-commerce business, uncovering insights on overall performance, customer demographics, product and category trends, marketing efficiency, sales channels, inventory management, and operational performance.

## Problem Statement

The business aims to better understand its customer behavior, product performance, and operational bottlenecks in order to drive growth, reduce churn, and improve profitability across all sales and marketing channels.

## Data Source

The dataset includes transactional, customer, product, inventory, and marketing performance data extracted from an e-commerce platform’s internal database.

## Data Structure

The data is organized across multiple tables:

* `Transactions`: Sales data including date, product ID, customer ID, revenue, and profit.
* `Customers`: Demographics including gender, age, marital status, income, education.
* `Products`: Product details including category, brand, and stock info.
* `Marketing`: Campaign performance data across channels.
* `Orders`: Operational data covering delivery status and fulfillment rates.

## Tool Used

* Microsoft Power BI (Desktop)

## Skills Applied

* Data Cleaning
* Data Modeling
* DAX Calculations
* Data Visualization
* Business Intelligence Storytelling
* Performance Metrics Interpretation

## Data Analysis Process

1. Data Cleaning using Power Query
2. Data Modeling by establishing relationships between tables
3. DAX Measures for calculating KPIs (YoY Growth, AOV, Churn Rate, etc.)
4. Dashboard Design with interactive visuals and slicers
5. Insight Extraction to inform business decisions

## Executive Summary

* Year-over-Year (YoY) Revenue and Transaction Growth: 33.4%
* Customer Growth: 7%
* Profit: \$3.57M | Average Order Value (AOV): \$248.61
* Churn Rate: 15% | 85.05% revenue from loyal customers
* High operational success: \~90% completed orders

## Insights
![image](https://github.com/user-attachments/assets/a0cd3fda-8987-4460-8026-1d2a1c1492a2)



 YoY Growth: Revenue & transactions grew by 33.4%; customer base by 7%

Customer Retention: 85% of revenue came from loyal (non-churned) customers

Category Trends:

Electronics lead in revenue but fluctuate

Apparel shows rapid growth from a low base

Beauty is second highest but unstable

Top Product: Sportswear (Apparel) is the highest-grossing item

High-Revenue States: Texas, Nevada, Colorado, South Dakota, Minnesota, Kentucky, Maine, New Jersey
![image](https://github.com/user-attachments/assets/ccb267aa-2992-4b9c-a8ea-8bbb580976e0)

The company recorded a $3.57M profit, with an average order value of $248.61 and a low churn rate of 0.15, indicating strong customer retention. Operationally, 89.99% of orders were completed, 8.05% failed, and 1.96% were processing, reflecting high fulfillment efficiency.

Electronics led in revenue and profit but showed fluctuations. Beauty, second in profit, also fluctuated, while Apparel, though lowest in revenue, grew exponentially. Subcategory-wise, Sportswear topped profits significantly, followed by Makeup, Bath & Body, Smartphones, Televisions, and Appliances. Oral Care had the lowest profit.

In terms of demographics, the 31–50 age group generated the most revenue, followed by 51–80, while 18–30 contributed the least. For discount impact, low discounts drove the highest revenue and profit, followed by mid discounts. High and no discounts had minimal impact on both revenue and profit.
![image](https://github.com/user-attachments/assets/4b9261ed-6df4-46c9-8d16-4b0686a0c6f8)
Loyalty is strongest among the Middle and Lower-Middle income groups, making them key segments for retention and growth. The Married demographic dominates the loyal customer base, followed by Singles, suggesting that relationship status influences loyalty. Across age groups, loyalty distribution between genders is nearly equal, showing no gender-based bias.

Churn analysis reveals that gender is not a major churn factor, with nearly identical churn rates for males (0.151) and females (0.146). However, age and income levels do play a role. The 31–50 age group churns the most, followed by 18–30, while 51–80 shows the least churn—despite being a strong revenue contributor. The Upper-Middle income group has the highest churn, even though they’re not the most loyal.

![image](https://github.com/user-attachments/assets/925b421f-0a3c-4fa9-9a98-1c3f88674524)
Males aged 31–50 emerge as the most loyal segment, consistently engaging with the brand and contributing significantly to repeat purchases.

When it comes to performance by channel, the Online store dominates, generating the highest revenue and profit—a clear indicator of strong digital engagement and efficient online operations.

In terms of product performance, Electronics stands out as the top-performing category, leading in both revenue and profitability, signaling a strong demand and healthy margins in this segment.

Colorado takes the lead as the state with the highest number of customers, making it a key geographic area for continued marketing and service delivery focus.

![image](https://github.com/user-attachments/assets/e11b8b05-82b1-4c7f-a367-35859904c5dc)

Email marketing leads across all metrics—highest spend (~9M), most clicks (~10M), and top conversions (200K+)—making it the most impactful channel.

Social Media follows closely with ~6M spend, 7.5M clicks, and ~150K conversions, showing strong efficiency.

TV ads see moderate investment (~3.5M) but lower engagement and conversions, suggesting weaker ROI.

Billboards, with the lowest spend (~1.5M), yield the fewest clicks (~2.5M) and conversions (~50K), indicating minimal performance impact.

![image](https://github.com/user-attachments/assets/7dbaf99c-e0b0-4153-add2-001c5fe8e444)












### 1. Business Performance

* Strong YoY growth in both revenue and transactions
* Slower growth in customer acquisition compared to sales

### 2. Inventory Issues

* High manual adjustments and stockouts for key products:

  * Anderson-Wagner Organizer
  * Nelson Doll Score210
  * Li-Evans Yarn Skein
  * Miller Feeder

### 3. Customer Demographics

* Gender split is even, but females show greater loyalty
* Married and single customers drive most of the revenue
* Middle and lower-middle income groups dominate

### 4. Product & Category Trends

* Electronics leads in profitability
* Apparel generates the most revenue across channels
* Top products include Maybelline, Dove, Adidas, and Samsung

### 5. Sales Channel Performance

* Mobile App most profitable for Electronics
* Online best for Beauty
* Retail Stores best for Apparel
* Marketplace has the lowest profit contribution

### 6. Marketing Campaigns

* Email and Social Media dominate in conversions
* TV and Billboard underperform in direct response

### 7. Operations & Fulfillment

* 90%+ order completion and delivery success
* Low returns and failure rates
* Pending and processing orders need active monitoring

## Deep Dive

Explore the Power BI dashboard to:

* Filter by demographic segments
* Track churn trends across age and gender
* Identify operational inefficiencies
* Compare category profitability across channels
* Evaluate marketing channel effectiveness

## Recommendations

1. Investigate inventory issues for top-affected products.
2. Enhance retention strategies targeting high-churn segments (males, 18-50 age group).
3. Focus marketing on loyal demographic groups (middle income, married/single).
4. Optimize channel-specific strategies per product category.
5. Scale digital marketing efforts; re-evaluate TV/Billboard ROI.
6. Monitor delivery and processing bottlenecks.

## Conclusion

This analysis empowers stakeholders with critical insights to make data-driven decisions across marketing, inventory, customer experience, and fulfillment. The Power BI dashboard delivers real-time, actionable intelligence to guide business growth and optimization.

## How to Use This Project

* Download the `.pbix` file or access the published report (if hosted online).
* Open in Power BI Desktop to explore interactive visuals.
* Use slicers and filters to customize insights by demographics, product categories, and channels.
* Refer to the Executive Summary and Recommendations sections for key takeaways.

## Project Assets

* `Ecommerce_Analysis.pbix` – Power BI Dashboard File
* Screenshots – Key dashboard visuals
* Data Dictionary – Table and field descriptions (optional)

