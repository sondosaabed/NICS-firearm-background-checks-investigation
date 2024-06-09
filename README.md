# NICS firearm background checks Investigation

## Investigation process
In this report, a data analysis process is conducted on the NICS and Census Datasets. The process is performed in a structured manner where two main questions are considered: how some demographic factors contributes to the total numbers of gun permits issued, and what is the impact of housing and building permits on the total number of gun purchases, That is in diffrent states in teh year of 2016. In order to investigate and answer these questions: first of all the data is loaded into pandas dataframes, then an intial exploration is conducted, the next phase was assessing the data quality: that included multiple aspects such as: Detection of missing values, detection of duplicated values, detection of outliers and fiannly inconsistentny between the datsets. Now that the assessment is done, the datasets go through a cleaning process based on the assessment done, including handling the following: missing values, duplicated values, outliers and merging the datasets with fixing any inconsistentcies. Then, the exploratory data analysis (EDA) is done in order to answer the questions proposed, where that included visualizations too. Finally, the conclusions are made and presented to the reader and teh report is extracted into an html document.

## About the datasets
The data comes from the FBI's National Instant Criminal Background Check System. The NICS is used by to determine whether a prospective buyer is eligible to buy firearms or explosives.
Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase.
The data has been supplemented with state level data from census.gov

https://github.com/BuzzFeedNews/nics-firearm-background-checks/tree/master 

## Conclusions

In conclusion, two questions were investigated regarding the datasets whether the demographic columns affect the total number of gun permits issued and wether the total number of gun permits issued is affected by housing units or building units. In order to answer these questions, the datasets goes through the data cleansing process including handling outliers, duplicates, and missing values finally fixing the inconsistencies btween the datasets and standarizing it into teh year 2016.

### Demographic Factors and Gun Permits

The first question was answered with the following conclusions:

- A negative weak correlation was observed between all age groups and the total number of gun permits, indicating that as age group percentages increase, the number of permits tends to decrease slightly.
- Initial assumptions suggested that the gender percentage might not significantly affect the total number of permits, given the consistent nature of female population percentages. However, a moderate positive correlation was found between gender percentages and the number of permits, suggesting a potential influence.
- Analysis of racial demographics revealed various correlations:
  - Moderate positive correlations were found between higher percentages of Hispanic/Latino and Black/African American populations and the number of gun permits issued.
  - Moderate negative correlations were observed with Native Hawaiian/Pacific Islander and Two or More Races demographics, while Asian populations showed a very weak negative correlation.

### Housing and Building Units and Gun Permits

The second question was answered with the following conclusions:

- A positive correlation of 0.599 was observed between housing units and the total number of gun permits issued, indicating a moderate relationship.
- Variability in total gun permits against building permits was noted across states, with some states showing exceptionally high numbers of permits issued.
- A positive correlation was found between building permits and the total number of gun permits issued.

