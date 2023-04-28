# Neural_Network_Charity_Analysis


## Overview of Project
    The purpose of the this analysis is to determine whether at is capable of predicting whether the  applicants will be successful if funded by Alphabet Soup charity. The analysis was realized using machine learning and neural networks. This involved taking a deep dive into neural networks starting from a given dataset

## Results

- Data Preprocessing 
       * What variable(s) are considered the target(s) for your model?  
       The column IS_SUCCESSFUL is considered to be the target of our model, as it designates whether the charity has been used.
       * What variable(s) are considered to be the features for your model?
       The features for the model given are given by the following columns: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
       * What variable(s) are neither targets nor features, and should be removed from the input data?
        The EIN and NAME columns are neither targets nor features and this determinated us to remove them form the dataset.
        
- Compiling, Training, and Evaluating the Model 
        * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    In this model there are two hidden layers each with 80 neurons. The first activation function was 'relu' but the 2nd and 3rd were 'sigmoid'and the output function was 'sigmoid'. We increased the number of neurons on one of the hidden layers, then we used a model with three hidden layers.

Summary

As a conclusion, we have observed that the neural network model has not reached its target of 75% accuracy

 It is recommended the  Random Forest model because Random Forest  as a supervised machine learning techniques, as it is good for classification problems. Using this model produces a 78% accuracy, 
