# Identify Customer Segments with Arvato

This project was completed as a part of the course requirements of Udacity's Data Scientist Nanodegree certification.

## Project Overview

In this project, I worked with real-life data provided by Bertelsmann partners AZ Direct and Arvato Finance Solution. The data concerns two datasets: one with demographic information about the people of Germany and one with that same information for customers of a mail-order sales company.

Their main question of interest was to identify facets of the population that were most likely to be purchasers of their products for a mailout campaign. In other words, the objective was to identify under- and over-representation of customer segments between the two populations.

The project involved data wrangling and feature engineering to develop a functional analysis data set, using Principle Component Analysis and Kmeans to organise the general population into clusters and then compare those clusters between two datasets to see which of them comprise the main user base for the company.

## Python libraries used:

- NumPy
- pandas
- Sklearn / scikit-learn
- Matplotlib (for data visualization)
- Seaborn (for data visualization)

## Files

Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).

Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).

Data_Dictionary.md: Information file about the features in the provided datasets.

AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.

## Licensing
I am not allowed to publish the data provided by Arvato Financial Services due to the terms and conditions. In the notebook you will find my code and performed analysis on these datasets.
