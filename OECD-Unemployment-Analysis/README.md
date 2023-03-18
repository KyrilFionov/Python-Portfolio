# OECD-Unemployment-Analysis: Pandas | Plotly | Dash

## Background

In this project I analyze 22 years of data from the Organization for Economic Co-operation and Development (OECD) on Unemployment rates. Data is at monthly level and some dates are missing values

Primary goal of this projects was to create a Dash dashboard.

## Questions Addressed
* Provide an overview on the Unemployment Rate trends for OECD countries.
* Which countries had the smallest/highest average Unemployment Rate for a particular reporting period?
* Which countries had the smallest/highest change in Unemployment Rate for a particular reporting period?
* What was the minimum/maximum Unemployment Level achieved within the particular reporting period and what were the corresponding countries?


## Methods and Functions used
PANDAS
* Treating NaN values (filling empty fields)
* Changing column types (to_numeric, to_datetime, astype)
* Adding columns
* Using the .apply() method
* Using groupby to perform aggregate analysis

PLOTLY/DASH
* Automatically creating subplots figures depending on the dataset dimensions.
* Formatting/Stylihg figures and divisions
* Creating callback functions (dynamic filters)

## How to navigate
1. OECD_Unemployment_Analysis_Input.csv is an input file for the analysis
2. OECD_Unemployment_Analysis_Github.ipynb file contains Python script
3. Run the script and click the output link to open the Dashboard in your browser
