# Tumor Detection Project

## Overview
This project analyzes tumor characteristics to classify tumors as malignant or benign using machine learning. The workflow includes data cleaning, exploratory analysis, model training with a Random Forest Classifier, and visualization of results.

## Methodology
1. **Data Loading & Exploration:**
   - Loaded the Tumor_Detection dataset and explored its structure and missing values.
2. **Data Cleaning:**
   - Removed irrelevant columns and checked for missing values.
3. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of diagnosis labels.
   - Explored feature correlations using a heatmap.
4. **Data Preprocessing & Modeling:**
   - Encoded categorical labels and scaled features.
   - Split data into training and testing sets.
   - Trained a Random Forest Classifier and evaluated its accuracy.
5. **Visualization:**
   - Plotted feature importances and confusion matrix.

## Key Findings
- The Random Forest Classifier achieved high accuracy in classifying tumors as malignant or benign.
- Feature importance analysis revealed which tumor characteristics are most influential.
- The confusion matrix and classification report provided insight into the model's performance.
- Further improvements could include hyperparameter tuning, feature selection, or trying other classification algorithms.

## How to Run
1. Open the notebook `Tumor_detection.ipynb` in Jupyter or VS Code.
2. Run all cells in order to reproduce the analysis and visualizations.
3. Review the plots and summary for insights.

---

**Author:** Umang Dixit

**Date:** 13 August 2025
