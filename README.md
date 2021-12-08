# Real Estate Calculator
This is a calculator that allows the user to view properties that fit within their monthly budget after taxes, insurance, and supplemental income. The calculator works best for properties located in the San Francisco area but can also be applied to other cities as well.

# Requirements
1. Python 3
2. Python packages: sqlite3, pandas, csv
3. [Instant Data Scraper Google Extension](https://chrome.google.com/webstore/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah?hl=en-US) or use of provided data (See Method 2 in Set Up)

# Set Up
## Method 1: Scrape Current Data
1. Search for properties in your selected city on [Zillow](https://www.zillow.com/san-francisco-ca/?searchQueryState=%7B%22pagination%22%3A%7B%7D%2C%22usersSearchTerm%22%3A%22San%20Francisco%2C%20CA%22%2C%22mapBounds%22%3A%7B%22west%22%3A-122.57290134109931%2C%22east%22%3A-122.26253757156806%2C%22south%22%3A37.69278060668317%2C%22north%22%3A37.81303337655604%7D%2C%22regionSelection%22%3A%5B%7B%22regionId%22%3A20330%2C%22regionType%22%3A6%7D%5D%2C%22isMapVisible%22%3Atrue%2C%22filterState%22%3A%7B%22sort%22%3A%7B%22value%22%3A%22globalrelevanceex%22%7D%2C%22ah%22%3A%7B%22value%22%3Atrue%7D%2C%22con%22%3A%7B%22value%22%3Afalse%7D%2C%22manu%22%3A%7B%22value%22%3Afalse%7D%2C%22land%22%3A%7B%22value%22%3Afalse%7D%7D%2C%22isListVisible%22%3Afalse%2C%22mapZoom%22%3A12%7D)
2. Use the Instant Data Scraper to crawl and scrape all properties. For detailed instructions watch [this tutorial](https://www.youtube.com/watch?v=I-2YxQ5B-yA).
3. Store file as scrape.csv in the same location as WebScrape.py

## Method 2: Use Previously Scraped Data 
Use current scrape.csv file included. This scrape was conducted in Dec 2021 on San Francisco properties. No additional set up is needed.

# Installation
1. pip install sqlite3 pandas csv
2. Run Webscrape.py
