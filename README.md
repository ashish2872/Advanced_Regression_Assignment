# Advanced_Regression_Assignment
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
On the given dataset of the House Price Prediction, I have conducted the Exploratory Data Analysis and used multiple types of Regression models using advanced regression techniques to determine top 5 predictors

## Technologies Used
- Numpy
- Pandas
- Matplolib
- Seaborn
- ScikitLearn

## Conclusions 
1. Understanding the data - My first step was to understand what kind of data has been provided. 

2. Data Preparation and EDA  - Next I converted the categorical variables into their respective categories and performing the EDA on the numerial and categorical variables.

3. Dummy Variables creation - Next I created the dummy variables for the categorical variables, so the model efficiency increases.

4. Train-Test Split and Rescaling - In this particular step I split the dataset into 70:30 ratio and rescale the train dataset for all variables to be in the same interval.  

5. Training and Testing  the model - In this particular step, I used the RFE method to get the top 20 features and then run the model to get the train scores and test scores. From these scores I understood that the model is overfitting. So, I used the regularization technique by adding a penalty. I also used the Ridge and Lasso Regression techniques to determine the correct model 

