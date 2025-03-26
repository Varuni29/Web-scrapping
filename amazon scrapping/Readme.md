# Amazon Web Scraper using Selenium on Databricks
## Project Overview:
This project is a scalable web scraping solution for extracting Amazon product details using Selenium on Databricks. The script scrapes multiple pages of the Amazon website, retrieves product information (name, price, ratings, deals, etc.), and stores the data in a structured format using PySpark.

## Features:
1. Automated Web Scraping: Uses Selenium to dynamically extract data from Amazon product listings.
2. Parallel Execution: Distributes scraping tasks across Databricks worker nodes for efficient data retrieval.
3. Data Cleaning & Transformation: Converts extracted data into a structured format using PySpark DataFrame.
4. Scalability: Optimized to scrape multiple pages concurrently using Databricks’ parallel processing.

## Tech Stack:
1. Python (Selenium, BeautifulSoup, Pandas, PySpark)
2. Databricks (for distributed computing)
3. ChromeDriver (headless browser for web automation)

## Installation & Setup:
1. Installation of Google Chrome and Chrome Driver on Databricks is necessary.
2. Run the Script on Databricks and Upload and execute main.ipynb in a Databricks notebook. The script:
    1. Loads ChromeDriver in headless mode
    2. Iterates through Amazon pages
    3. Extracts product details
    4. Stores the results in a PySpark DataFrame
## Output:
1. The scraped data includes:
2. Product Name
3. Product Link
4. Ratings & Total Reviews
5. Price (Discounted & Original)
6. Deal Availability
7. Coupon Savings

The final dataset can be stored as a CSV file in Databricks or Azure Blob Storage.
