Pizza Sales Analysis Project using SQL

Overview:

This project aims to analyze pizza sales data using SQL to extract actionable business insights. The data includes various aspects such as order information, pizza types, sizes, prices, and the corresponding times the orders were placed. By crafting a series of SQL queries, I delved into customer behavior, sales trends, and product performance, helping to uncover valuable insights that could guide business decisions.

Insights and Analysis

1. Basic Analysis
   
         Total Orders: A query was used to retrieve the total number of orders placed over the observed period, providing a general measure of business volume.
   
         Total Revenue: By summing up the revenue generated from all pizza sales, I calculated the total earnings. This metric serves as a key indicator of business performance.
   
         Highest-Priced Pizza: Identifying the most expensive pizza helped highlight premium offerings and potential profit drivers within the product lineup.
   
         Most Common Pizza Size: The query revealed the most frequently ordered pizza size, giving insights into customer preferences.
   
         Top 5 Most Ordered Pizza Types: The top five most ordered pizzas, along with their quantities, were identified, showcasing the business’s best-selling items and helping to assess product popularity.
   
2. Intermediate Analysis
   
        Order Distribution by Hour: An analysis of orders placed by hour of the day revealed peak times for pizza purchases. This insight helps businesses optimize staffing and operations during busy periods.
   
        Category-Wise Pizza Distribution: By joining relevant tables, I derived the distribution of pizza sales across different categories (e.g., Veg, Non-Veg), giving insights into customer preferences within product segments.
   
        Orders Grouped by Date: Grouping the data by date allowed me to calculate the average number of pizzas ordered per day. This analysis provided insight into daily sales patterns and variability over time.
   
        Top 3 Most Ordered Pizzas by Revenue: I identified the top three most ordered pizza types based on total revenue generated, highlighting which pizzas are not only popular but also profitable.
   
3. Advanced Analysis

        Percentage Contribution to Revenue: I calculated the percentage contribution of each pizza type to the total revenue, allowing for a better understanding of how each product influences overall sales.
   
        Cumulative Revenue Analysis: By analyzing cumulative revenue over time, I gained insights into the growth of sales throughout the observed period, helping identify trends or anomalies in performance.
   
        Top 3 Pizzas by Revenue for Each Category: The analysis went further to determine the top three most ordered pizza types based on revenue within each category (e.g., Veg, Non-Veg). This deeper insight helps understand which pizzas are the most successful within their specific segments.

   
SQL Techniques Employed:

Aggregation Functions: I used SUM(), COUNT(), AVG(), and other aggregate functions to summarize data effectively.

JOINS: By performing various types of joins between tables, I was able to combine data across different dimensions such as order details, pizza details, and categories.

Group By and Date Functions: Grouping data by date and time helped to uncover trends and patterns in sales activity.

Window Functions: I utilized window functions for more advanced analysis, including ranking pizzas based on revenue and calculating cumulative totals.

Conclusion:

This project highlights the importance of SQL in extracting actionable insights from raw data. Through thorough analysis of pizza sales data, I was able to uncover key performance metrics, customer preferences, and sales trends. These insights can help a pizza business optimize its offerings, manage operations more effectively, and increase profitability.

Future Work:
As part of the continuous improvement of this analysis, 

I plan to:

Integrate more complex queries, such as predicting future sales using historical data.

Incorporate visualizations to better represent the trends and insights.

Further segment the analysis by customer demographics or location (if data is available) to provide more targeted business recommendations.









