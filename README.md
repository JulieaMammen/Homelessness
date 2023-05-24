# Investigating Homelessness in the U.S.

The purpose of this project is to see if we can predict homelessness rates. Furthermore, to examine the relationship between local housing, market factors, policies, demographics, and more in relationship to the rates of homelessness. We will also investigate whether there are alternative modeling approaches that can outperform the models described in the HUD report.  

## Data
This projects uses the data set 
  05b_analysis_file_update.csv
  and the data dictionary 
  HUD TO3 - 05b Analysis File - Data - Dictionary.csv
 We also will utilize the Housing and Urban Development model produced in 2019 to see if there are alternative modeling approaches.

## Data Preparation

The steps taken to clean the data set involved ensuring there are no missing values, but also ensuring that there are no extreme outliers that can skew the data set.

The file the performs the data preparation is:
  JulieMammen-DATA 3320 Homelessness Data Preparation.ipynb

## Data Analysis
The steps taken to analyze the data involves creating multiple regression models such as lasso, ridge, and XGBoost, in order to answer our overall question. 

The file that performs the data analysis is:
  JulieMammen-DATA 3320 Homelessness Analysis.ipynb
