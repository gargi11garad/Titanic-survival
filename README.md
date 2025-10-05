🛳️ Titanic Survival Prediction
📘 Project Overview

The Titanic Survival Prediction project is a classic machine learning task based on the famous Titanic disaster dataset. The goal is to build a model that predicts whether a passenger survived the tragedy, using various features such as age, gender, class, fare, and more.

This project demonstrates the complete machine learning workflow — from data preprocessing and visualization to model building, evaluation, and comparison across multiple algorithms.

🧠 Objective

To predict the survival of Titanic passengers based on passenger data and identify key factors that influenced survival outcomes.

📂 Dataset

The dataset used is the Titanic dataset available on Kaggle
.
It includes the following key columns:

PassengerId

Pclass

Name

Sex

Age

SibSp

Parch

Ticket

Fare

Cabin

Embarked

Survived (Target variable)

🧩 Project Workflow

Data Loading & Exploration

Loaded and explored the dataset using pandas and numpy.

Checked for missing values and data types.

Performed descriptive statistical analysis.

Data Cleaning & Preprocessing

Handled missing values (Age, Embarked, Cabin).

Converted categorical features (Sex, Embarked) into numerical using encoding.

Dropped irrelevant columns like Name, Ticket, Cabin for simplicity.

Scaled numerical features using StandardScaler.

Exploratory Data Analysis (EDA)

Visualized survival rate by gender, passenger class, age group, etc.

Used matplotlib and seaborn for data visualization.

Discovered that women and children had a higher survival probability.

Model Building
Implemented and trained multiple machine learning models including:

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree Classifier

Naive Bayes

Model Evaluation

Evaluated models using accuracy, confusion matrix, and classification report.

Prediction

Tested the model on unseen data.

🧾 Libraries Used

pandas

numpy

matplotlib

seaborn

scikit-learn




View results and model comparison charts.
