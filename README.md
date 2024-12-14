# DTSA-5509: Introduction to Machine Learning - Supervised Learning Project

## Overview
This repository contains the work for my Supervised Learning project, part of the DTSA-5509: Introduction to Machine Learning course. The project focuses on predicting the potability of water using classification algorithms. The dataset used contains various water quality parameters.

## Dataset
The dataset used in this project is `water_potability.csv`, which includes features like:
- **pH**
- **Hardness**
- **Solids**
- **Chloramines**
- **Sulfate**
- **Conductivity**
- **Organic Carbon**
- **Trihalomethanes**
- **Turbidity**
- **Potability** (Target)

The dataset can be found in this repository.

## Project Objectives
The primary goals of the project are:
1. To explore and preprocess the water potability dataset.
2. To build and evaluate classification models to predict water potability.
3. To analyze model performance and identify the most important features for classification.

## Tools and Technologies
The project was implemented using:
- **Python**
- **Jupyter Notebook**
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## Approach
1. **Exploratory Data Analysis (EDA)**:
   - Examined dataset properties, checked for missing values, and visualized feature distributions.
2. **Data Preprocessing**:
   - Handled missing values and normalized the dataset for better model performance.
3. **Model Training**:
   - Trained multiple classification models including:
     - Logistic Regression
     - Random Forest
     - Decision Trees
     - Support Vector Machine (SVM)
4. **Model Evaluation**:
   - Evaluated models using metrics like accuracy, precision, recall, and F1-score.
5. **Feature Importance Analysis**:
   - Identified key factors affecting water potability.

## Results
The trained model achieved satisfactory performance, with **Random Forest** yielding the highest accuracy among the models evaluated.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/kashan2a/DTSA-5509-Introduction-to-Machine-Learning-Supervised-Learning.git
