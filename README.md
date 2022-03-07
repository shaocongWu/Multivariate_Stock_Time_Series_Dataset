# Multivariate Stock Time Series Dataset
This repository contains multivariate daily data of 800 stocks from the Chinese stock market that are constituents of the CSI 300 and CSI 500 indices.

The data of each stock is stored in a separate csv file, named by the code. e.g., 000001.SZ.csv

> You can find all the data files in the "CSV" folder.

The structure of each csv file is as follows.

No. | ts_code | trade_date | open | high | low | close  | pre_close | change | pct_chg | vol | amount |
:-----:|:-----:|:-----:|:----------:|:----:|:-----:|:--------:|:------:|:-----:|:-----:|:-----:|:-----:|
……|……|……|……|……|……|……|……|……|……|……|……|

Item | Type | Description |
:-----:|:-----:|:-----:|
ts_code | str | stock code |
trade_date | str | transaction date |
open | float | opening price |
high | float | highest price |
low | float | lowest price |
close | float | closing price |
pre_close | float | closing price of the previous trading day |
change | float | close - pre_close
pct_chg | float | Percent Change
vol | float | volume of transaction
amount | float | stock amount