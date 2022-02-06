# Problem Statement
Classifying whether a person is successful or not related to age and interest

# Dataset
The dataset used is the Beginner's Classification (https://www.kaggle.com/sveneschlbeck/beginners-classification-dataset) from Kaggle

The class labels are
  1. age
  2. interest
  3. success

# Model used
**Logistic Regression:**

Logistic regression (LR) is basically a supervised classification algorithm. In a classification problem, the target variable(or output), y, can take only discrete values for a given set of features(or inputs),X. The model builds a regression model to predict the probability that a given data entry belongs to the category numbered as “1”. Just like Linear regression assumes that the data follows a linear function, Logistic regression models the data using the sigmoid function. The setting of the threshold value is a very important aspect of Logistic regression and is dependent on the classification problem itself. In this particular case, LR is binomial, i.e., target variable can have only 2 possible types: “0” or “1” which represent "caffeine is not present in considerable amount" for "0" and vice-versa.
