# Web Scraping Project - Consumer Reports

This is a small project where I applied basic web scraping techniques to extract product categories and their corresponding links from the [Consumer Reports](https://www.consumerreports.org/cro/a-to-z-index/products/index.htm) website. 

## Files

- `project_scraping_customerreports_website.py`: This is the Python script used to perform the web scraping.

## Requirements

Before running the script, you need to install a few Python libraries. You can do this by running:

pip install requests fake-useragent beautifulsoup4 lxml

## Features

- The project uses `requests` to fetch the webpage and `BeautifulSoup` for parsing HTML and extracting the relevant data.
- A fake user agent is used to avoid potential blocking by the website.
- The script outputs the data in a clean and simple format, which can be adapted or expanded depending on the needs of the user.

## Disclaimer

This excercise is part of the course "Web Scraping and Crawling with Python: Beautiful Soup, Requests & Selenium" from Waqar Ahmed (GoTrained Academy) on UDEMY
