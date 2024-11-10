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
- **Data Preprocessing/**: Source cde for data preprocessing.
- **Model Training and Evaluation/**: Source code for model training, and evaluation.
- **Results and Analysis/**: Final outputs, plots, and tables.

## Key Files

- **data_preprocessing.ipynb**: Functions for data cleaning, encoding, and imputation.
- **model_training_and_evaluation.ipynb**: Implements and trains both models, including hyperparameter tuning.
- **results_and_analysis**: Compare model accuracy and generates accuracy tables.

## Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Certification-Prediction-Project.git
   cd Certification-Prediction-Project
