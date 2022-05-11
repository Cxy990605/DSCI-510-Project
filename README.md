# DSCI-510-Project
### How to run the scraping programs? (revised for hw4)
# According to the given file "DSCI510FinalProjectGuidelines", there exists three ways of runnning the file:
	1. scraper.py --scrape:  scrape the data but return only 5 entries of each dataset.
	2. scraper.py --static <path_to_dataset>: return the static dataset scraped from the web and stored in database or CSV file
	3.scraper.py: Return the complete scraped datasets. 
# After applying those three command lines above, there should be csv.files created for the project analysis
# Please notice that I separately upload these web scraping .py files, and hence there are three independ files instead of only one


### How to run the project programs?
# The whole project is done by a jupyter notebook file
# Packages Required: pandas, csv, numpy, yfinance, matplotlib.pyplot, requests, beautifulsoup, datetime, seaborn, statsmodels.api, statsmodels.formula.api, mean, stats
# The web-scraping csv.files are located in the same folder of jupyternotebook, and hence can be directly read  by pd.read_csv()
# Github already uploaded the whole dataset, including 3 csv.files and ipynb.files
