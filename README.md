# WebScrapping: Amazon Search for particular item
Web scrapping the amazon website data and analyze the data using Pandas and numpy

This project performs web analysis on Amazon website using Python, BeautifulSoup, and Pandas. 
The analysis covers various aspects, including extracting and analyzing Book with description, Price, Rating and Review Count


## Project Overview

The project can be divided into the following sections:

1. **Data Extraction**: The data is extracted from the HTML of Amazon using BeautifulSoup. The url function will allow anyone to search for particular item thorugh selected number of pages.The scrap record function get data from each book.The search_all_page function search data from all the pages.( number of pages applied by the user).
   
3. **Data Cleaning**:Data for price, rating, review and description is get thorugh removing space and get by particular html tag 
   
6. **Data Analysis**: Various analyses are performed on  data. The plot Price range VS rating to get an idea that is the high rated books are affordable or not.Bar plot shows that high rated books are affordable and falls under range of $15- $20.Another analysis is for particular topics covered by number of books. Pie chart shows that most of books covered sql itself. But 37.5% includes python as well and the analytics is coverd by  8.3% of books.

