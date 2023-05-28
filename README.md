# Web Scraping with Scrapy

This repository provides a collection of Scrapy spiders and related components for web scraping and data extraction. The project focuses on leveraging the Scrapy framework, Python, and various techniques to efficiently scrape data from websites.

## Getting Started
To get started with this project, follow the steps below:

## Prerequisites
- Python 3.7 or higher
- Scrapy framework
- Additional dependencies (specified in pyproject.toml)

## Installation
1. Clone this repository to your local machine.
2. Navigate to the project directory.
```bash
cd web-scraping-with-scrapy
```
3. Create a virtual environment (optional but recommended).
```bash
Poetry init
Poetry shell
```
4. Install the required dependencies using Poetry
```bash
Poetry install
```

By following these steps, you can install the required dependencies using Poetry and manage your project's dependencies effectively.

## Features
1. Crawling through websites & scraping data from each page
The Scrapy spiders in this project are designed to crawl through websites and scrape data from each page. They utilize the powerful features of Scrapy, such as the ability to follow links, parse HTML/XML responses, and extract data using XPath or CSS selectors.

2. Cleaning data with Items & Item Pipelines
The scraped data is processed and cleaned using Scrapy's Item classes and Item Pipelines. Items define the data structure for scraped items, while Item Pipelines allow for further processing, validation, and storage of the scraped data. Customize the item classes and pipelines as per your requirements.

3. Saving data to CSV files, MySQL & Postgres databases
The project provides functionality to save the scraped data to various destinations, including CSV files, MySQL databases, and Postgres databases. Configure the appropriate pipelines and settings to store the data in your desired format and location.

4. Using fake user-agents & headers to avoid getting blocked
To prevent websites from detecting and blocking the scraping activities, the spiders utilize fake user-agents and headers. These mechanisms help mimic real user behavior and avoid potential blocking