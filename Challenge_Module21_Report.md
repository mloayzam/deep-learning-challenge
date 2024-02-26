###MODULE 21###

###OVERVIEW OF THE ANALYSIS:###

The purpose of this analysis is to develop a deep learning model to predict the success of funding applications submitted to Alphabet Soup, a nonprofit foundation. 
By utilizing historical data on various factors associated with funding applications, such as application type, affiliation, and use case, 
the goal is to create a predictive model that can accurately classify whether an application will be successful or not. 

###RESULTS:###

data preprocessing:

Target Variable: The target variable for the model is the "IS_SUCCESSFUL" column, which indicates whether an application was successful (1) or not (0).

Feature Variables: The feature variables for the model include all columns (EIN and NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANISTATUS, INCOME_AMT, 

Variables to be Removed: The "EIN" and "NAME" columns were removed from the input data as they are identifiers and not relevant for predicting application success.

compiling, training, and evaluating the model:

Model Architecture:

The neural network model consisted of six hidden layers with varying numbers of neurons (250, 120, 80, 50, 30, and 20) and the "tanh" activation function.

The output layer had one neuron with a sigmoid activation function, suitable for binary classification tasks.

Achievement of Target Model Performance:

The model achieved an accuracy of approximately 72.72% on the test dataset, with a loss of approximately 0.556.

Steps Taken to Increase Model Performance:

Increasing the number of hidden layers and number of neurons of the neural network architecture to capture more complex patterns in the data.

Changing the activation function from “relu” to "tanh" to potentially improve the model's performance in capturing nonlinear relationships.

###SUMMARY:###

Overall, the deep learning model developed for Alphabet Soup achieved a moderate level of performance, with an accuracy of approximately 72.72%. 
While this accuracy is satisfactory for many applications, further optimization may be beneficial to improve model performance. 




