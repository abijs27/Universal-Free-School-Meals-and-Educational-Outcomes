# Universal-Free-School-Meals-and-Educational-Outcomes

This repository contains an analysis of universal free school meals and educational outcomes from the 2014-2015 to 2018-2019 academic years for Pennsylvania schools. 

The Universal_Free_School_Meals_and_Educational_Outcomes.ipynb Jupyter notebook contains visualizations of the adoption of and participation in the Community Eligibility Provision (CEP), Keystone exam placements, and school dropout rates, as well as the estimated average effect of CEP adoption on Keystone exam placements and school dropout rates for the schools that adopted CEP (average treatment effect on the treated [ATT]).

The excel (.xlsx) files (with the exception of Data_Dictionary.xlsx) are the original datasets from the Pennsylvania Department of Education website (https://www.pa.gov/agencies/education).

The .csv files are the original datasets converted to the csv format. 

The final combined dataset for analysis is titled school_df.csv. (Note: I recommend against downloading and re-uploading this file for analysis as many school identification numbers start with 0s, and 0s can be stripped during the download/upload process. Please run the Data Cleaning portion of the Universal_Free_School_Meals_and_Educational_Outcomes.ipynb Jupyter notebook to import the individual csv files in this repository and create the school_df DataFrame.)

The Data Dictionary.xlsx spreadsheet contains a data dictionary for all columns in the school_df DataFrame.
