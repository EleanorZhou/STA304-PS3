# STA304-PS3
3rd Assignment of STA304 - Predicting the 2020 America Federal Election Result from Democracy Fund + UCLA Nationscape and IPUMS USA Datasets This repo contains code and data for forecasting the US 2020 presidential election. It was created by Rutvik Gupta (1004939837), Elyssa Plaza (1004356760), Yubing Xia (1005063244), Hongbo Zhou(1004832862).
The purpose is to create a report that summarises the results of a statistical model that we built. 

Some data is unable to be shared publicly. We detail how to get that below. 

Inputs contain data that are unchanged from their original. We use two datasets:

[Survey data - Request access to the Democracy Fund + UCLA Nationscape ‘Full Data Set’ at :https://www.voterstudygroup.org/publication/nationscape-data-set. Use the - 01-data_cleaning-survey.R to get started preparing this dataset, and then go on cleaning and preparing it.]

[ACS data - Please create an account with IPUMS: https://usa.ipums.org/usa/index.shtml. Download the relevant post-stratification data (it’s probably easiest to change the data format to CSV). Use the ACS data to create the post-stratification dataset using the 02-data_cleaning-post-strat.R]
Outputs contain data that are modified from the input data, the report and the supporting material.

Scripts contain R scripts that take the inputs and outputs and produce outputs. These are:

01-data_cleaning-survey.R

02-data_cleaning-post-strat.R
