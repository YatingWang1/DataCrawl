# Data Crawl
> A Python code to crawl structured web content such as Yelp.

This program uses BeautifulSoup package to crawl 100 ice cream shops near zip code "10023" from Yelp website(excluding advertisements). It stores ranking, name, rating, number of reviews, phone number, detailed address and district information of each shop in a CSV file, and draws two kinds of bar charts, one showing number of shops in each district and the other showing average using rating of each district.

## Usage Example
If you want to crawl other kinds of shops, you can change the URL you want to crawl here.
```
#the url we want to crawl
url = 'https://www.yelp.com/search?find_desc=ice+cream&find_loc=10023&ns=1'
```

## Meta
Yating Wang – ywang1078@fordham.edu

## Release History
* 2/9/2020
    * 0.0.1
