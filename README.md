# CryptoCurrencyDataMining
Get the time series data for different cryptocoins, web scraped from coinmarketcap.

# Installation 
  We use R program for pulling the data from coinmarket cap website. So R should be installed along with any editor in order to make changes.

  Following packages should be installedto run the program.
  rvest,
  tidyverse,
  plyr,
  jsonlite,
  anytime

# Installing Packages

  To install any of the missing packages run the following command in R console.

                    install.packages("package_name")
  Package name should be inside the "" quotes.                  


# Output

The code will generate csv files of three kinds.
  1) Complete list of coins available on coinmarketcap and their aliases
  2) Complete list of exchanges available on coinmarketcap and heir aliases
  3) For each coin or token a file with timeseries data of volume, marketcap,and prices.
  
