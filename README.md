# tiki-scraping
- Selenium to get Categories data (URL, Category Name) since it's from ajax
- Loop to get API response with library Requests + Multithreading
- Conver to dataframe, CSV file
- Quick analyzing with matplotlib

# Note
When trying to get API response, some of the returned json  has the key 'data' and value is an empty list. This happens when try to scrape page 22, 25, but sometimes it works very well to the last page of each category.
I'm trying to find the answer for this problem.

# Quick analyzing: Questions...
1/ How many duplicated products?
2 / How many products are there in each category?
3/ How many sellers are there on Tiki?
4/ How many brands in Tiki? Name top 10 brands with the most products?
5/ Which category has the most comments? Which category has the least comments?
