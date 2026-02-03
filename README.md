# extrovert-vs-introvert-personality-prediction
EDA &amp; drift analysis for Kaggle Playground Series S5E7: Predict Introvert vs Extrovert from daily behavior features.
# Personality Predictor: Introvert or Extrovert

This repository contains an exploratory data analysis (EDA) notebook based on the Kaggle Playground Series Season 5 Episode 7 dataset. The goal of the project is to understand behavioral patterns that distinguish introverted and extroverted personalities.

The notebook focuses on data understanding and feature analysis. Model training is suggested as a future step but is not included in the current version.

---

## Dataset Information

Source: Kaggle Playground Series S5E7

Files used:
- train.csv
- test.csv
- sample_submission.csv

Target variable:
- Personality (Introvert / Extrovert)

---

## What is Covered in the Notebook

- Dataset overview and basic statistics
- Duplicate check
- Target class distribution
- Missing value analysis
- Numerical feature distributions
- Categorical feature analysis
- Outlier inspection
- Feature vs target relationship
- Correlation analysis
- Train–test distribution comparison
- Data drift check using Kolmogorov–Smirnov test

---

## Key Observations

- Missing values are moderate and evenly distributed across train and test sets.
- Behavioral features show clear separation between introverts and extroverts.
- Time_spent_Alone is the strongest indicator of personality type.
- No significant data drift is detected between training and test datasets.
- Outliers contain useful information and should not be removed aggressively.

---

## Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Missingno
- SciPy

---

## How to Run

### On Kaggle
1. Open the notebook in Kaggle.
2. Attach the Playground Series S5E7 dataset.
3. Run all cells.

### Locally
1. Download the dataset from Kaggle.
2. Update file paths inside the notebook.
3. Install required packages:
