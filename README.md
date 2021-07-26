# Neural_Network_Charity_Analysis

## Overview
The purpose of this project is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. In this analysis, we use a library in python called TensorFlow to evaluate data gathered from previous loans.

## Data Processing
What variable(s) are considered the target(s) for your model?
- IS_SUCCESSFUL is the variable we are targeting. 

What variable(s) are considered to be the features for your model?
- All columns except dropped ones would be considered to be the features for the model. 

What variable(s) are neither targets nor features, and should be removed from the input data? 
- NAME and EIN wouild be dropped first. Both of these features would have little to no impact on the outcome. 

## Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The deep-learning neural network model is made of two hidden layers with 80 and 30 neurons. These layers also have an activation funtion. The first and second hidden layers being 'relu' and 'sigmoid' being the outcome.

![Attempt_1](https://user-images.githubusercontent.com/80054925/126931487-4b3bf4f6-97f1-4ccf-b172-4d2953c05eb7.png)
