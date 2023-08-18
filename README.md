## Report on the Performance of Deep Learning Model for Alphabet Soup

## Overview of the Analysis:
The purpose of this analysis is to develop a binary classifier using a deep learning model that can predict whether applicants will be successful if funded by Alphabet Soup, a nonprofit foundation. The goal is to assist Alphabet Soup's business team in selecting applicants for funding with the best chance of success in their ventures. The analysis involves utilizing various features provided in a dataset containing metadata about organizations that have received funding from Alphabet Soup.

## Results:

Data Preprocessing:  

Target Variable: IS_SUCCESSFUL (Binary variable indicating whether the money was used effectively)  
Feature Variables: EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
Variables to Remove: EIN and NAME (Identification columns), as they are not relevant for prediction.  

Compiling, Training, and Evaluating the Model:  

Neurons, Layers, and Activation Functions: The neural network model comprises three layers. The input layer has neurons equal to the number of features, the hidden layer(s) have neurons determined through experimentation, and the output layer has a single neuron with a sigmoid activation function. The sigmoid activation is suitable for binary classification tasks.  
Target Model Performance: The target model performance, defined by accuracy, was set at 75%.  
Steps for Improving Model Performance: In attempts to enhance model performance, various steps were taken, including experimenting with different activation functions(op1) adjusting the number of neurons and hidden layers(op2), tuning hyperparameters (batch size op3).  

## Summary:
The deep learning model achieved an accuracy of 74%, surpassing the target performance of 75%. Still need more improve
