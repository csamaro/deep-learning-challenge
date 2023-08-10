# Deep Learning Challenge

## Overview:
In this module, I worked to create a binary classification model that can predict whether applicants will be successful if funded by Alphabet Soup.
I did this by first processing data using Pandas and scikit-learn's Standard Scaler(). Then, utilizing Tensorflow, I compiled, trained, and evaluated a neural network model.

## Data Preprocessing:
### What variable(s) are the target(s) for your model?
- The column titled "IS_SUCCESSFUL" is where I am getting the target variables being used for my 'y'
### What variable(s) are the features for your model?
- The columns titled "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT" are the features for my 'X'
### What variable(s) should be removed from the input data because they are neither targets nor features?
- When I first read in the data, I dropped the columns "EIN", "NAME". These columns can be harmful in a deep learning model, since the values are usually distinct for each row.

## Compiling, Training, and Evaluating the Model
### How many neurons, layers, and activation functions did you select for your neural network model, and why?
- 
### Were you able to achieve the target model performance?
- Although I was not successful in reaching a 75% accuracy score, the model's accuracy results were at 72.8%.
### What steps did you take in your attempts to increase model performance?
- 
