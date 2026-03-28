# Translating an R Machine Learning Workflow into Python

**Name:** Natchapa Aunkay (Gift)
**Course:** DNSC 6330 – Responsible Machine Learning
**Instructor:** Prof. Michael Akinwumi
**Assignment:** Individual Homework 1

---

## 1. Purpose of the Analysis

This project reproduces a complete machine learning workflow originally developed in R using Python. The objective is to implement all major analytical steps—data preprocessing, exploratory data analysis (EDA), modeling, and evaluation—in Python while ensuring consistency with the original R results.

The analysis uses the COMPAS dataset to:

* Understand the structure and key characteristics of the data
* Build a logistic regression model to predict COMPAS risk scores
* Evaluate model performance using classification metrics
* Analyze fairness by comparing performance across racial groups

---

## 2. Python Libraries Used

The following libraries are used:

* pandas
* numpy
* matplotlib
* seaborn
* statsmodels
* scikit-learn

Install them using:

pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

---

## 3. Instructions for Reproducing the Results

### Step 1: Clone the repository

git clone https://github.com/gifyncp/assignment1-rML-Natchapa.git
cd assignment1-rML-Natchapa

---

### Step 2: Run the analysis

#### Option A: Jupyter Notebook (Recommended)

jupyter notebook

Open the notebook file and run all cells from top to bottom.

#### Option B: Python script

python compas_analysis.py

---

### Step 3: Workflow Overview

1. Load COMPAS dataset from GitHub
2. Clean and preprocess data
3. Perform exploratory data analysis (EDA)
4. Train logistic regression model
5. Evaluate model performance
6. Analyze fairness across racial groups

---

## 4. Reproducibility and Documentation

* The code is fully reproducible
* Each step is clearly commented
* The workflow follows the same structure as the R implementation

---

## 5. Notes

* Minor differences between Python and R results may occur
* These differences do not affect the overall conclusions
