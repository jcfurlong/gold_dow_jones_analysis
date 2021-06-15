# gold_dow_jones_analysis
This is an analysis I performed on historical price information for gold and the Dow Jones. These are traditionally seen as having a strong negative relationship. 
While I found that to be the case prior to 2000, it does not during the 21st century. My analysis suggests a moderate positive correlation over the past 21 years. 

The first file, "Web Scraping Gold and Dow.ipynb", contains my python code for scraping datasets from https://www.macrotrends.net/1319/dow-jones-100-year-historical-chart
and https://www.macrotrends.net/1333/historical-gold-prices-100-year-chart
It also places that data into a pandas dataframe and exports it as a CSV. I did not want that in the same file as my analysis, as I was worried about lag.

The second file, "Web Scraping Analysis.ipynb", contains my analysis and conclusions. It also is where I cleaned the data and converted the dollar amounts to 2021 rates. The
data for that conversion comes from https://www.officialdata.org/us/inflation/1800?amount=1#citation
