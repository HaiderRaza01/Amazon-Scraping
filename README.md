Amazon Product Scraper
This project is a Python-based web scraping tool designed to collect product information from Amazon's website. This tool can extract data such as product name, price, rating, number of reviews, and other details for analytics, price tracking, and research purposes.


Features
Scrapes essential product details:
Product name
Price
Rating
Number of reviews
Availability
Other specifications
Handles pagination to scrape multiple pages
Saves data to CSV or JSON formats for further analysis

Requirements
Python 3.7+
Libraries:
requests
beautifulsoup4
pandas
lxml (for parsing HTML)
fake_useragent (optional, to rotate user agents for stealth scraping)
time (for adding delays between requests)
