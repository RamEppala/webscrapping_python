# webscrapping_python

Scrapping a web Page using BeautifulSoup and Urllib2 python libraries 

Web scraping is a computer software technique of extracting information from websites. This technique mostly focuses on the transformation of unstructured data (HTML format) on the web into structured data (database or spreadsheet).

non-programming way to extract information out of web pages, you can also look at import.io . It provides a GUI driven interface to perform all basic web scraping operations. 

Libraries required for web scraping:

Urllib2: It is a Python module which can be used for fetching URLs.

BeautifulSoup: It is an incredible tool for pulling out information from a webpage.

BeautifulSoup does not fetch the web page for us. That’s why, I use urllib2 in combination with the BeautifulSoup library.

Code written in BeautifulSoup is usually more robust than the one written using regular expressions. Codes written with regular expressions need to be altered with any changes in pages. Even BeautifulSoup needs that in some cases, it is just that BeautifulSoup is relatively better.

Regular expressions are much faster than BeautifulSoup, usually by a factor of 100 in giving the same outcome.

So, it boils down to speed vs. robustness of the code and there is no universal winner here.

