# Does Borrower Socioeconomic Background Affect Financial Relief in Student Loan Complaints?

## Overview

This project examines whether borrower socioeconomic background affects the likelihood of receiving financial relief in private student loan complaints filed with the Consumer Financial Protection Bureau (CFPB). Using OLS/Linear Probability Models with clustered standard errors, we find that higher-income borrowers and those in areas with higher educational attainment are more likely to receive relief, consistent with mechanisms of borrower sophistication and firm-side discrimination.

## Data Sources

Data used in this project must be downloaded separately before running the notebook:

- CFPB Student Loan Complaints: Consumer Financial Protection Bureau — download and save as ‘consumer_complaints.csv’ in the *Final Project/* folder
- ACS Census Data (2014, 5-year estimates): U.S. Census Bureau — ‘DP03’ (economic characteristics) and ‘S1501’ (educational attainment), save in *Final Project/*

## Methods

- OLS / Linear Probability Model with zipcode-clustered standard errors
- Socioeconomic regressors: log median income, poverty rate, unemployment rate, bachelor's degree attainment
- Web scraping: CFPB enforcement actions and Navient press releases
- Machine learning: Random Forest for robustness check
