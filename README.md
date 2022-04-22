Data Wrangling (pandas)

Business requirement I

Using the data ‘pct_distribution.csv’, I added a column called ‘% Sales Contribution’ (rounded to 2 decimals) which shows how many percent each product has contributed towards the entire sales

I sorted the column ‘% Sales Contribution’ in a descending order.
The row indexes are out of order. I Reorganize the indexes so it’s from 0 to 5 again. Everything else should remains the same.

Then I put a $ (dollar sign) infront of the numbers in ‘Sales_dollar’ column, then renamed the column to ‘Sales’.


Business requirement II

Using the data ‘groupby_df.csv’, I calculated how much each product totaled in sales, then named the column as ‘Sales_dollar_product’

Then I calculated how much each person totaled in sales, then named this column as ‘Sales_dollar_person’

Then calculated how much each person totaled in sales per product, then named this column as ‘Sales_dollar_person_product’

Addendum
It turns out that the stakeholders don’t want any sales above $50.00 to be in the calculation. Using the data ‘groupby_df.csv’, perform Business requirement II again without the sales over $50.00.


Business requirement III

Using the data ‘merge_df.csv’, I inner joined it with ‘pct_distribution.csv data on product to get matching records from both tables.

Then I performed a left join on both dataframe on product column to get all the records in the left table and the corresponding matching records in the right table

Then I performed an outer join on both dataframe on product column to get all records in both tables.



