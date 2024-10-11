# Credit Score Classification

This project focuses on building a machine learning model to classify credit scores based on customer credit-related data. The task is to automate the process of categorizing credit scores to assist financial institutions in decision-making.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [References](#references)

## Overview
The goal of this project is to create an intelligent system that can classify individuals into different credit score brackets using machine learning techniques. This project is based on the Kaggle dataset: [Credit Score Classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification/data).

**Problem Statement**: Given a person's credit-related information, the task is to predict their credit score category to aid in credit approval processes.

## Dataset
The dataset contains various features related to an individual's financial and credit history, which include:
- **Age**: Age of the person.
- **Occupation**: Profession of the individual.
- **Annual Income**: Annual income in dollars.
- **Monthly Debt**: Total monthly debts in dollars.
- **Number of Bank Accounts**: Number of bank accounts held.
- **Number of Credit Cards**: Number of active credit cards.
- **Credit Score**: Target label - Low, Medium, or High.

The dataset is split into two sets:
- **Train Dataset**: Used for training the model.
- **Test Dataset**: Used for evaluating the model's performance.

## Project Structure
- `0_preprocess_data.ipynb`: Preprocessing steps.
- `1_notebook (description statistics).ipynb`: Exploratory Data Analysis and descriptive statistics.
- `2_notebook (features fixing + selection).ipynb`: Feature fixing and selection processes.
- `3_notebook_features_extraction.ipynb`: Feature extraction.
- `4_notebook_balancing.ipynb`: Handling class imbalance.
- `5_notebook_cv.ipynb`: Cross-validation and hyperparameter tuning.
- `6_notebook_tests.ipynb`: Final testing and model evaluation.
