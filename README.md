# DNN3

# About Data
The data includes stats about patient 
the label data contains te probability of a patient booking an online appoinment 

# Preprocessing
The data has some anomolies like having negative values and some values that are greater than 1, those values were assumed to be wrongly recorded and were changed 
tp positive values below one 
then the data was split and standardzed

# Model
A basic dense neural network model was implmented to predict the probability of the data. To optimize the model keras tuner and randomsearch were used 
to search for the best hyperparameters and then the results of those hyperparameters are compared
