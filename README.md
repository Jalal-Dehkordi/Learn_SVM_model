# Learn_SVM_model
Teaching and learning to use the SVM model of machine learning
# Iris Flower Classification using SVM Model

This project utilizes a Support Vector Machine (SVM) model for classifying iris flowers.

## Description

This repository contains a Jupyter Notebook project that demonstrates the use of Support Vector Machines (SVM) for classifying iris flowers based on their attributes.

## Introduction

In this project, we explore the famous Iris flower dataset and apply the SVM algorithm for flower classification. The Iris dataset consists of measurements for sepal length, sepal width, petal length, and petal width of three species: Iris setosa, Iris versicolor, and Iris virginica.

## Getting Started

To get started with this project, you can follow these steps:
Clone the repository to your local machine:   git clone github.com/Jalal-Dehkordi/Learn_SVM_model.git
Open the Jupyter Notebook file svm-project.ipynb using Jupyter Notebook or JupyterLab.
Run each cell in the notebook to see the code in action and understand the classification process using SVM.
## Exploratory Data Analysis
The notebook begins with exploratory data analysis (EDA) to visualize the Iris dataset. It includes pair plots and kernel density estimation (KDE) plots to analyze the relationships between various features and species.
## Train Test Split
The dataset is then split into training and testing sets using the train_test_split function from sklearn.model_selection.
## Training an SVM Model
An SVM model is trained on the training data using the SVC class from sklearn.svm.
## Model Evaluation
The model's predictions are evaluated using a confusion matrix and classification report from sklearn.metrics.
## Hyperparameter Tuning with GridSearchCV
Hyperparameters of the SVM model are tuned using GridSearchCV from sklearn.model_selection. Different combinations of hyperparameters are tested to find the best configuration.
## Results
The final SVM model, along with the hyperparameter-tuned model, provides accurate predictions for the iris flower species based on the input features.
## Conclusion
The Jupyter Notebook svm-project.ipynb showcases the entire process of iris flower classification using SVM. Feel free to explore the notebook, experiment with the code, and learn more about support vector machines.

