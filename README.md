# Crime Category Forecasting – Kaggle Competition

This repository contains my solution for the [Crime Cast: Forecasting Crime Categories] Kaggle competition. The goal is to predict the category of crimes based on various features from the provided dataset.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Approach](#approach)
- [Files in this Repository](#files-in-this-repository)
- [How to Run](#how-to-run)
- [Results](#results)
- [Requirements](#requirements)

---

## Overview

In this project, I performed exploratory data analysis (EDA), feature engineering, and built machine learning models to predict the `Crime_Category` for reported incidents. The notebook provides step-by-step insights into the workflow, from understanding the data to evaluating model performance.

---

## Dataset

The original datasets are available on the Kaggle competition page and include:

- `train.csv` – Training data with features and target labels (`Crime_Category`)
- `test.csv` – Test data for which predictions are to be made
- `sample.csv` – Sample submission format

---

## Approach

1. **Data Loading & Exploration**
   - Loaded and inspected the structure and summary statistics of the data.
   - Explored feature distributions, missing values, and relationships between variables.

2. **Feature Engineering**
   - Processed date and time features to extract useful information (e.g., month, day, hour occurred).
   - Handled categorical variables and missing values.

3. **Model Building**
   - Built and evaluated machine learning models for multi-class classification.
   - Compared model performance using appropriate metrics.

4. **Prediction & Submission**
   - Generated predictions on the test set.
   - Prepared the output file for Kaggle submission.

---

## Files in this Repository

- `22f3002119-notebook-t22024.ipynb` – Main Jupyter notebook with code, EDA, feature engineering, modeling, and results.
- `submission.csv` – Example output file for Kaggle submission (if included).
- `README.md` – Project documentation (this file).

---

## How to Run

1. **Download the data:**
   - Download `train.csv`and `test.csv`.
   - Place the files in a folder named `input` or update the notebook paths accordingly.

2. **Install dependencies:**
   - The notebook uses Python 3 and common libraries: `numpy`, `pandas`, `scikit-learn`, etc.
   - You can install dependencies using:
     ```
     pip install numpy pandas scikit-learn
     ```

3. **Run the notebook:**
   - Open `22f3002119-notebook-t22024.ipynb` in Jupyter Notebook or JupyterLab.
   - Run all cells sequentially to reproduce the analysis and results.

---

## Results

- The notebook includes performance metrics and visualizations for model evaluation.
- Final predictions are saved in `submission.csv` for submission to Kaggle.

---

## Requirements

- Python 3.x
- numpy
- pandas
- scikit-learn

[Notebook link](https://www.kaggle.com/code/kantpiyush2024/22f3002119-notebook-t22024)
