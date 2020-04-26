# Naive Bayes Algorithm

### Basic Probability
* Probability of getting head/tail when you flip a coin is 0.5 i.e. 50%
* Similarly probability of getting queen from a deck of card is 4/52 i.e. 7.7 %

### Consitional Probability
* Unlike basic probability in conditional probability we know that the event A has occured and we are trying to predict the probability of B. i.e. What is probability of getting a queen of diamond. Here card type diamond is event A.
* So the consitional probability of getting a queen of diamond is represented as P(Queen/Diamond) = 1/13 i.e. 7.7%
* More general representation is P(A/B) = Probability of 'Event A' knowing that 'Event B' has already occured
* Thomas Bayes conditional probability equation is:
  P(A/B) = ( P(B/A) * P(A) ) / P(B)

### Naive Bayes
* So using Bayes conditional probability equation we can find the probability of certain events based on probability of some knwon events.
* Its called 'Naive' because it assumes the known events(features) are independent of each other. This makes our calculations little simpler

### Naive Base Classifiers
  #### Bernoulli Naive Bayes
  * It Assumes that all our features are binary, means they take only two values 0 and 1
  * e.g. 1 can represent spam mails where 0 can represent ham mails  
  #### Multinomial Naive Bayes
  * It is used when we have descrete data e.g. Movie rating from 1 to 5 as each rating will have certain frequency to represent  
  #### Gaussian Naive Bayes
  * Because of the assumtion of nominal distributions(bell curve) Gaussian Naive Bayes is used when all the features are continuos
  * E.g. IRIS flower dataset features(sepal width, sepal length, petal width, patal length) are continuous. We can t represent these features in terms of their occurance which means data is continuous

### Where its used
* Email spam detection
* Handwritten digit recognition
* Weather prediction
* Face detection
* News article categorization

### Code
* Part1: Use Titanic crash dataset from Kaggle and predict survival chance for passenger
  * Using 'Gaussian Naive Bayes Classifier  
  * [Notebook Reference](Naive_Bayes_Part1.ipynb)
* Part2: Spam email classification
  * Using 'Mulinomial Naive Bayes classifier'
  * We are going to use 'Count Vectorizer' technique for converting the mail body into numbers.
  * How it works: We will identify the unique words accorss all the mails and then find the count of each word in every mail. So we get the matrix with columns equal to no of unique words and rows equal to number of mails and each cell represent the count of that unique word(in that mail)
  * [Notebook Reference](Naive_Bayes_Part2.ipynb)
* Exercise:
  * Use wine dataset from sklearn.datasets to classify wines into three categories
  * Load the dataset and split it into test and traion
  * Train the model using Gaussian and Multinomial classifier and post the scores
  * Used trained model to perform some prediction on data
  * [Notebook Reference](Exercise_Naive_Bayes.ipynb)

### Reference
* [Naive Bayes classifier: A friendly approach](https://youtu.be/Q8l0Vip5YUw)
