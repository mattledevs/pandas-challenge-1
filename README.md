# Background
This module challenge focuses on data analysis with Python's Pandas library. As a crucial component in various fields, such as data science, machine learning, and business intelligence, practical data analysis involves examining, cleaning, processing, and extracting useful information from large datasets. This assignment provides a hands-on opportunity to develop these skills.


In this challenge, a dataset from a fictional e-commerce company is used to explore and analyze data to address real-world business questions. Various prompts with Juptyer notebook will involve identifying top customers, popular product categories, calculating profits, as well as transforming, and analyzing the data for various scenarios.


# Location of GIT repository
[https://github.com/mattledevs/pandas-challenge-1](https://github.com/mattledevs/pandas-challenge-1)


# Challenge Overview
## Part 1: Explore the Data
In this part, the sales data will be imported and use Pandas to learn more about the dataset.


The following questions are answered using Pandas:


- What three item categories had the most entries?
- For the category with the most entries, which subcategory had the most entries?
- Which five clients had the most entries in the data?
- How many total units (the qty column) did the client with the most entries order?


## Part 2: Transform the Data


Various columns will be created and calculated:
- Calculate the subtotal for each line using the unit_price and the qty
- Shipping price with the logic: assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under
- Total price using the subtotal and the shipping price along with a sales tax of 9.25%.
- The cost of each line using unit cost, qty, and shipping price (assume the shipping cost is exactly what is charged to the client)
- The profit of each line using line cost and line price


## Part 3: Confirm Your Work
After transforming data, email receipts are used to verify total prices for 3 orders. Calculations are matched to the receipts with multiple lines.




## Part 4: Summarize and Analyze
New columns with confirmed values are created to find the following information.


A summary DataFrame is created showing the totals for the top 5 clients with the following information: total units purchased, total shipping price, total revenue, and total profit as well as applying a function to change the currency to millions of dollars. The data and columns are formatted and renamed suitable for presentation. Then the DataFrame is sorted in descending order by total profits.


Conclusion at the end summarizes findings.

