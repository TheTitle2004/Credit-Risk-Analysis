# Credit Risk Profiling and Default Analysis

**Status: In Progress**

## Project Overview

This independent empirical project investigates the relationship between borrower characteristics and credit card payment-default outcomes using Python.

The study aims to develop an interpretable statistical approach to credit risk assessment, with future work focusing on probability-of-default modelling and validation.

## Dataset

- **Source:** UCI Machine Learning Repository
- **Dataset:** Default of Credit Card Clients
- **Observations:** 30,000 credit card clients
- **Period:** Taiwan, 2005
- **Explanatory variables:** 23
- **Dependent variable:** Next-month payment default (0 = No Default, 1 = Default)

Dataset: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis Completed

- Loaded and explored the dataset using Python.
- Examined variable definitions and descriptive statistics.
- Calculated the overall observed default rate of 22.12%.
- Compared average credit limits between defaulters and non-defaulters.
- Analysed default rates across five credit-limit groups.
- Created a bar chart showing default rates by credit-limit group.

## Preliminary Findings

Observed default rates decrease across increasing credit-limit groups, from approximately 31.79% in the lowest group to 11.17% in the highest group.

These findings describe associations within the historical sample and do not establish causation.

## Planned Work

- Data-quality assessment and cleaning
- Repayment-history analysis
- Logistic regression modelling
- Model evaluation and probability calibration
- Sensitivity and robustness analysis
- Final research report and methodology documentation

## Limitations

The dataset represents historical credit card clients in Taiwan and may not generalise to other populations or periods.

The project does not estimate Loss Given Default (LGD), Exposure at Default (EAD), or institutional credit ratings.

## Author

Shirshak Das  
M.A. Economics, IIT Madras