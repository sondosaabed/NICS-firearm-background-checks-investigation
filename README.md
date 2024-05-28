# NICS firearm background checks Investigation

## Investigation process
In this report, a data analysis process is conducted on the NICS and Census Datasets. The process is performed in a structured manner where two main questions are considered: how some demographic factors contributes to the total numbers of gun permits issued, and what is the impact of housing and building permits on the total number of gun purchases, That is in diffrent states in teh year of 2016. In order to investigate and answer these questions: first of all the data is loaded into pandas dataframes, then an intial exploration is conducted, the next phase was assessing the data quality: that included multiple aspects such as: Detection of missing values, detection of duplicated values, detection of outliers and fiannly inconsistentny between the datsets. Now that the assessment is done, the datasets go through a cleaning process based on the assessment done, including handling the following: missing values, duplicated values, outliers and merging the datasets with fixing any inconsistentcies. Then, the exploratory data analysis (EDA) is done in order to answer the questions proposed, where that included visualizations too. Finally, the conclusions are made and presented to the reader and teh report is extracted into an html document.

## About the datasets
The data comes from the FBI's National Instant Criminal Background Check System. The NICS is used by to determine whether a prospective buyer is eligible to buy firearms or explosives.
Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase.
The data has been supplemented with state level data from census.gov

https://github.com/BuzzFeedNews/nics-firearm-background-checks/tree/master 
