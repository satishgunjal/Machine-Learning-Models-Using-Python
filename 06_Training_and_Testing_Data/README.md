# Training and Testing Data

1. Its good practice to first randomly sort and the data then split into two parts. 80% of data for training the model and remaining 20% of the data for testing the model.
2. The reason we don't use same training set for testing is because our model has seen those samples before, using same samples for making predictions might give us wrong impression about accuracy of our model.
3. Here we are going to use sklearn.model_selection.train_test_split method

# Code
1. We have a dataset containing prices of used BMW cars. We are going to analyze this dataset and build a prediction function that can predict a price by taking mileage and age of the car as input
[Notebook Reference](Training_and_Testing_Data.ipynb)
