# ChiPy_MLB

Repository containing files related to MLB data pipeline project

1. Statcast_scraper.ipynb : Jupyter notebook with POC to use url with pandas.read_csv to import data from baseballsavant.com
2. MLB_2018_Data_Download : Using statcast_scraper.ipynb as a base, this jupyter notebook uses a 2018 schedule csv file that contains the dates of games played in 2018. Then concatenates the url string with specific dates to import data. Next steps will be to look through schedule csv to download all of 2018 data. 
