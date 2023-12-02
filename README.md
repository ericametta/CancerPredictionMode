# Cancer Prediction Model
### Overview
This project aims to develop a predictive model for cancer classification based on genetic mutation data. It employs the use of decisions trees and then random forest approach, a powerful ensemble machine learning technique. The model predicts whether a given genetic sample is indicative of cancer (C) or non-cancer (NC). For feature engineering, we test both Phi selection method and information gain method.

### Features
- Implementation of a custom random forest algorithm.
- Decision trees built using a unique selection of features based on information gain.
- Out-of-bag (OOB) error estimation for model validation.
- Majority voting system for final classification in the random forest.

### Data
The dataset used in this project consists of genetic mutation features. Each sample (row) represents a different genetic profile, and each feature (column) corresponds to a particular genetic mutation, marked as 1 (present) or 0 (absent). The dataset includes a 'class' label for each sample indicating its cancer status ('C' for cancer, 'NC' for non-cancer).

### Structure
The project comprises several components:

Data Preprocessing: Scripts for cleaning and preparing the data for analysis.
Decision Tree Generation: Code to generate decision trees based on bootstrapped samples and random feature selection.
Random Forest Construction: An ensemble of decision trees, each contributing to the classification decision.
Classification and Validation: Functions to classify new samples and assess the model's performance using OOB samples.

### Usage
To use this model, follow these steps:

Data Input: Load your genetic mutation data in the required format.
Model Training: Run the feature engineering notebook to make best feature decisions and build the model.
Prediction: Use the model to classify new genetic samples as 'C' (cancer) or 'NC' (non-cancer).

