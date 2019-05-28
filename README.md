# Topos-Assignment

### About
The aim of this assignment is to create a Scraper in Python to scrape data about top cities of USA, clean it and store it to Bigquery from the following link :
https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population

The table containing the information about the top cities is scraped, cleaned and stored.
Script in Python is written to perform web scraping using BeautifulSoup and Selenium. 
Furthermore, to enhance the data, a long(LD) and short description(SD) about the cities is collected using the site https://www.lonelyplanet.com/search
For every top city, the scraper collects the description.

Cleaning of data involves stripping of blank spaces, percentage signs, commas from numerical values and unwanted characters.

### Requirements : 
Python 3, Selenium, BeautifulSoup, Chrome Driver

### Installation :
1) pip install selenium
2) Download the Chrome Driver in accordance to the version of the web Chrome Browser from (http://chromedriver.chromium.org/downloads)

## Storing to Bigquery
Steps:
1) Once the Cleaned_data.csv is ready, it is in the format ready to be loaded to Bigquery
2) Using Bigquery console create table (upload)
3) Browse the file
4) Since it is a CSV file, we use the enable option Auto-detect

