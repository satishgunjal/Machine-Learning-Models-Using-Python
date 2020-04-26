# Naive Bayes Algorithm

### Basic Probability
* Probability of getting head/tail when you flip a coin is 0.5 i.e. 50%
* Similarly probability of getting queen from a deck of card is 4/52 i.e. 7.7 %

### Consitional Probability
* Unline basic probability in conditional probability we know that the event A has occured and we are trying to predict the probability of B. i.e. What is probability of getting a queen of diamond. Here card type diamond is event A.
* So the consitional probability of getting a queen of diamond is represented as P(Queen/Diamond) = 1/13 i.e. 7.7%
* More general representation is P(A/B) = Probability of 'Event A' knowing that 'Event B' has already occured
* Thomas Bayes conditional probability equation is:
  P(A/B) = ( P(B/A) * P(A) ) / P(B)

### Naive Bayes
* So using Bayes conditional probability equation we can find the probability of certain events based on probability of some knwon events.
* Its called 'Naive' because it assumes the known events(features) are independent of each other. This makes our calculations little simpler

### Where its used
* Email spam detection
* Handwritten digit recognition
* Wheather prediction
* Face detection
* News article categorization

### Code
* Part1: Use Titanic crash dataset from Kaggle and predict survival chance for passenger
  [Notebook Reference](/Naive_Bayes_Part1.ipynb)
* 

### Reference
* [Naive Bayes classifier: A friendly approach](https://youtu.be/Q8l0Vip5YUw)
