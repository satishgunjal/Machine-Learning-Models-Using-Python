
# Support Vector Machine (SVM)
* SVM algorithm is preferred by many as it provide more accurate results with less computational power
* SVM are mostly used for classification tasks but can also be used for regression tasks as well
* SVM is suited for extreame cases( where difference between feature is very small. e.g. cat which groomed like a Dog)
* So the SVM will looks at the extreame points in dataset and draws a boundary (line incase of 2D and hyperplane for more 2D) between those extreame points to separate the features. Which results in best possible segregation of classes
* Suport vectors are the data points which are close to the opposing class. SO SVM actually only consider these support vectors for defining the classification boundary and ignore's the other training examples
* e.g. suppose we have a dataset of dogs and cats. In that dataset there is a dog that looks like a cat and a cat thats is groomed like a dog. So our SVM algorithm will use these two extreame examples as support vectors and draws boundary to classify the dogs and cats classes. Since this boundary is based on extream examples(support vector) it will takes care of other training examples as well.
* SVM will use multiple such support vectors to classify dataset and increase the margin between to classes

## SVM parameters
* Gamma: In case of high value of Gamma decision boundary is dependent of points cloase it where in case of low value of Gamma decision SVM will consider the far away points also while deciding the decision boundary
* Regularization parameter(C): Large C will result in overfitting and which will lead to lower bias and high variance. Small C will result in underfitting and which will lead to higher bias and low variance

# Code
 1. We will use IRIS flower dataset from sklearn and try to predict the flower type
    [Notebook Reference](Support_Vector_Machine.ipynb)
    
 2. Exercise: Train SVM classifier using sklearn digits dataset to predict digit from 0 to 9.
    [Notebook Reference](Exercise_Support_Vector_Machine.ipynb)  

## References:

* [Support Vector Machine](https://youtu.be/FB5EdxAGxQg)
* [Support Vector Machine](https://youtu.be/Y6RRHw9uN9o)
* [Tutorial](https://towardsdatascience.com/support-vector-machine-introduction-to-machine-learning-algorithms-934a444fca47)
* [SVM Gamma Parameter](https://youtu.be/m2a2K4lprQw)
