#  Web Scraping Projects

This repository contains two beginner-friendly web scraping projects using Python and BeautifulSoup. The goal is to extract structured data from public websites and process it using pandas.

## Project 1: Book Store Scraper

- **Source**: [books.toscrape.com](https://books.toscrape.com/)
- **Data Extracted**:  
  - Book Title  
  - Price  
  - Star Rating  
  - Stock Availability  
- **Features**:  
  - Scrapes all 50 pages (1000 books)  
  - Stores data in a CSV file

## Project 2: IPL 2022 Auction Scraper

- **Source**: IPL 2022 auction site (https://www.iplt20.com/auction/2022#:~:text=Explore%20IPL%202022%20auction%20data%2C%20including%20players%20bought%2C,remaining%20amounts.%20Get%20all%20the%20details%20on%20IPLT20.)
- **Data Extracted**:  
  - Player Name  
  - Team  
  - Base Price  
  - Sold Price  
  - Auction Status (Sold/Unsold)
- **Features**:  
  - Parses tabular data from the webpage  
  - Cleans and formats into structured CSV

## Tech Stack

- Python
- BeautifulSoup
- Requests
- Pandas

## Output

Each project stores the scraped data in CSV format for easy analysis or further use.
