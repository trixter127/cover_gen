---
title: Machine Learning Algorithms
---
Machine Learning Algorithms form the core of machine learning processes, providing the computational methods necessary for systems to learn from data and make predictions or decisions. These algorithms can be categorized into different types, each suited for specific tasks such as regression, classification, and clustering. Understanding these algorithms is crucial for effectively implementing machine learning solutions.

### Common Types of Machine Learning Algorithms

Machine Learning Algorithms can be broadly categorized into three main types:

- **Regression** - Used to determine a numerical value, predicting "how much" or "how many."
- **Classification** - Assigns labels or categories to data points.
- **Clustering** - Groups similar data points together based on patterns or characteristics.

![[ML_Algos.png]]

## Regression Algorithms

Regression Algorithm calculated the co-relation between the input features and output(identifying the dependant and independent values of the input for the output ). Its prediction is always in continuous spectrum( its  always a number). Regression algorithms are employed when the goal is to predict a numerical value. Some commonly used regression algorithms include:

- **Decision Tree Regression** - Divides inputs into subsets to make decisions.
- **Neural Network Regression** - Classification problems (hand written digits classification)
- **LASSO Regression** - Its a form of Linear Regression that shrinks the input data values (good for true predictions rather than inferences)
- **Ridge Regression** - Its a method for analyzing multiple regressions and very similar to LASSO (good for true predictions rather than inferences)
- **Elastic Net Regression** - Hybrid of LASSO and Ridge
- **Linear Regression** - Modelling the relation between the Input features and outputs
- **Polynomial Regression** - Relationship between the dependent and independent variables are modelled to nth degree
- **Stepwise Regression** - form of fitting regression model where the choice of predictive features is automated and determined on the fly
- **Logistic Regression** - it is used to detect success or failure of an event (Note: Usually used for classification tasks)

### Deciding on the Best Regression Algorithm

Choosing the most suitable regression algorithm involves considering factors such as data exploration, goodness of fit, the objective of the model, and cross-validation.


## Classification Algorithms

Classification algorithms are designed to assign labels or categories to data points. They are commonly used in tasks such as image recognition, spam detection, and sentiment analysis. Based on the training data certain boundary conditions are determined by model and then these are applied to predict the target classification.
- Classifier  - algorithm that maps the data to the categories
- Classification Model - which predicts the classification of the target data
- Feature - individual measurable property
### Types of classification algorithms
- **Binary Classification** - Two class classification
- **Multi-class Classification** - More than two classifications
- **Multi-label Classification** - More than one label for the data
### Different classification algorithms
- **Support Vector Machine Algorithm** - Each item is plotted in n-dimension space (n: no of features), the vector lines are drawn between these and the best lines that separate the classifications into even distributions are picked to detect the classification.
- **Random Forest Algorithm** - these use decision trees and are created on the fly
- **Stochastic Gradient Descent Algorithm**  -
- **Logistic Regression Algorithm** - Used for binary classification usually, has a hypothesis based on sigmoid curve 
- **Naive Bayes Algorithm** - Detects the independence of the features , like if one feature is completely unrelated to others. Text based usages like spam
- **Decision Tree Algorithm** - Used for prediction in general, outcomes are result of various decisions
- **K-nearest neighbors algorithm** - Used for pattern recognition , data mining and intrusion detection, the algorithm based on the features of the input data predicts the classification we already know. 

## Clustering Algorithms

Clustering algorithms group similar data points together based on patterns or characteristics. This is useful in tasks such as customer segmentation or anomaly detection.

Its an **unsupervised learning** as it uses **unlabelled data** and then group them logically into **clusters**.

### Types of clustering algorithms
- **Density-based Algorithm** - Groups based on high concentration of data points 
- **Distribution-based Algorithm** - Groups based on probability that it belongs to certain cluster. 
- **Centroid-based algorithms** - Groups based on Geographic center of population of data points
- **Hierarchical-based algorithms** - Based on branches

### Different clustering algorithms
 - **K-means clustering algorithm** - its a centroid based algorithm , works better with smaller datasets , tries to minimize the variance between data points 
 - **DBSCAN clustering algorithm** - Density based algorithm
 - **Gaussian Mixture algorithm** - Fix inconsistently distributed data and then predict the distribution
 - **BIRCH algorithm** - works well Large Dataset, its a Hierarchical-based algorithm.
 - **Affinity propagation clustering algorithm** - 
 - **Mean-Shift clustering algorithm** - mode-seeking algorithm
 - **OPTICS Algorithm** 
 - **Agglomerative hierarchy clustering algorithm** - based on similarities merges datapoints into clusters
 