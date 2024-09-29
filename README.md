Cell Phone Sales Data Analysis Project



I’m excited to share my SQL project completed during training. The goal of the "Cell Phone Sales Data" project was to derive actionable insights from the data.



Project Objective :



1. Sales Trends: Identifying changes in sales patterns over time.

2. Top-performing Models and Manufacturers: Analyzing which models and manufacturers were the most popular.

3. Customer Purchasing Behavior: Understanding the preferences and habits of customers.

4. Price Analytics: Analyzing pricing trends, including the lowest and average prices of models across different manufacturers.



Techniques Used:



1. Data Retrieval and Filtering:

          SELECT Statements: Extracted data from DIM_CUSTOMER, DIM_LOCATION, DIM_MODEL, and FACT_TRANSACTIONS.

          WHERE Clauses: Refined data by criteria like year, manufacturer, and country.



2. Data Aggregation:

          GROUP BY: Aggregated data by models, states, or years for sales analysis.

          Aggregate Functions:

                            COUNT(): Counted transactions per model or state.

                            SUM(): Calculated total sales.

                            AVG() and ROUND(): Computed average sales prices, ensuring clarity.



3. Joining Tables:

          INNER JOIN: Combined related tables to analyze sales distribution and model performance.



4. Ranking and Window Functions:

         DENSE_RANK(): Ranked products/customers by sales volume.

         LAG(): Compared year-on-year sales for trend identification.



5. Data Sorting:

         ORDER BY: Sorted data to rank top-selling models and customers.



6. Set Operations:

          UNION and INTERSECT: Identified top-selling models across multiple years.



7. Date Functions:

          DATEPART() and YEAR(): Analyzed sales trends over time for deeper insights.



Achievements:



1. Top Purchasing States: Identified states with the highest customer purchases since 2005, offering geographic sales insights.

2. Leading Manufacturer: Determined Samsung as the top cell phone manufacturer in the US over multiple years.

3. Transaction Analysis: Analyzed transaction volumes by model, zip code, and state for regional and product-specific insights.

4. Price Insights: Found the cheapest cell phone model and assessed average prices among the top five manufacturers.

5. Customer Spending Behavior: Identified high-spending customers in 2009 and analyzed their purchasing habits.

6. Sales Consistency: Highlighted models that ranked among the top sellers from 2008 to 2010.

7. Manufacturer Activity: Noted manufacturers active in 2010 but not in 2009, indicating market shifts.

8. Spending Pattern Analysis: Analyzed percentage changes in spending for top customers, revealing trends in loyalty and purchasing power.
