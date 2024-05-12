# Used cars price prediction
### Authored by Ahmad Zalmout

## Abstract

In this document, a dataset of used cars was used to predict the selling price of the car based on a selection of features, for instance, number of seats, distance travelled, engine size, and so on. <br>
The dataset was collected from [Used Car Price Dataset](https://www.kaggle.com/datasets/rishabhkarn/used-car-dataset). The collection of the dataset is not clearly stated however, after some heavy research it was concluded that the data might be collected from an Indian cars selling [website](https://www.cardekho.com/). <br>

The reasons being the following:
1. The presense of a column "Price(in lakhs)" and that is an indian numbering system used to refer to large amounts and is usually related to the currency Rupees.
2. Everytime a car in the dataset is searched online, it is found in this website mentioned having almost all the features present in the dataset.
<br>

In the document, regression models were used for predicting the price (in euro) after some heavy data cleaning.

## Introduction

This document is intended as a project for a Data Science student to practice some data exploration techniques and the use of limited knowledge in ML models to try to predict prices of used cars as acurate as possible.<br>
In this exercise, a number of ML regression models were used to examine which would produce better results than the other.<br>
The models were exposed to tuning in order to achieve the required results.

## Data Preprocessing

To work with ML models, a few steps are needed to prepare the data for prediction.
The techniques used in this project are the following:

1. Removing Redundant columns.
2. Renaming misleading column name.
3. Checking and removing "NA" values.
4. Checking and removing duplicate values.
5. Checking data consistency across each column.
    1. Making sure categorical columns contain only categories.
    2. Making sure numerical columns contain reasonable ranges of values.
6. Exploratory data analysis.

