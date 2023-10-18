# EDA on Lending Club Loan data
Lending Club is a Consumer Finance company for who is interested to understand if a new loan application can be accepted or rejected.
We have a dataset with loan data that are currently active, paid off or charged-off. 
We are advising the company with driver variables to avoid credit loss using EDA.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
- We have done univariate and bivariate analysis on the dataset. We have derived metrics which is required.
- We have made assumptions based on publicly available domain information.
- As data imputations can’t be reliably done, this step is skipped and the columns with empty values are dropped from analysis.
- We have also not considered the loan data for the currently active loans as we can’t predict drivers from this.
- Also, we have dropped customer behavior variables as this will be unique and can’t be used to generalize/ aggregate the data.

## Technologies Used
- Python

## Acknowledgements
- References 
https://towardsdatascience.com/how-to-clean-your-data-in-python-8f178638b98d
https://realpython.com/python-data-cleaning-numpy-pandas/
https://towardsdatascience.com/a-complete-guide-to-plotting-categorical-variables-with-seaborn-bfe54db66bec
https://poulami98bakshi.medium.com/univariate-and-bivariate-analysis-an-easy-guide-2139dd286d4b
