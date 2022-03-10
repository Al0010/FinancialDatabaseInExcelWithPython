# Financial Database In Excel With Python

Create an ordered database of financial data on Excel using Pandas.

Through this script:

1) Download data from Yahoo Finance 
2) Create a dataframe using Pandas 
3) Extracts specific data from the dataframe
4) Create a database of financial data in Excel 

This simple script allows you to download data from Yahoo Finance. Once the dataframe containing the data has been created, the user will be able to extract the data of interest. Once the data of interest has been highlighted, the user will proceed to build a database in Excel.

This script helps the operator to simplify and speed up the creation of databases in Excel. 

In this example, an Excel database of opening and closing data is created with an analysis time period from 1/1/2021 to 10/3/2022. 
The assets under analysis in this example are: Nasdaq, Facebook, Netflix, Amazon, Google, Tesla, Nvidia, Nikola and Ferrari.

Version: Python V 3.10.2

# How to run this script 
1) Import libraries 
2) Set the script 
3) Run 

You can copy and paste the code into your Virtual Studio Code to test the script with the default settings in the example. Be careful when entering your directory for writing the excel file. An example of directory is: price.to_excel(excel_writer = r'/Users/utente/Desktop/Test.xlsx')

# Install Libraries
- pip3 install pandas 
- pip3 install datareader 
- pip3 install yahoo-finance

# Libraries to import 
- import pandas as pd
- import pandas_datareader.data as web
- import datetime as dt
