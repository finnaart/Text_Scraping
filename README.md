# Skintific Product Scraper

This is a Python project for scraping product data from the Skintific website's "Hot Sale" section. The project uses BeautifulSoup to extract product details such as the name, price, pre-discount price, and rating from multiple pages.

## Features
- Scrapes product information from multiple pages of the Skintific website.
- Extracts the following data:
  - Product name
  - Sale price
  - Pre-discount (regular) price
  - Product rating
- Stores the scraped data into a Pandas DataFrame for easy analysis and export.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.x installed on your machine
- The following Python libraries installed:
  - `requests`
  - `beautifulsoup4`
  - `pandas`

## How It Works
- The script requests the HTML of the "Hot Sale" section on Skintific's website.
- It loops through three pages of products to gather the information.
- The data is then processed and stored in a Pandas DataFrame for easy manipulation and export to CSV or other formats.
