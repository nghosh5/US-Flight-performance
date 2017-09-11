# US-Flight-performance
To understand delay performance on various US airlines based on recent twelve months airline data by building glm,poisson and lasso models
The data consists of 12 months csv.
SAS macro is built to import CSVs from one single folder and then columns are cleaned and renamed before merging to form dataset.
Missing values have also been treated in this code.
Lagged variables are created for delay metrics such as departure and arrival delay.
Finally models are built to understand on-time performance of Airlines based on delay metrics.
