# Advanced Regression House Prices Study
This project shows EDA and Lasso and Ridge regression on house prices in Australia.


## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Methods Used](#Methods-Used)
* [Conclusions](#conclusions)
* [Technologies Used](#Technologies-Used)
* [Language](#Language)
* [IDE](#IDE)
* [Files](#Files)
* [Acknowledgements](#acknowledgements)


## Problem Statement
A US Based company is trying to enter Australian Market trying to understand the market based on the previous sale data from Australia. The outcome of the regression model analytics to be used by the company to make decisions on if the company should buy the properties or not (enter the market) and also help the company understand how the house prices change with variables/features provided in the dataset.

Key Points company is looking to find out are 

- Which variables are significant in predicting the price of a house 
- How well those variables describe the price of a house.

During the process aim is also to find optimal lambda and lasso regression value.

## Methods Used

__These are the steps used in the case study to understand, visualise, anlyze and predict data :__

- Read the file, understand the data, remove any duplicates, derive/delete columns/rows if needed, convert columns and visualize the data to see the behaviour (EDA, Exploraroty Data Analysis)
- Data Preparation
- Then the data will be split into trained and test data and train data will be rescalled 
- Feature Selection
- Lasso,Linear and Ridge Regression Model Building
- Decision making

## Conclusions

__Ridge Regression__

From the graph on ridge regression train and test it can be seen that 

Train Score : As the lambda increases this makes the r2 score to decrease, this suggests that it leads to error to be increasing. This is suggesting that the design is becoming more generalised than overfitting. By increasing the alpha the design becomes more generalised.

Test Score: At the lower value of ridge the error is high.From the graph we can see that as the alpha is increasing the error starts decreasing up to the peak point. After the peak point the error is increasing and alpha is decresing. 


__Lasso Regression__


From the graph on ridge regression train and test it can be seen that


Train Score : Error is low at the starting point of lasso regression with fairly high r2 score and slowly peaking to optimal alpha then reducing down gradually as the error increases and design becomes more generalised and simple.

Test Score: Test score follows the same path as the Train score in terms of behaviours.





__TOP TO FEATURES BASED ON THIS WOULD BE__


- __GrLivArea__
- __OverallQual__
- __LandContour_Lvl__
- __OverallCond__
- __BsmtQual__
- __GarageArea__
- __FireplaceQu__
- __Condition1_Norm__
- __Foundation_PConc__
- __Exterior2nd_CmentBd__

## Technologies Used
* Pandas : 1.2.3
* numpy : 1.20.3
* matplotlib: 3.5.2
* seaborn : 0.11.2
* scikit-learn : 0.20.3
* statsmodels : 0.9.0

## Language
* Python

## IDE
* jupyter Notebook

## Files
* .pynb file -- jupyter file containing the code
* .pdf file -- subjective questions
* .csv file -- data set


## Acknowledgements
* https://scikit-learn.org/stable/modules/model_evaluation.html 
* https://stackoverflow.com/questions/17778394/list-highest-correlation-pairs-from-a-large-correlation-matrix-in-pandas
* https://stackoverflow.com/questions/35827863/remove-outliers-in-pandas-dataframe-using-percentiles


## Contact
Edwin Mathew 
