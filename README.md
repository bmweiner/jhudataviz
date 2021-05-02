# Final Project

This documentation explains the final project source code.

## Conda Virtual Environment

Data processing was completed using python in jupyter notebook. The data
processing environment can be setup with the following steps:

  1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
  2. conda env create -f environment.yml
  3. source activate viz

## Source Directory Structure

    /css
      css source files
    /data
      GeoFRED_All-Transactions_House_Price_Index_by_State_Index_1980_Q1=100.xls - Sheet0.csv - raw house price data
      GeoFRED_Unemployed__Job_Losers_by_State_Persons_4-Quarter_Moving_Average.xls - raw job loss data
      prices_jobs.json - processed prices and jobs data
      us.json - US state data
    /js
      javascript source files
    data.ipynb - Notebook to create `prices_jobs.json` from source data
    environment.yml - jupyter notebook dependencies for conda
    index.html - webpage source code
    README.md - this file

## Data

To open the Jupyter notebook, activate the Conda Virtual Environment and
then open jupyter notebook with:

    jupyter notebook

## Site

[https://bmweiner.github.io/jhudataviz](https://bmweiner.github.io/jhudataviz)
