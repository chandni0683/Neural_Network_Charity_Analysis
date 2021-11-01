# Neural_Network_Charity_Analysis

## Overview of the analysis
With the knowledge of machine learning and neural networks, we use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization. We will be Preprocessing Data for a Neural Network Model, Compile, Train, and evaluate the Model and optimize the Model. 

## Results

### Data Preprocessing
What variable(s) are considered the target(s) for your model?

Column IS_SUCCESSFUL is considered the target for this model.

What variable(s) are considered to be the features for your model?

The other columns APPLICATION_TYPE,	AFFILIATION	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS and ASK_AMT are considered to be the features of the model.


What variable(s) are neither targets nor features, and should be removed from the input data?

The name and EIN columns are dropped as they are neither targets nor features.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Two hidden layers were created. Both layers use the Relu as a activation function.

Were you able to achieve the target model performance?
The first model predicts following results:


What steps did you take to try and increase model performance?
