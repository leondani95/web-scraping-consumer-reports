# Web Scraping Project - Consumer Reports

Hello! 👋

This is a small project where I applied basic web scraping techniques to extract product categories and their corresponding links from the [Consumer Reports](https://www.consumerreports.org/cro/a-to-z-index/products/index.htm) website. 

## Files

- `scraper.py`: This is the Python script that I wrote to perform the web scraping.

## Requirements

Before running the script, you need to install a few Python libraries. You can do this by running:

pip install requests fake-useragent beautifulsoup4 lxml


## How to Use

1. Download the script or open the Jupyter notebook file.
2. Run the script:
   - For `scraper.py`, execute it using Python:
     ```bash
     python scraper.py
     ```
3. The script will scrape product categories and their links, saving them to a text file for later use.
   

## Example Output

The script generates an output like this:

Air Conditioners ---> https://www.consumerreports.org/appliances/air-conditioners/

Air Filters ---> https://www.consumerreports.org/appliances/air-filters/

Air Fryers ---> https://www.consumerreports.org/appliances/air-fryers/

Air Mattresses ---> https://www.consumerreports.org/home-garden/air-mattresses/

Air Purifiers ---> https://www.consumerreports.org/appliances/air-purifiers/


## Notes

- The project uses `requests` to fetch the webpage and `BeautifulSoup` for parsing HTML and extracting the relevant data.
- A fake user agent is used to avoid potential blocking by the website.
- The script outputs the data in a clean and simple format, which can be adapted or expanded depending on the needs of the user.
