# Neural_Network_Charity_Analysis

## Overview of the analysis: 

With the knowledge of machine learning and neural networks, we use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 

Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing

What variable(s) are considered the target(s) for your model?

IS_SUCCESSFUL Column

What variable(s) are considered to be the features for your model?

Every Column except for target (IS_SUCCESSFUL) and the drop columns (EIN, NAME)

What variable(s) are neither targets nor features, and should be removed from the input data?

Columns that I dropeed are EIN, NAME, yes, they should be removed.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

![3 layer 80-30](https://user-images.githubusercontent.com/95401877/167766511-3ba399e9-b174-4ad3-a58e-f42132ad44ca.png)

3 layers, 80-30 neurons. "relu" and  "sigmoid" activation functions. 

![4 layers 80-10](https://user-images.githubusercontent.com/95401877/167766533-0b86bf5a-5781-4c50-b5c2-dd985450cd2b.png)

4 layers, 80-10 neurons. The same activation functions.

Because I hope to get higher performance.

Were you able to achieve the target model performance?

No, I tried different ways, but I cannot reach 75% the target model performance.

What steps did you take to try and increase model performance?

I did incease layers and changed the number of input features.


## Summary: 

After using the neuron network and optimization, we did not meet expectations and did not get more than 75% accuracy. So we could choose to use Random Forest classifiers due to their sufficient number of estimators and tree depth. Also we can get a faster performance than neural networks and could have avoided the data from being overfitted.
