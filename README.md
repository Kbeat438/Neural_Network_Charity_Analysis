# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of this analysis is to create a neural network binary classifier that is capable of predicting if funding from Alphabet soup will be successful

## Results: 
### Data Preprocessing
- What variable(s) are considered the target(s) for your model? 
The variable that is the target of this model is the IS_SUCCESSFUL variable
- What variable(s) are considered to be the features for your model?
Features of this model include AFFLIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL CONSIDERATIONS
- What variable(s) are neither targets nor features, and should be removed from the input data?
The two variables EIN and NAME are neither targets nor features and removing them helps optimize the training data.
 
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the optimized version of this model i used 150 nodes for layer 1 and then 75 for each hidden layer. I used 4 layers in the attempt of optimzing the layer beyond 75% because the model seemed to do better with more hidden layers and neurons. I used RELU for the first three layers and then sigmoid for the last three because that was the way the module seemed to preform the best. 
- Were you able to achieve the target model performance?
I was not able to achieve the target model performance. The target was 75% and my average accuracy was 72.5% and the highest my model could get was 74% 
- What steps did you take to try and increase model performance?
To increase model performance and optimize the results i added more neurons, deleted the status column, added more hidden layers, changed the number of epochs, changed the activation function, and tried different combinations of the max number for binning. 
## Summary: 
The results for this model were a 72.5% accuracy score with a .56 loss metric. It is not an optimal option for predicting if a loan is going to be successful or not. The next step would be to try a random forest classifer because it is better at compiling data that is right-skewed such as this. 
