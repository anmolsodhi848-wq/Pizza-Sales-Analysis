# Pizza-Sales-Analysis


## Project Objective

To analyze pizza sales data to uncover revenue trends, product performance, ingredient contribution, and customer ordering patterns in order to generate actionable business insights for revenue optimization and strategic decision-making.


## Dataset Source

https://github.com/anmolsodhi848-wq/Pizza-Sales-Analysis/blob/main/Pizza%20Order.xlsx


## Key Performance Indicators (KPIs)

1. Total Revenue: 2,236,929
2. Total Orders: 13,402
3. Total Quantity Sold: 129,194 pizzas
4. Average Order Value (AOV): 166.9
5. Average Pizzas per Order: 9.64


## Process

1. ## Data Preparation
   1. Cleaned raw transactional data
   2. Removed inconsistencies and null values
   3. Standardized categorical fields (Size, Category, Ingredients)
   4. Separated ingredients using delimiter transformation
   5. ## Created calculated fields:
      1. Revenue = Quantity × Price
      2. Average Order Value


2. ## Data Visualization
   1. ## Designed interactive dashboards:
      1. Sales Overview Dashboard
      2. Product & Ingredient Insights Dashboard

  2. ## Implemented filters:
     1. Category
     2. Date Range
     3. Hour of Time
     4. Pizza Name
     5. Price Range
     6. Size
     7. Revenue Range

3. Created calculated fields and table calculations
4. Applied sorting, percentage contribution, and KPI cards
5. Designed an executive-style layout for clarity and storytelling


## Dashboard

1. ## Sales Overview

<img width="1910" height="976" alt="image" src="https://github.com/user-attachments/assets/7576f4a5-4bdb-4e2e-811a-b708dc7bf2db" />

2. ## Product and Ingredient Insights

<img width="1918" height="977" alt="image" src="https://github.com/user-attachments/assets/699da3f7-6eb1-4f00-bcbc-13ddc2050768" />


## Project Insights

1. ## Revenue & Category Insights:
   1. Chicken category contributes the highest revenue (~46.5%).
   2. Classic category generates the lowest revenue share (~8.5%).
   3. Revenue shows seasonal fluctuations with noticeable peaks in certain months.

2. ## Size Analysis:
   1. Large (L) pizzas dominate sales (~42% of total quantity).
   2. Medium size follows, while Small contributes the least.

3. ## Product Performance:
   1. Top-performing pizzas generate significantly higher revenue concentration.
   2. Revenue distribution suggests a strong product concentration strategy.

4. ## Time-Based Analysis:
   1. Peak order hours occur during afternoon and early evening (1 PM – 7 PM).
   2. Very low order volume late at night.

5. ## Ingredient Insights:
   1. Tomatoes, Red Peppers, and Red Onions are the most used ingredients.
   2. Ingredients like Tomatoes contribute the highest revenue impact.
   3. Large-size pizzas drive higher ingredient usage and revenue contribution.


## Conlusions

1. Revenue is heavily driven by Chicken category and Large-sized pizzas.
2. A limited number of pizzas generate a majority of revenue (Pareto trend).
3. Ingredient-level analysis reveals key cost-impact components.
4. Sales peak during specific hours, indicating strong lunch and dinner demand patterns.
5. Business performance can be optimized by focusing on high-performing categories and sizes.


## Recommendations

1. Promote high-margin, top-performing pizzas through bundled offers.
2. Introduce marketing strategies for underperforming categories (e.g., Classic).
3. Optimize inventory planning based on most used ingredients.
4. Implement time-based promotional campaigns during non-peak hours.
5. Consider pricing strategy optimization for Small size pizzas to increase volume.
6. Focus advertising on Large pizzas as they generate maximum revenue.


## Future Scope

1. Profitability Analysis (Cost vs Revenue per Pizza & Ingredient)
2. Customer Segmentation & RFM Analysis
3. Demand Forecasting using Time Series Models
4. Dynamic Pricing Strategy Modeling
5. Basket Analysis (Frequently Bought Together)
6. Integration with real-time POS data
7. Predictive modeling using Python/SQL
