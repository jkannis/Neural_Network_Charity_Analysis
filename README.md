# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis is to use neural networks machine learning to try to predict whether loan applicants will be successful if funded by Aphabet Soup.

## Results
### Data Preprocessing
- The target variable for this model is 'IS_SUCCESSFUL' as this model is meant to predict of borrowers will be successful.

![Target Variable](https://github.com/jkannis/Neural_Network_Charity_Analysis/blob/main/Resources/TargetVariable.png)

- The main features for this model are 'APPLICATION_TYPE', 'CLASSIFICATION', and 'USE_CASE'.

![Features](https://github.com/jkannis/Neural_Network_Charity_Analysis/blob/main/Resources/Fig1.png)

- The 'EIN' and 'NAME' variables are not needed for this model and were removed.

![Unneeded Variables](https://github.com/jkannis/Neural_Network_Charity_Analysis/blob/main/Resources/UnneededVariables.png)

### Compiling, Training, and Evaluating the Model
- The most successful model had two hidden layers using tanh activation functions. The first layer had 80 neurons and the second layer had 30 neurons.

![Neural Network](https://github.com/jkannis/Neural_Network_Charity_Analysis/blob/main/Resources/NeuronsLayers.png)

- This model missed the target performance by 2.5%.

- In the three attempts to increase model performance additional hidden layers were added, the number of neurons in the hidden layers were changed, and activation functions were changed.

## Summary

While this model did not reach the full target performance, the results may be acceptable for this type of project. I would recommend taking a closer look at the variables to determine which features contribute most to the target.