# IRIS FLOWER Classification
## Overview 📝

The Iris flower dataset is a classic dataset introduced by the British statistician and biologist Ronald Fisher in his 1936 paper, The Use of Multiple Measurements in Taxonomic Problems. The dataset is often referred to as Anderson's Iris data set due to Edgar Anderson’s collection of the data. It consists of 50 samples from three species of Iris flowers: Iris-setosa, Iris-virginica, and Iris-versicolor. Four features were measured for each sample: sepal length, sepal width, petal length, and petal width, all in centimeters. This dataset is commonly used for classification tasks in machine learning, including support vector machines and other classification techniques.

## Objective 🎯

♦️ The Iris flower dataset consists of three species: setosa, versicolor, and virginica. These species can be distinguished based on their measurements. Now, imagine that you have the measurements of Iris flowers categorized by their respective species.<br>
♦️ Your objective is to train a machine learning model that can learn from these measurements and accurately classify the Iris flowers into their respective species.<br>
♦️ Use the Iris dataset to develop a model that can classify iris flowers into different species based on their sepal and petal measurements. This dataset is widely used for introductory classification tasks.

## Dataset 📑📊

The data set consists of 50 samples from each of three species of Iris <br>
🔺Iris setosa<br>
🔺Iris virginica<br>
🔺Iris versicolor <br>
Four features were measured from each sample (in centimetres):
🔘Length of the sepals<br>
🔘Width of the sepals<br>
🔘Length of the petals<br>
🔘Width of the petals<br>

## Model Training and Evaluation
### 1.Data Loading:

Load the dataset using pandas.
### 2.Data Exploration:

Display descriptive statistics and the first few rows of the dataset.
### 3.Data Preparation:

Split the dataset into features (X) and target (Y).<br>
Split the data into training and test sets using train_test_split.
### 4.Model Training:

Train a Logistic Regression model using the training data.
### 5.Model Evaluation:

Make predictions on the test data.<br>
Evaluate the model using accuracy score and classification report.
