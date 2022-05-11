# DSCI-510-Project
## How to run the scraping programs? (revised for hw4)
### files_name: wti_spot_price.py   OXY_Stock_Price.py    EV_sales.py
### According to the given file "DSCI510FinalProjectGuidelines", there exists three ways of runnning the file:
	1. scraper.py --scrape:  scrape the data but return only 5 entries of each dataset.
	2. scraper.py --static <path_to_dataset>: return the static dataset scraped from the web and stored in database or CSV file
	3.scraper.py: Return the complete scraped datasets. 
### After applying those three command lines above, there should be csv.files created for the project analysis
### Please notice that I separately upload these web scraping .py files, and hence there are three independ files instead of only one


## How to run the project programs?
### 1. The whole project is done by a .ipynb file
### Packages Required: pandas, csv, numpy, yfinance, matplotlib.pyplot, requests, beautifulsoup, datetime, seaborn, statsmodels.api, statsmodels.formula.api, mean, stats
### The web-scraping csv.files are located in the same folder of jupyternotebook, and hence can be directly read  by pd.read_csv()
### 2. Another version as .py file called scraper.py, which started with the data scraping function
### file name: scraper.py
### Difference from .ipynb: def process_data(data) function to read .csv file
###                         end with  if __name__ == '__main__': main()

## How to run the scraping file, which includes three web scraping function in one file?
### command line: python3 data_scraper.py
	Wrote car sales data to car_sales.csv
	Wrote WTI spot price data to wti_spot_price.csv
	Wrote OXY price data to OXY_stock.csv

## What's more:
### Github/DSCI-510-Project already uploaded the whole dataset, including 3 .csv files & .ipynb files & .py files
