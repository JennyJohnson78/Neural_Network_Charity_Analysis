# Neural Network Charity Analysis

## Overview

Alphabet Soup is non-profit, philanthropic organization that helps charities that serve the environment and people's well-being. More than 34,000 organizations have received funding from Alphabet Soup. Using machine learning and neural networks via the TensorFlow platform in Python, a binary classifier will be created, one capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Results

### Data Preprocessing

- The feature that is being targeted in this dataset is the IS_SUCCESSFUL column.
- The features being used are every column (APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT)  
except the ones that will be dropped.
- The featuress to be dropped are the EIN and NAME columns.

### Compiling, Training, and Evaluating the Model

The model with the highest accuracy rate was 72.6% accurate.

- 120 neurons were used, spread across three layers (80, 30, and 10). The activation functions used were ReLU for hidden layers 1-3, and sigmoid for the output layer.
- It was not possible to reach 75% accuracy with any model. After consulting with two other colleagues, they divulged that they were not able to reach 75% accuracy either.
- In an attempt to reach 75% accuracy, the number of neurons on one of the hidden layers were increased, and then a model with three hidden layers was used. When these modifications did not work, the tanh activation function was tried. None of these increased the model's accuracy.

## Summary

This model achieved 72.6% accuracy with 55.7% data loss. Although the model did not achieve 75% accuracy, it did come close. If this model were being used to predict outcomes in medicine among patient diagnosis, this would not suffice, but for this purpose, the model comes close to the accuracy desired. The best way to increase the accuracy of the model would be to have more data. More data would make the accuracy of the model stronger.

![image](https://user-images.githubusercontent.com/67409852/151640445-91fc5edc-9988-43f8-a8d3-81e64e07bc85.png)

