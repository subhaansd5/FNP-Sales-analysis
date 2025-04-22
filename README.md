# Project Background
This project was undertaken as a portfolio piece to showcase my data analysis and dashboard creation skills using Microsoft Excel. 
I chose to analyze publicly available (or simulated) sales data from Ferns and Petals, a well-known online gifting company, to demonstrate the ability to extract meaningful insights and present them in a clear, interactive format. 
The dashboard aims to provide a comprehensive overview of sales performance across various dimensions relevant to an e-commerce business.

Insights and recommendations are provided on the following key areas:

- **Revenue Trends Analysis:** Evaluation of historical sales and revenue patterns accross occasions and timelines. Analyzed order volume and average order value across month. Key metrics includes: Total revenue, total customers, Avereage order value and total orders.
- **Product Level Performance:** Analyzed the product performance according to the revenue, revenue contributions of the of the different categories and order times of the top performing products. Evaluated the top and bottom 5 products.
-**Customer Behaviour:** analyzed the buying behaviour of customers, specially differences of buying behviour between male and female customers. analyzed the buying behaviour of the top 5 customers from all and top 5 each from different gender across different occasion and timeline.

An interactive Excel dashboard can be downloaded [here.]([FNP Data analysis apr.xlsx](https://github.com/subhaansd5/FNP-Sales-analysis/raw/main/FNP%20Data%20analysis%20apr.xlsx)

Please refer the following link for Data. [Datasets.](https://github.com/subhaansd5/FNP-Sales-analysis/tree/bda27816c761af9220e035676c3668f8a66a33da/Data)

# Data Structure & Initial Checks

FNP's database structure as seen below consists of three tables: orders, customers, and products, with a total row count of 1000 order records.

![FNP's ERD](https://github.com/subhaansd5/FNP-Sales-analysis/blob/56cb605f2cc462077aac926127b2b65b37ed623b/Data%20Structure.png)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets. 
The power query and DAX queries utilized to inspect, perform quality checks. Data cleaning, transformation and creation of calculated columns and calculated measures has been done using DAX and power query.

#   Executive Summary

###   Overview of Findings

A total revenue of ₹ 35,20,984 was generated from 1,000 orders fulfilled in 2023, with an average order value of ₹ 3,520.98. Seasonal events significantly influenced sales, with anniversaries contributing ₹ 6,74,634 from 205 orders, and Raksha Bandhan generating ₹ 6,31,585 from 132 orders. Product category performance was concentrated, with "colors" leading revenue generation at ₹ 3,32,798. The average spending per customer was ₹ 3,520.

Below is an overview page from the Excel dashboard, and more detailed examples are included throughout this report. The interactive dashboard can be downloaded [here.](https://github.com/subhaansd5/FNP-Sales-analysis/blob/4653f0dc7d7f49b1b2ea55971812f5897328f1c2/Dashboard.xlsx)

###   Sales Trends:

* Revenue peaked in February and August, exceeding ₹ 14,00,000 in each month. This aligns with the timing of Holi/Valentine's Day (February) and Raksha Bandhan (August), indicating a strong correlation between revenue and these occasions.
* Revenue was lower from April to July and in September, October, and December, periods with fewer major religious occasions, suggesting seasonality impacts sales.

![Sales Trends](https://github.com/subhaansd5/FNP-Sales-analysis/blob/a9e19560b514a9c1778c49bbe6f089efde5121fe/Revenue%20Analysis.png)

###   Product Performance:

* Three product categories—colors, soft toys, and sweets—accounted for 71% of the company's revenue, generating over ₹ 24,50,000 in 2023, highlighting the concentration of revenue in a few key categories.
* Within the plants category, the "cumgift" product underperformed, contributing only ₹ 7,714 in total revenue for 2023, indicating a potential area for review.
* Several individual products, including "Magnam set," "Quia gift," "dolores gift," and "Harum pack," each generated revenue exceeding ₹ 100,000, demonstrating strong individual product performance. 

![Product Performance](https://github.com/subhaansd5/FNP-Sales-analysis/blob/a9e19560b514a9c1778c49bbe6f089efde5121fe/Product%20Performance.png)

###   Customer Behavior Analysis:

* Revenue, orders, and average spending are distributed nearly equally between female and male customers, suggesting a balanced customer base.
* Dhanbad, Imphal, and Kavali each generated more than 25 orders, identifying these cities as key markets for order volume.
* Kavali shows a notable gender disparity, with female customers generating over ₹ 100,000 in revenue and male customers contributing no revenue. Conversely, Machilipuram, Bhatpara, and Agra show the opposite trend, with male customers generating over ₹ 60,000 in revenue each and no revenue from female customers, highlighting significant regional and gender-based differences in spending patterns.

![Customer Behaviour analysis](https://github.com/subhaansd5/FNP-Sales-analysis/blob/a9e19560b514a9c1778c49bbe6f089efde5121fe/Customer%20Behaviour.png)






