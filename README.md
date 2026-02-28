# DECISION-TREE-IMPLEMENTATION


_COMPANY_: CODTECH IT SOLUTIONS


_NAME_: VAISHNAVI VILAS BANSUDE


_INTERN ID_: CTIS4923


_DOMAIN_: MACHINE LEARNING


_DURATION_: 4 WEEKS


_MENTOR_: NEELA SANTOSH KUMAR

DESCRIPTION OF TASK:

Title:
Decision Tree Classification Using Diabetes Dataset

Introduction:

This project focuses on implementing a Decision Tree classification model using Python and the scikit-learn machine learning library to predict whether a person has diabetes. Diabetes is a widespread and serious health condition that affects millions of people worldwide. Early detection and proper diagnosis are very important for effective treatment and prevention of complications. Machine learning techniques can analyze medical datasets and identify hidden patterns that may not be easily visible through manual analysis. By applying classification algorithms, healthcare professionals can receive support in decision-making processes. This project demonstrates how a Decision Tree algorithm can be applied to a real-world healthcare dataset to perform binary classification in a simple and interpretable manner.


Objective:

The main objective of this project is to build a machine learning model that can accurately classify patients as diabetic or non-diabetic based on their medical attributes. Another important objective is to understand the working principle of Decision Tree algorithms, including how they split data based on feature values. The project also aims to evaluate the model’s performance using appropriate evaluation metrics and to visualize the structure of the trained Decision Tree for better interpretability.


Dataset Description:

The Diabetes dataset used in this project contains several important medical attributes such as Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, Body Mass Index (BMI), Diabetes Pedigree Function, and Age. The dataset also includes a target variable called Outcome. Each record in the dataset represents the medical details of a patient. The Outcome column indicates whether the patient has diabetes (1) or does not have diabetes (0). The dataset is structured in tabular format and is commonly used for academic and research purposes in machine learning and data science.


Methodology / Implementation:

First, the required Python libraries such as pandas, numpy, matplotlib, and scikit-learn are imported. The dataset is loaded from a CSV file and examined to ensure it is correctly read. The data is separated into input features (X) and target labels (y). The dataset is then divided into training and testing sets, where 80% of the data is used for training and 20% is used for testing.
A Decision Tree Classifier is created using the Gini index as the splitting criterion. To prevent overfitting and maintain simplicity, the maximum depth of the tree is limited. The model is trained using the training dataset and then applied to the test dataset to generate predictions.


Model Evaluation:

The performance of the model is evaluated using accuracy, confusion matrix, and classification report. Accuracy measures the percentage of correct predictions made by the model. The confusion matrix provides detailed information about true positives, true negatives, false positives, and false negatives. The classification report includes precision, recall, and F1-score values, which help in understanding the quality of predictions for each class.


Visualization:

The trained Decision Tree is visualized using the plot_tree function from scikit-learn. The visualization clearly displays the decision rules, splitting conditions, feature names, and class labels. This graphical representation makes the model easy to interpret and understand.


Conclusion:

The Decision Tree classification model successfully predicts diabetes with reasonable accuracy. This project provides practical knowledge of machine learning implementation and improves understanding of classification algorithms in healthcare applications.

OUTPUT

<img width="1957" height="1175" alt="Image" src="https://github.com/user-attachments/assets/47c56757-1d5a-474c-919c-2320913c76a5" />
