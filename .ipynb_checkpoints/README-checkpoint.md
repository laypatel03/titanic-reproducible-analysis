# Reproducible Titanic Survival Analysis

Course: CS 684 – Python and R for Data Science  
Spring 2026

## Overview

This project presents a fully reproducible end-to-end data science workflow analyzing passenger survival on the Titanic. The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), and predictive modeling using logistic regression and decision trees.

All results can be reproduced by cloning this repository and running the notebook.

Dataset Source:
https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

---

## Project Structure

titanic-reproducible-analysis/
│
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── titanic_full_analysis.ipynb
├── figures/
├── src/
├── .gitignore
└── environment.yml

---

## Setup Instructions

1. Clone repository:
   git clone https://github.com/yourusername/titanic-reproducible-analysis.git

2. Navigate into project:
   cd titanic-reproducible-analysis

3. Install dependencies:
   pip install -r requirements.txt

4. Run Jupyter:
   jupyter notebook notebooks/titanic_full_analysis.ipynb

---

## Key Findings

- Women had significantly higher survival rates than men.
- First-class passengers had dramatically higher survival probability.
- Engineered features such as Title and Family_Size improved predictive performance.
- Logistic Regression achieved ~82% accuracy and strong AUC performance.

---

## Reproducibility Statement

All datasets, figures, and outputs are generated programmatically.  
Running the notebook from top to bottom will recreate:
- Cleaned dataset
- Saved figures
- Model comparison results

No manual steps are required.