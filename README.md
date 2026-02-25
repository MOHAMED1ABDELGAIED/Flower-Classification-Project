🌸 Flower Classification Project
📌 Project Overview

This project focuses on building a machine learning model to classify iris flowers into three species: Setosa, Versicolor, and Virginica using the Iris dataset.

The project workflow includes:

Exploring and analyzing the dataset (EDA)

Creating new features to improve classification (Feature Engineering)

Training two models: Logistic Regression and Decision Tree

Evaluating models using accuracy and confusion matrices

Building a simple command-line interface (CLI) to predict species for new samples

📂 Dataset

The Iris dataset contains 150 samples with 4 main features:

Sepal Length (cm) – the length of the sepal

Sepal Width (cm) – the width of the sepal

Petal Length (cm) – the length of the petal

Petal Width (cm) – the width of the petal

Target – the flower species (0 = Setosa, 1 = Versicolor, 2 = Virginica)

1️⃣ Exploratory Data Analysis (EDA)

In this step, we:

Checked the distribution of flower species

Summarized the dataset to understand feature ranges and statistics

Visualized relationships between features using scatter plots and pair plots

Observed correlations between different features

2️⃣ Feature Engineering

To improve model performance, new features were created from the original ones:

Petal Area – calculated by multiplying petal length by petal width

Sepal Area – calculated by multiplying sepal length by sepal width

Petal-to-Sepal Ratio – petal area divided by sepal area

Petal Sum – sum of petal length and width

These features help better separate Versicolor and Virginica, which are sometimes difficult to distinguish using only the original features.

3️⃣ Model Training

The dataset was split into training and testing sets. Two models were trained:

Logistic Regression: a linear model that predicts the probability of each species

Decision Tree: a model that splits the feature space into regions to classify samples

After training, predictions were made on the test set to evaluate performance.

4️⃣ Model Evaluation

Models were evaluated using:

Accuracy – percentage of correctly classified samples

Confusion Matrix – visualizing which species were correctly or incorrectly classified

Observations:

Logistic Regression achieved 100% accuracy after feature engineering

Decision Tree achieved 90% accuracy, with some misclassifications between Versicolor and Virginica

Feature Engineering significantly improved the Logistic Regression performance

5️⃣ CLI Prediction Script

A simple command-line interface was built so that users can input flower measurements (sepal length & width, petal length & width) and get a predicted species.

This demonstrates how the trained model can be deployed for practical use.

📌 Dependencies

To run this project, the following tools and libraries are needed:

Python 3.x

pandas for data manipulation

numpy for numerical operations

scikit-learn for machine learning models and evaluation

seaborn and matplotlib for visualization

joblib for saving and loading models

6️⃣ Conclusion

Feature Engineering can improve model accuracy significantly

Logistic Regression performed perfectly with the new features

Decision Tree may require tuning to reach the same performance

The project demonstrates the full ML workflow:
EDA → Feature Engineering → Modeling → Evaluation → Deployment
