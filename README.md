Iris Flower Classification:

This project demonstrates the use of Machine Learning to classify iris flowers into three species (Setosa, Versicolor, and Virginica) based on their sepal and petal measurements. The dataset used is the famous Iris Dataset introduced by Ronald Fisher in 1936.

Project Overview:

The goal of this project is to:

Load and clean the Iris dataset.

Explore the data through visualization.

Train a machine learning model to classify iris flowers.

Evaluate the model’s performance.

This is a beginner-friendly project to understand data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

Dataset Information:

Features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Target Classes:

Iris-setosa

Iris-versicolor

Iris-virginica

Dataset size: 150 samples (50 samples per class)

Technologies Used:

Python 3

Libraries:

numpy

pandas

matplotlib & seaborn (for visualization)

scikit-learn (for ML models)

Steps Involved:

Data Loading

Import the dataset using CSV file.

Data Preprocessing

Check for null values, duplicates, and clean the dataset if necessary.

Encode categorical labels.

Exploratory Data Analysis (EDA)

Summary statistics of features.

Pairplots, histograms, and scatter plots for feature relationships.

Model Building

Split dataset into training and testing sets.

Train models such as:

Logistic Regression

Decision Tree

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Model Evaluation

Accuracy score, confusion matrix, and classification report.

Compare performance across models.

Prediction

Test with new flower measurements.

How to Run

Clone this repository:

git clone https://github.com/your-username/iris-flower-classification.git
cd iris-flower-classification


Install dependencies:

pip install -r requirements.txt


Run the notebook or script:

jupyter notebook iris_classification.ipynb


 
Models like Logistic Regression, KNN, and SVM achieve high accuracy (~95–98%).

Confusion matrix shows clear classification with very few misclassifications.

Petal length and petal width are the most important features for classification.

Applications:

A classic benchmark dataset for machine learning beginners.

Can be extended to deep learning, deployment (Flask/Django), or real-time predictions.

Author:

MANOJ M

Contact: manojmanoj4624@gmail.com
