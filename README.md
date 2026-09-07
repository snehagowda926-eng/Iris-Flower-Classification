# Iris Flower Classification

## Project Description

Iris Flower Classification is a machine learning project that predicts the species of an Iris flower based on its physical measurements.

The project uses four measurements as input:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Using these measurements, the machine learning model classifies the flower into one of three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The Iris dataset is stored in this GitHub repository and loaded directly into the Google Colab notebook using Python.

## Objectives

- Understand the basics of classification in machine learning.
- Analyze and visualize the Iris dataset.
- Train machine learning classification models.
- Compare the performance of different models.
- Evaluate the models using accuracy, classification report, and confusion matrix.
- Use cross-validation to check model performance.
- Predict the species of a new Iris flower using user-provided measurements.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

## Machine Learning Models

The following classification algorithms are used:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest

The models are trained using the Iris flower measurements and their performance is compared using test data.

## Dataset

The project uses the Iris Flower Dataset containing measurements of three Iris species.

The dataset contains:

- 150 flower samples
- 4 input features
- 3 target classes

## Model Evaluation

The models are evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix
- 5-Fold Cross Validation

The average cross-validation accuracy obtained in the project is:

**96.00%**

## Prediction

The project also allows the user to enter measurements of a new Iris flower:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The trained model then predicts the flower species and displays the prediction confidence.

## Project Files

```text
Iris-Flower-Classification
│
├── Iris.csv
├── Iris_Flower_Classification.ipynb
├── requirements.txt
└── README.md
