# Books_to_Scrape
[Scrapping Techniques using Regular Expressions (Regex)] 

The learning objective of this exercise is to practice Python programming language using Beautiful Soup library to "scrape" books information from the website https://books.toscrape.com

![Bookstore](https://github.com/fabianaba/Books_to_Scrape/bookstore.png)

## Deliverable result: 
Must be a '.csv' file; table with 6 columns named as title, price, rate, availability in stock, category, and date/time of scrapping.

## Process:
* create a pattern dataframe containing the 6 columns listed above 
* for each category (Classics, Science Fiction, Humor, and Business), create a Beautiful Soup object to extract the information in their specific webpages and create a dataframe to concatenate with the pattern dataframe. Missing information will be filled with 'NA'.
* concatenate all dataframes into a final dataframe
* export the final dataframe to a '.csv' file

## Input:
Webpages for each category as follow:
* Classics: http://books.toscrape.com/catalogue/category/books/classics_6/index.html
* Science Fiction: http://books.toscrape.com/catalogue/category/books/science-fiction_16/index.html
* Humor: http://books.toscrape.com/catalogue/category/books/humor_30/index.html
* Business: http://books.toscrape.com/catalogue/category/books/business_35/index.html
