# News-Headline-Classification

## Group members
1) Jayant Mukundam (Roll no. 44)
2) Chetan Naik (Roll no. 47) 
3) Sarthak Thakur (Roll no. 64)

## Problem Statement
Our project aims to build a machine learning model to classify the given set of news articles into 7 categories based on the news headlines.

## Dataset Description
The dataset contains various news articles & each article have following labels:  
 			 1) Headline.  
			 2) Brief description of the news.  
			 3) URL of the article.  
			 4) Date of publishing.  
			 5) Name of the news paper.  
			 6) Category.  
			
Each news article falls into one of the 7 categories namely sport, business, US based news, world, health, entertainment, science & technology. 

## Models implemented  
We have used three models to categorize the news headlines.

### 1) Support Vector Machine
Support Vector Machine is a supervised machine learning algorithm which can be used for both classification or regression challenges. However,  it is mostly used in classification problems. In the SVM algorithm, we plot each data item as a point in n-dimensional space with the value of each feature being the value of a particular coordinate. Then, we perform classification by finding the hyper-plane that differentiates the classes very well. 

### 2) Multinomial Naive Bayes
The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts. However, in practice, fractional counts such as tf-idf may also work.

### 3) Multilayer Perceptron
A multilayer perceptron (MLP) is a class of feedforward artificial neural network (ANN). An MLP consists of at least three layers of nodes: an input layer, a hidden layer and an output layer. Except for the input nodes, each node is a neuron that uses a nonlinear activation function. MLP utilizes a supervised learning technique called backpropagation for training.Its multiple layers and non-linear activation distinguish MLP from a linear perceptron.
