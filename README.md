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

Were you able to achieve the target model performance?
The goal was 75% accuracy. The model was not able to achieve that. 

![Results_1](https://user-images.githubusercontent.com/80054925/126931746-01c67f09-0095-4cff-81ca-4e8d619ff642.png)
![Results_2](https://user-images.githubusercontent.com/80054925/126931749-5978f35e-8fdf-4b75-bbcc-9861684bc57c.png)
![Results_3](https://user-images.githubusercontent.com/80054925/126931751-ecbd8ec2-29de-493c-a617-0e0e56eed47a.png)

What steps did you take to try and increase model performance? 
I tried adding more hidden layers and changing the output layer. I used tanh as an output layer but it did not improve reults. 

![Attempt_2](https://user-images.githubusercontent.com/80054925/126931875-c1acb40a-88e7-46f3-b723-87f840359d67.png)
![Attempt_3](https://user-images.githubusercontent.com/80054925/126932028-9ce5b51c-9297-4d7b-bae2-f5761fbff45b.png)
