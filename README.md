# Implementation-of-ML-algos-in-Python
In this repo, i will try to implement various machine learning algorithms from scratch and analyse best practices and advantages of using them. This repo can be a good start for anyone starting with machine learning and wants to get basic  intuition behind the theory and working of various common machine learing algorithms. The implementations are not efficient and are just meant as a source to learn and prepare for data science interviews. t<br>

**Nearest Neighbours**
1. [kNN(k nearest Neighbours)](https://github.com/jyotipmahes/Implementation-of-ML-algos-in-Python/blob/master/k-NN%20.ipynb): This notebook contains the implementation of kNN classifier and regressor along with various distance/similarity metrics that can be used for kNN. It also includes best ways of finding k value and how k impacts decision boundary. Time complexity is a major issue with kNN is demonstrated towards the end.

2. [Nearest Neighbors Search](https://github.com/jyotipmahes/Implementation-of-ML-algos-in Python/blob/master/Nearest%20Neighbors%20Search.ipynb) : kNN has linear time complexity and hence is very slow for large data set. In this notebook, we explore various **exact(kd tree, ball tree) and approximate(Locality Sensitive Hashing, ANNOY etc)** nearest neighbour search algorithms and basic logic behind each. We will implement some of these algorithms soon.

**Naive Bayes**
1. [Naive Bayes(categorical data)](https://github.com/jyotipmahes/Implementation-of-ML-algos-in-Python/blob/master/Naive_Bayes.ipynb): This notebook contains the basic theory behind Multinomial Naive Bayes and implements it from scratch. The notebook also covers various forms of Naive Bayes(**Binomial, Gaussian**) and the pro's and con's of using Naive Bayes algorithm.
2. [Gaussian Naive Bayes](https://github.com/jyotipmahes/Implementation-of-ML-algos-in-Python/blob/master/Gaussian_Naive_Bayes.ipynb): This notebook contains the implementation of Gaussian Naive Bayes algorithm and covers how to implement Binomial Naive Bayes.

**Decision Trees**
1. [Decision Tree Classifier](https://github.com/jyotipmahes/Implementation-of-ML-algos-in-Python/blob/master/Decision%20Tree%20Classifier.ipynb): This notebook contains the basic theory and implementation of Decision Tree Classifier. The notebook talks about various splitting criterion but uses Gini Index for implementation of Decision Tree Classifier.
2. [Decision Tree Regression](https://github.com/jyotipmahes/Implementation-of-ML-algos-in-Python/blob/master/Decision%20Tree%20Regression%20.ipynb): This notebook contains the implementation of Decision Tree Regressor with Mean Square Error as the splitting criterion. It also shows how to visualize decision trees.

**Random Forest**
1. [Random Forest Classifier and Regressor](https://github.com/jyotipmahes/Implementation-of-ML-algos-in-Python/blob/master/Random%20Forest%20Regressor%20and%20Classifier.ipynb): This notebook contains the implementation of both Random Forest Classifier and Regressor along with basic theory behind it.

**SVM**
1. [Support Vector Machines(SVM)](https://github.com/jyotipmahes/Implementation-of-ML-algos-in-Python/blob/master/SVM%20Classifier.ipynb): This notebook contains the basic theory and math behind SVM and implementing it from scratch. This notebook tries to solve convex optimization problem using gradient descent and talks about various efficient ways of solving optimization problems in python. 
