# Iris Flower Classification with PySpark MLlib

## Overview
This project implements and compares three classification algorithms on the Iris dataset using PySpark MLlib:
- Decision Tree
- Random Forest
- Logistic Regression

All models are tuned using 5-Fold Cross Validation and Grid Search. Performance is evaluated using Accuracy, Precision, Recall, and F1-Score.

## Requirements
- Python 3.9
- PySpark
- scikit-learn
- pandas
- matplotlib
- numpy

## How to Run
1. Install dependencies: pip install pyspark scikit-learn pandas matplotlib numpy
2. Open `iris_final.ipynb` in Jupyter Notebook
3. Run all cells in order from top to bottom

## Results
| Model | CV F1 |
|-------|-------|
| Decision Tree | 0.9273 |
| Random Forest | 0.9535 |
| Logistic Regression | 0.9513 |

**Best Model: Random Forest (CV F1: 0.9535)**

## Project Structure
├── iris_final.ipynb    # Main notebook
└── README.md           # Project description
