# Assignment-Implementation-of-Decision-Tree-CART-
Assignment 1 
CART Decision Tree Project
Overview

This project demonstrates the implementation of a CART Decision Tree classifier using the Gini Index as the splitting criterion. The project uses a dataset to perform the following tasks:

    Train a decision tree using CART with the Gini Index on a dataset where all attributes are considered categorical.
    Train another decision tree using CART with the Gini Index on the same dataset, considering attributes as ordinal.
    Compare the performance of both models by evaluating accuracy, confusion matrix, and Gini Index at each node.

Project Structure

    train.csv: The dataset used for training the decision tree models.
    cart_project.py: The main script that implements the CART decision tree for both categorical and ordinal data.
    README.md: The file that provides an overview and instructions on how to run the project.

Requirements

To run the project, ensure that you have the following libraries installed:

bash

pip install pandas numpy scikit-learn seaborn matplotlib

Steps to Run the Project

    Clone or download the project files.
    Place the dataset (train.csv) in the working directory.
    Run the Python script cart_project.py to train the models and view results.

Project Workflow

    Data Preprocessing:
        For Task A: The attributes are treated as categorical.
        For Task B: The attributes are treated as ordinal using OrdinalEncoder.

    Model Training:
        A decision tree classifier is trained using the Gini Index criterion on both categorical and ordinal versions of the dataset.

    Performance Evaluation:
        The accuracy and confusion matrix of both models are evaluated and displayed.
        The Gini Index for each split/node of the tree is calculated and shown in tabular form.

Key Functions

    Training Decision Tree: Trains the CART decision tree using the Gini Index.
    Confusion Matrix: Displays confusion matrices for both categorical and ordinal models using Seaborn heatmaps.
    Gini Index Calculation: Outputs a table showing the Gini Index for each node of the decision tree.
