Iris Flower Classification

Overview

This repository contains a machine learning model for classifying Iris flower species using the famous Iris dataset. The dataset includes three species: Setosa, Versicolor, and Virginica, with features such as sepal length, sepal width, petal length, and petal width.

Dataset

The Iris dataset is a well-known dataset in the field of machine learning. It consists of 150 samples, with 50 samples per species. Each sample includes four numerical features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Project Structure

├── IRIS FLOWER PREDICTION.ipynb  # Jupyter Notebook with model training & evaluation
├── Untitled.ipynb                 # Python script for model training
├── README.md                      # Project documentation
├── requirements.txt               # Dependencies required to run the project
└── dataset/                        # (Optional) Directory for dataset files

Requirements

To run this project, install the required dependencies using:

pip install -r requirements.txt

Usage

Clone the repository:

git clone https://github.com/your-username/iris-flower-classification.git
cd iris-flower-classification

Open the Jupyter Notebook:

jupyter notebook "IRIS FLOWER PREDICTION.ipynb"

Run the notebook cells to:

Load the dataset

Perform data preprocessing

Train a machine learning model

Evaluate and test the model

Make predictions

Alternatively, you can run the Python script:

python Untitled.ipynb

Model

The project includes the following classification models:

Decision Tree Classifier: Trains a decision tree on the Iris dataset

k-Nearest Neighbors (KNN): (Model comparison is included)

Exploratory Data Analysis (EDA)

Computes a correlation matrix for numerical columns

Visualizes correlations using a heatmap

Results

After training and testing the model, the best-performing model achieves high accuracy in classifying the three Iris species. More details on model performance are available in the notebook.
