# Mushroom Classification
Implementation of Logistic Regression, Naive Bayes model and K-nearest neighbour Model using sklearn libraries

# Logistic Regression :

* Logistic regression is a type of supervised learning algorithm used for classification problems. It is a linear model that is used to predict a binary outcome (1 / 0, Yes / No, True / False) given a set of independent variables.
* Logistic Regression is much similar to the Linear Regression except that how they are used. Linear Regression is used for solving Regression problems, whereas Logistic regression is used for solving the classification problems.

The logistic regression formula is as follows:

p(y=1|x) = 1 / (1 + e^-(b0 + b1x1 + b2x2 + ... + bn*xn))

where:

p(y=1|x) is the probability that the outcome y is 1 given the input variables x
e is the base of the natural logarithm
b0, b1, ..., bn are the model coefficients
x1, x2, ..., xn are the input variables
The outcome y is predicted to be 1 when the probability p(y=1|x) is greater than 0.5, and 0 otherwise.


# Naïve Bayes Classifier Algorithm : 

* Naïve Bayes algorithm is a supervised learning algorithm, which is based on Bayes theorem and used for solving classification problems.
* It is mainly used in text classification that includes a high-dimensional training dataset.
* Naïve Bayes Classifier is one of the simple and most effective Classification algorithms which helps in building the fast machine learning models that can make quick predictions.
* It is a probabilistic classifier, which means it predicts on the basis of the probability of an object.
* Some popular examples of Naïve Bayes Algorithm are spam filtration, Sentimental analysis, and classifying articles.

![image](https://user-images.githubusercontent.com/83088512/212376035-71bbba9d-aec6-4884-8eea-93fe065c8ee4.png)

# K-Nearest Neighbor(KNN) Algorithm :

* K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique.
* K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.

![image](https://user-images.githubusercontent.com/83088512/212376273-218b1a8e-8ea1-47e2-9d0e-ee05f8d6e5b2.png)

* K-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.
* K-NN algorithm can be used for Regression as well as for Classification but mostly it is used for the Classification problems.

![image](https://user-images.githubusercontent.com/83088512/212376468-42894519-fc8e-43e5-8083-cd5341dc021b.png)
