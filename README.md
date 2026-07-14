# FMCG-Sales-Inventory-Analytics-Dashboard
This is an End-to-end FMCG sales and inventory analytics project using SQL and Power BI to uncover sales trends, promotion effectiveness, pricing insights, and stockout risks

**Executive Summary ** 
This project analyzes three years of FMCG sales data to uncover trends in sales performance, country purchasing behavior, inventory management, holidays, weekends, and promotional effectiveness. I used SQL for data exploration and Power BI for visualization. The dashboard provides actionable insights that support strategic business decisions related to sales growth, inventory management, and regional performance.

**Business Problem**
FMCG companies generate large volumes of sales data from multiple cities, countries, products, suppliers, and sales channels. I was answering the following business questions.
Problem Statement
1.	Total units sold by month
2.	Units sold by channel
3.	Daily trends
4.	Percentage category sold by net sales
5.	Year where most units were sold
6.	Total units sold by category
7.	Sales by country, city, and average discount
8.	Do countries affect the price sold, the same brand but sold at different prices in a different country?
9.	Are there sku that sell at specific times or seasons?
10.	Do promotions, holidays, and weekends drive higher sales?
11.	Which brands generate high revenue despite offering low discounts?
12.	Which products have low stock but high demand?
13.	What is the average discount percentage?
14.	Which products benefit the most from promotions?
15.	Does heavy discounting reduce profit margins?
16.	Stockout incidents trend
17.	Channels by stock out
18.	Potential lost sales due to stockouts

** Methodology**
1. I cleaned and prepared the FMCG sales dataset for analysis.
2. Explored the data using SQL to answer key business questions and identify trends.
3. Built an optimized data model in Power BI.
4. Created DAX measures and interactive visualizations to monitor sales, 5. inventory, promotions, and regional performance.
6. Interpreted the results to generate actionable business insights and recommendations

**Skills Used **
SQL
1. Data exploration
2. Aggregate functions
3. Date
4. CASE statements
4. GROUP BY
5. Data filtering

POWER BI
1. Data modeling
2. DAX measures
3. Time intelligence
4. Interactive dashboards
5. KPI design
6. Maps

**RESULTS**
**Executive Dashboard Results**
1. How is the business performing overall between 2021 and 2023?
  1. The gross sales for three years were 484.7M
  2. Net sales totaled 472.9M
  3. The FMCG company sold a total of 65.1 M units
**Business Impact**
The business achieved strong sales over the three years, with Hypermarkets serving as the primary revenue channel. This indicates that maintaining strong relationships with large retail partners is critical for sustained growth

**Recommendation**
Increase investment in Hypermarket partnerships, negotiate additional shelf space, and launch exclusive promotions through this channel to maximize revenue.

2. When do customers purchase the most products?
   1. July and December recorded the highest sales volumes.
   2. Weekends outperformed weekdays.
   3. Holidays generated more sales than normal days
**Business Impact**
Sales follow clear seasonal patterns. If inventory is not increased before peak periods, the company risks losing revenue due to stock shortages

**Recommendation**
Increase production and inventory before July and December, and plan marketing campaigns around weekends and holiday periods to maximize sales

3. Which markets contribute the most to sales?
   1. Italy generated the highest net sales.
   2. Italy sold the most units.
   3. Berlin recorded the highest unit sales among cities
**Business Impact**
Italy is the company's strongest-performing market and presents opportunities for further investment and expansion
**Recommendation**
Allocate additional marketing resources to Italy while investigating why lower-performing countries are underperforming
4. Are products priced consistently across different countries?
   1. The same brands were sold at different average prices across countries.
   2. Austria had the highest average prices.
   3.BrandE had the lowest average selling price
**Business Impact**
Pricing inconsistencies may affect competitiveness and profitability across markets
**Recommendation**
Review pricing strategies by country to ensure they align with local market conditions and overall business objectives
5. Where are inventory shortages affecting sales?
   1.BrandD experienced the highest stockout incidents.
   2. Beverage products had the most stockouts.
   3. May recorded the highest number of stockout incidents.
   4. Italy had the highest potential revenue loss due to stockouts
**Business Impact**
Frequent stockouts of high-demand products can lead to lost sales, reduced customer satisfaction, and missed revenue opportunities

**Recommendation**
Improve demand forecasting and inventory replenishment for BrandD and Beverage products, particularly before May and in high-demand markets like Italy

**LIMITATIONS**
1. Stockout analysis assumes the provided inventory data is accurate
2. External factors, such as competitor pricing, were not included
3. Promotional effectiveness cannot fully establish causation without experimental data.

**Next Steps **
Future improvements could include:
1. Building predictive sales forecasting models.
2. Implementing demand forecasting for inventory optimization.
3. Creating automated alerts for stockouts and declining sales.
4. Incorporating profitability and cost analysis.
5. Deploying the dashboard to the Power BI Service with scheduled data refresh and row-level security.
6. Integrating real-time sales data
   
**Conclusion**
This project demonstrates how SQL and Power BI can transform raw FMCG sales data into meaningful business insights. The analysis identified high-performing markets, profitable brands, seasonal demand patterns, pricing differences, and inventory risks. These insights can support decision-making in sales strategy, inventory optimization, pricing, and operational planning.
