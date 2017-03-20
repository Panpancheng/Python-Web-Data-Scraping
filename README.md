# Python-Web-Data-Scraping
Use Python Beautiful Soup to Scrape Web Data:
First from HTML,get the needed htmls.
Then use beautiful soup from python to scrape data, using tag infornmation.
At last use for loop to extract data from multiple htmls, and put the data into csv files.
 
Libraries required for web scraping

As we know, python is a open source programming language. You may find many libraries to perform one function. Hence, it is necessary to find the best to use library. I prefer BeautifulSoup (python library), since it is easy and intuitive to work on. Precisely, I’ll use two Python modules for scraping data:

Urllib2: It is a Python module which can be used for fetching URLs. It defines functions and classes to help with URL actions (basic and digest authentication, redirections, cookies, etc). For more detail refer to the documentation page.
BeautifulSoup: It is an incredible tool for pulling out information from a webpage. You can use it to extract tables, lists, paragraph and you can also put filters to extract information from web pages. In this article, we will use latest version BeautifulSoup 4. You can look at the installation instruction in its documentation page.
BeautifulSoup does not fetch the web page for us. That’s why, I use urllib2 in combination with the BeautifulSoup library.


Reference website is:
1.https://www.analyticsvidhya.com/blog/2015/10/beginner-guide-web-scraping-beautiful-soup-python/
2.https://www.crummy.com/software/BeautifulSoup/bs4/doc/
