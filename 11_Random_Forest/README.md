# Introduction
1. Random forest is supervised learning algoriothm which is used for classification as well as regression. However it is mostly used for classfication problems
2. In Random forest algorithm dataset is devided in multiple batches and using 'Decision Tree' algorithm, gets prediction for each batch and then choose the best solution based on voting
3. We can understand the working of Random Forest algorithm with the help of following steps:
    - Step 1 − First, start with the selection of random samples from a given dataset.
    - Step 2 − Next, this algorithm will construct a decision tree for every sample. Then it will get the prediction result from every decision tree.
    - Step 3 − In this step, voting will be performed for every predicted result.
    - Step 4 − At last, select the most voted prediction result as the final prediction result.
    
## Pros
1. It overcomes the problem of overfitting by averaging or combining the results of different decision trees.
2. Random forests work well for a large range of data items than a single decision tree does.
3. Random forest has less variance then single decision tree.
4. Random forests are very flexible and possess very high accuracy.
5. Scaling of data does not require in random forest algorithm. It maintains good accuracy even after providing data without scaling.
6. Random Forest algorithms maintains good accuracy even a large proportion of the data is missing.

## Cons
1. Complexity is the main disadvantage of Random forest algorithms.
2. Construction of Random forests are much harder and time-consuming than decision trees.
3. More computational resources are required to implement Random Forest algorithm.
4. It is less intuitive in case when we have a large collection of decision trees.
5. The prediction process using random forests is very time-consuming in comparison with other algorithms.

# Code
1. We are going to use sklearns digits dataset to predict the digit from 0 to 9
   [Notebook Reference](11_Random_Forest/Random_Forest.ipynb)
   
2. Use iris flower dataset from sklearn.datasets to predict flower species using random forest classifier
   [Notebook Reference](11_Random_Forest/Exercise_Random_Forest.ipynb)
