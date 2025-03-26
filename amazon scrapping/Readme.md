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
