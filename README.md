# eBay Webscaping

## Overview
Performed analysis on eBay's Presidents Day sales by web-scraping detailed product information using Python

## Steps:
1. Save URLs of each items separately
2. Create a folders called "deals" to store the html pages for each item
3. Loop through the pages downloaded in previous step, open and parse them. Then identify and select: seller name, seller score, item price, item price, list price, number of items sold, title, returns allowed, shipping price, and condition
4. Save information above into a SQL database
5. Run summary statistics on each item; Print the mean, min, max, and mean for each numeric column, dependent on whether “list price” and "condition" was provided

## Conclusion
From the table above, it seems that the existence of “list price” appear to influence sales. The items with list prices have higher mean number of items sold regardless of the conditions.
