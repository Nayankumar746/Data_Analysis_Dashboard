# Pizza Sales Analysis (SQL + Power BI) 

Analysis of one year (2015) of pizza restaurant sales — 48,620 order line
items across 21,350 orders — using SQL for analysis and Power BI for an
interactive 2-page dashboard.

## Project Objective

The pizza restaurant wants an annual sales report for 2015, so the owner can understand ordering patterns, identify best- and worst-performing pizzas, and plan menu and staffing decisions for the year ahead.

## Dataset used:

- <a href="https://github.com/Nayankumar746/Data_Analysis_Dashboard/blob/main/pizza_sales_excel_file.xlsx">Pizza_sales_dataset</a>

## SQL queries used to calculate KPIs and build the Power BI dashboard

-<a href="https://github.com/Nayankumar746/Data_Analysis_Dashboard/blob/main/Pizza_Sales_SQL_Qurries.doc"> SQL Documentations</a>

## Questions(KPIs)

- What are the total revenue, total orders, total pizzas sold, average order value, and average pizzas per order?
- Which day of the week gets the most and fewest orders?
- Which month gets the most and fewest orders?
- What percentage of sales comes from each pizza category (Classic, Veggie, Supreme, Chicken)?
- What percentage of sales comes from each pizza size (S, M, L, XL, XXL)?
- Which 5 pizzas generate the most and least revenue?
- Which 5 pizzas sell the most and least by quantity?
- Which 5 pizzas appear in the most and fewest orders?
- What time of day do most orders come in?

## Dashboard Link
- <a href="https://github.com/Nayankumar746/Data_Analysis_Dashboard/blob/main/pizza_dasboard.pbix"> View Dashboard</a>

## Process

- Verified the dataset for missing values and inconsistencies (none found across 48,620 rows).
- Wrote 15 SQL queries to answer the KPI questions above, covering aggregates, trends, and top/bottom rankings.
- Built a 2-page Power BI dashboard with category and date-range slicers to visualize the same KPIs interactively.

## Project Insight

- Friday is the busiest day (3.5K orders); Sunday is the slowest (2.6K).
- July is the peak month (1,935 orders); October is the lowest (1,646).
- Classic pizzas lead in volume (14,888 sold), but Chicken pizzas lead in revenue — meaning Chicken pizzas sell for more per unit, not just in higher numbers.
- Large pizzas make up roughly 46% of sales by size, the single largest share.
- The Brie Carre Pizza is the weakest performer across all three measures — revenue, quantity, and order count — making it the clearest candidate for a menu review.

## Final Conclusion

From this analysis, I found that Friday and Saturday get the most orders, while Sunday and Tuesday are the slowest, so the restaurant could run mid-week offers to balance this out. July turned out to be the busiest month, so they should plan extra staff and stock around that time. I also noticed that Large size pizzas make up almost half of all sales, and Chicken category pizzas bring in more revenue even though Classic pizzas sell in higher numbers — so promoting Chicken pizzas more could help increase revenue. Lastly, the Brie Carre Pizza performed the worst in every measure I checked (revenue, quantity, and orders), so the restaurant might want to review or replace it. Overall, this project helped me understand how a business can use simple sales data to make better decisions about menu items, staffing, and offers.

## Dashboard Image

- <a href="https://github.com/Nayankumar746/Data_Analysis_Dashboard/blob/main/Screenshot%202026-09-25%20094454.png"> Image 1st</a>

- <a href="https://github.com/Nayankumar746/Data_Analysis_Dashboard/blob/main/Screenshot%202026-09-25%20094515.png"> Image 2nd</a>
