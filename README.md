# Amazon-Scraper-by-Shafay

<b>Amazon Scraper using Selectorlib</b>

A simple amazon scraper to extract product details and prices from Amazon.com using Python Requests and Selectorlib.

There are two simple scrapers in this project.

Amazon Product Page Scraper amazon.py
Amazon Search Results Page Scraper searchresults.py
Note: A completely web browser based commercial version of these scrapers are available in ScrapeHero Marketplace

<b><h2>Usage</h2></b>

From a terminal

Clone this project and cd into it cd amazon-scraper
Add a Virtual Environment python3 -m venv .venv (Optional)
Activate the Virtual Environment source .venv/bin/activate (Optional)
Install Requirements pip3 install -r requirements.txt

<b><h2>Scrape Product Details from Product Page</h2></b>

Add Amazon Product URLS to urls.txt
Run python3 amazon.py
Get data from output.jsonl

<b><h2>Scrape Products from Search Results</b></h2>

This scraper only scrapes product from the first page of search results

Add Amazon Product URLS to search_results_urls.txt
Run python3 searchresults.py
Get data from search_results_output.jsonl

