# Store Sales - Time Series Forecasting
This repository holds an attempt at using time-series forecasting to forecast store sales on data from Corporación Favorita, a large Ecuadorian-based grocery retailer.
(https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview)
## Overview
- The task is to build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores, given 5 different .csv files as my data sets.
- I planned to use machine learning skills with an approachable training dataset of dates, store, and item information, promotions, and unit sales as a way to compile all this data and create accurate predictions.
## Summary of Work Done
### Data:
- I successfully implemented the train.csv and test.csv data sets. The others would follow the same general methodology.
### Problem Formulation:
- Input: 5 .csv files containing relevant data.
- Output: A submission file containg each id in the test dataset, with their corresponding value predictions.
### Performance:
- My notebook took a substantially long time creating the models of just 2 of the 5 data sets, therefore safe to assume it is a very taxing system if not ran on higher software.
## Files in Repository
- The 5 datasets:
  - train.csv
  - test.csv
  - stores.csv
  - oil.csv
  - holiday_events.csv
- SSTSF.ipynb : Notebook containing sections of the code used to obtain the output.
- transactions.csv : .csv file containg data pertaining to all transactions Corporación Favorita has completed.
## Software Setup
- Packages required:
  - Pandas
  - Numpy
  - MatPlotLib
  - Seaborn
  - Sklearn
- Installed through "pip install _____" in the terminal.
## Data
Data can be found using the link to the Kaggle challenge above, navigating to the "Data" tab, then scrolling down the page and clicking on the "Download All" button on the right to download a zip file containing the necessary data files.
