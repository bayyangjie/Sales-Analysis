# Sales Analysis 

The goal of this project is to assist stakeholders, such as sales managers and executives, in evaluating sales performance as well as customer shopping trends and behaviors. This is accomplished by developing two dashboards, specifically the 'Sales Dashboard' and 'Customer Dashboard'.

Please click [here](https://public.tableau.com/views/Sales_Dashboard_17338076965380/SalesDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) to access the interactive dashboard available on my Tableau public profile.

<br>

# About the dataset

The dataset comprises of four different csv files namely Orders, Customers, Location and Products. The Orders table serves as the root or the primary table in the relationship. The other tables (Customers, Location, and Products) are then logically joined or related to it. 

<img src="https://github.com/bayyangjie/Sales-Dashboard/blob/main/Images/dataset%20structure.png?raw=true" width="100%"/>

<br>

# Sales Dashboard
The purpose of the sales dashboard is to present an overview of the sales metrics and trends in order to analyze year-over-year sales performance and understand sales trends.

<img src="https://github.com/bayyangjie/Sales-Dashboard/blob/main/Images/sales.png?raw=true" width="100%"/>

## Key Requirements

#### KPI Overview
In this segment, the KPIs (i.e total sales, profits and quantity) for the current (selected) year and the previous year are compared while also identifying the highest and lowest total sales of the selected year.

* **Total Sales**: Only 2020 to 2021 showed a decrease in sales but total sales grew back to back years from 2021 to 2023 with 2021 to 2022 having the highest increment.

* **Total Profits**: Total profits have a positive increment for all three years back to back with 2021 to 2022 having the highest increment.

* **Total Quantity**: Total sales quantity increased back to back for each of the three years with 2022 to 2023 having the highest increment.

#### Sales and Profit of Product Subcategories
The plots in this segment show the total sales and the profit/loss of each product subcategory. The total sales is also further narrowed down to compare between the current and previous year.

- Phones and chairs subcategories have the highest sales consistently each year from 2020 to 2023. Both products also returned profits each year for all four years.
- The tables subcategory show consistent losses throughout all the 4 years with the highest incurred losses occurring in 2023 at a loss of $8000.

#### Weekly Sales & Profit Trends
This plot shows the sales and profits of each week in the selected year. Weeks that have sales and profits above average are indicated in blue and weeks that have sales and profits below average are indicated in orange.

- For the sales chart, a common trend for all four years is that sales for the first half of the year tend to be below average and it starts to increase above average towards the end of the year.
- For the profits chart, the trend shows fairly balanced levels for all weeks throught the year for each of the four years.

<br>

# Customer Dashboard
The customer dashboard aims to provide an overview of customer data, trends and behaviors. This helps in assisting marketing teams and management to better understand customer segments and improve customer satisfaction.

<img src="https://github.com/bayyangjie/Sales-Dashboard/blob/main/Images/customer%20dashboard.png?raw=true" width="100%"/>

<br>

## Key Requirements

#### KPI Overview
This segment provides a summary of total number of customers , total sales per customer and total number of orders for the current year and the previous year. For each of the above mentioned KPI, they are presented on a monthly basis comparing between the current year and the previous year. Months with the highest and lowest sales are also identified. 

- All three metrics showed positive year-to-year increases from 2020 to 2023 except from 2020 to 2021 where total number of customers recorded a slight drop of -3.7%.

#### Customer Distribution by Number of Orders
In order to obtain insights into customer behavior, loyalty and engagement, the customer distribution is analyzed based on the number of orders that they have placed. 

- For each year from 2020 to 2023, the number of purchases that majority of customers make is in the range of 1 to 3.

#### Top 10 customers by Profit
The top 10 customers that generated the highest profit and sales for the company are identified and ranked accordingly together with their total number of orders placed as well as the total sales and profit generated. Their last order dates are also recorded.

- The top customer generated the most profit and sales for the company in 2022 at $8765 and $14203 respectively.
- Comparing the top 10 customers of each year, none of the customers made more than 5 purchases. 
