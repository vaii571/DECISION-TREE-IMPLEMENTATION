# DECISION-TREE-IMPLEMENTATION


_COMPANY_: CODTECH IT SOLUTIONS


_NAME_: VAISHNAVI VILAS BANSUDE


_INTERN ID_: CTIS4923


_DOMAIN_: MACHINE LEARNING


_DURATION_: 4 WEEKS


_MENTOR_: NEELA SANTOSH

DESCRIPTION OF TASK:

Title:
Decision Tree Classification Using Diabetes Dataset

Introduction:

This project focuses on implementing a Decision Tree classification model using Python and the scikit-learn machine learning library to predict whether a person has diabetes. Diabetes is a widespread health condition, and early detection plays an important role in effective treatment and management. Machine learning techniques can analyze medical data and discover hidden patterns that support clinical decision-making. This project demonstrates how a Decision Tree algorithm can be applied to a real-world healthcare dataset for classification.


Objective:

The main objective of this project is to build a machine learning model that can accurately classify patients as diabetic or non-diabetic based on their medical attributes. Another objective is to understand the working of Decision Trees and visualize how the model makes decisions.


Dataset Description:

The Diabetes dataset used in this project contains medical attributes such as Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, Body Mass Index (BMI), Diabetes Pedigree Function, Age, and a target variable called Outcome. Each record represents a patient, and the Outcome column indicates whether the patient has diabetes (1) or not (0). The dataset is commonly used for educational and research purposes.


Methodology / Implementation:

First, required Python libraries such as pandas, numpy, matplotlib, and scikit-learn are imported. The dataset is loaded from a CSV file and checked for correctness. The data is separated into input features (X) and target labels (y). The dataset is then divided into training and testing sets, with 80% used for training and 20% for testing.
A Decision Tree Classifier is created using the Gini index as the splitting criterion. To reduce overfitting and keep the model simple, the maximum depth of the tree is limited. The model is trained on the training data and used to predict outcomes for the test data.


Model Evaluation:

The model is evaluated using accuracy, confusion matrix, and classification report. Accuracy indicates the percentage of correct predictions. The confusion matrix shows the number of correctly and incorrectly classified instances. The classification report provides precision, recall, and F1-score values for each class.


Visualization:

The trained Decision Tree is visualized using the plot_tree function. The visualization shows decision rules, feature names, and class labels, helping to understand how predictions are made.


Conclusion:

The Decision Tree classification model successfully predicts diabetes with reasonable accuracy. This project provides practical experience in applying machine learning techniques and improves understanding of how Decision Trees can be used for healthcare classification tasks.
