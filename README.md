# Cancer Classification using SVM and PCA

This project implements a machine learning pipeline to classify cancer data using dimensionality reduction (PCA) and a Support Vector Machine (SVM). The dataset undergoes preprocessing, feature selection, and evaluation to determine classification performance.

## Features
- Exploratory Data Analysis with heatmaps and statistics
- Data preprocessing (dropping IDs, standardization)
- Principal Component Analysis (PCA) for dimensionality reduction
- Support Vector Machine (SVM) classifier
- Evaluation using accuracy and classification report

## Dataset
The project expects a file named 'cancer_data.csv' to be in the root directory. It should contain features like patient measurements and a target class.

## How to Run
1. Clone the repository
2. Add the 'cancer_data.csv' dataset to the project folder
3. Open and run 'main.ipynb' in Jupyter Notebook or Google Colab

## Requirements
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
