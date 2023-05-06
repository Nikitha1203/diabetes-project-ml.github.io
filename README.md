# diabetes-project-machine learning
This is a project to predict the likelihood of a person having diabetes based on various diagnostic measures. The project uses machine learning algorithms implemented in Python.

Table of Contents
Installation
Usage
Dataset
Model Selection
Evaluation
Conclusion
Dataset
The dataset used in this project is the Pima Indians Diabetes Database, which is publicly available on the UCI Machine Learning Repository. The dataset contains diagnostic measures for 768 women of Pima Indian heritage, and the goal is to predict whether or not each woman has diabetes.

Model Selection
Several machine learning algorithms were tested on the dataset, including Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, and Support Vector Machines. The Random Forest algorithm performed the best, with an accuracy of 78%.

Evaluation
The accuracy of the model was evaluated using k-fold cross-validation, which splits the dataset into k subsets and trains and evaluates the model k times. The mean accuracy across all k folds was used as the final accuracy metric.

Conclusion
This project demonstrates how machine learning can be used to predict the likelihood of a person having diabetes based on diagnostic measures. The Random Forest algorithm performed the best on the dataset, with an accuracy of 78%. This model could potentially be used to help identify individuals at risk for diabetes and provide early interventions.
