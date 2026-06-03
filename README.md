# Data Cleanser for Healthcare Dataset

## Project Overview

The purpose of this project is to perform data cleaning and preprocessing on a synthetic healthcare dataset. The project focuses on handling missing values and detecting/treating outliers using different statistical and machine learning techniques.

This project is useful for preparing datasets before applying machine learning algorithms and data analysis techniques.

---

# Objectives

* Create a synthetic healthcare dataset
* Introduce missing values and outliers
* Analyze missing data
* Apply multiple missing value imputation techniques
* Detect and treat outliers
* Prepare a clean dataset for machine learning

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

# Dataset Features

The dataset contains the following healthcare-related features:

| Feature Name   | Description            |
| -------------- | ---------------------- |
| patient_id     | Unique patient ID      |
| age            | Patient age            |
| gender         | Gender of patient      |
| region         | Patient region         |
| bmi            | Body Mass Index        |
| blood_pressure | Blood pressure level   |
| cholesterol    | Cholesterol level      |
| glucose        | Glucose level          |
| disease_risk   | Disease risk indicator |

---

# Project Structure

```text
Data-Cleanser-Project/
│
├── healthcare_dataset.csv
├── clean_healthcare_dataset.csv
├── project.ipynb
├── README.md
```

---

# Part A — Missing Value Handling

The following techniques were used for handling missing values:

## 1. Mean Imputation

Used for numerical columns.

## 2. Mode Imputation

Used for categorical columns.

## 3. KNN Imputer

Uses nearest neighbors to estimate missing values.

## 4. MICE Imputer

Iterative machine learning based imputation method.

---

# Part B — Outlier Detection and Treatment

The following methods were used:

## 1. Z-Score Method

Detects extreme values based on standard deviation.

## 2. IQR Method

Uses quartiles to identify outliers.

## 3. Percentile Method

Caps values using upper and lower percentile limits.

## 4. Winsorization

Limits extreme values without removing rows.

---

# Part C — Final Clean Dataset

After preprocessing:

* Missing values were handled
* Outliers were treated
* Final dataset became suitable for:

  * Machine Learning
  * Data Analysis
  * Visualization
  * Predictive Modeling

---

# Visualizations Used

* Missing Value Heatmap
* Boxplots Before Outlier Treatment
* Boxplots After Outlier Treatment

---

# Installation

Install required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

---

# Run Project

```bash
jupyter notebook
```

Open the notebook and run all cells step by step.

---

# Results

* Missing values handled successfully
* Outliers detected and treated
* Clean dataset generated successfully

---

# Conclusion

This project demonstrates practical data preprocessing techniques used in real-world healthcare datasets. Proper data cleaning improves model accuracy and data quality significantly.

