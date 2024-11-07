# Certification Prediction Project

This project aims to predict whether a student will become certified based on their training data using machine learning models. We explore **Logistic Regression** and **K-Nearest Neighbors (KNN)** classifiers and tune hyperparameters to select the best-performing model. This work also covers data preprocessing, model evaluation, and data visualization.

## Project Overview

We leverage two primary models in this project:
1. **Logistic Regression** with L2 regularization and hyperparameter tuning.
2. **K-Nearest Neighbors (KNN)** classifier with varying neighbors.

Both models are compared based on validation accuracy, and the best-performing model is used to make predictions on the test dataset.

## Dataset

- **Training Data**: `edx_train.csv`
- **Testing Data**: `edx_test.csv`
- Target Variable: `certified`

## Project Structure

The repository is organized as follows:
- **data/**: Contains training and testing datasets and output files.
- **notebooks/**: Jupyter notebooks for step-by-step analysis.
- **src/**: Source code for data preprocessing, model training, and evaluation.
- **results/**: Final outputs, plots, and tables.

## Key Files

- **data_preprocessing.py**: Functions for data cleaning, encoding, and imputation.
- **model_training.py**: Implements and trains both models, including hyperparameter tuning.
- **model_evaluation.py**: Compares model accuracy and generates accuracy tables.
- **utils.py**: Contains utility functions for file handling and data management.

## Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Certification-Prediction-Project.git
   cd Certification-Prediction-Project
