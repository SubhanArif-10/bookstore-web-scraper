# Bookstore Intelligence Mission: Web Scraper

A Python web scraper that collects competitor book data from [books.toscrape.com](https://books.toscrape.com/) and turns it into a clean dataset for business analysis.

## What it does
- Scrapes title, price, star rating, availability and product URL for every book
- Converts rating words (One to Five) into numbers 1-5
- Loops over all 50 catalogue pages (1,000 books) with one reusable function
- Saves the result as `competitor_books.csv`
- Answers business questions and solves a £100 star-maximisation challenge

## Libraries
`requests`, `BeautifulSoup (bs4)`, `pandas`, `numpy`, `matplotlib`

## How to run
Open the notebook in Google Colab and choose Runtime → Run all.

## Files
- `23i_5135_Assignment2.ipynb`: scraper and analysis
- `competitor_books.csv`: scraped dataset
- `rating_counts.png`: bar chart of star ratings
