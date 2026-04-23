#Iris Flower Classification using Decision Tree
Overview

This project builds a machine learning model to classify iris flowers into three species:

Setosa
Versicolor
Virginica

The model uses a Decision Tree Classifier from Scikit-learn and evaluates its performance on test data.

Dataset

The dataset used is the classic Iris dataset, containing:

Sepal Length
Sepal Width
Petal Length
Petal Width
Species (Target)

Ensure the file iris.csv is present in the project directory.

Technologies Used
Python
Pandas
Scikit-learn
How It Works
Load dataset using Pandas
Split data into training and testing sets
Train a Decision Tree model
Make predictions on test data
Evaluate using:
Accuracy Score
Confusion Matrix
Classification Report
Model Details
Algorithm: Decision Tree Classifier
Train-Test Split: 80% Training / 20% Testing
Random State: 42
How to Run
Step 1: Install dependencies
pip install pandas scikit-learn
Step 2: Run the script
python your_script_name.py
Output

The script will display:

Accuracy of the model
Confusion Matrix
Classification Report (Precision, Recall, F1-score)
