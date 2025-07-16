# Decision Tree Classifier – Credit Risk Prediction

This project applies a Decision Tree Classifier to predict whether an individual is a good or bad credit risk, based on demographic and financial information. The dataset used is sourced from OpenML and contains various customer attributes.

## Objective

The goal is to build a machine learning model that can classify customers as creditworthy or not based on their data. This can help financial institutions in making informed lending decisions.

## Dataset

- **Source**: OpenML Dataset #31
- **Link**: https://www.openml.org/d/31
- **Format**: CSV
- **Target Variable**: `class` (binary classification)

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Steps Involved

1. Import required libraries
2. Load the dataset from a remote source
3. Encode categorical variables using Label Encoding
4. Split the dataset into features (`X`) and target (`y`)
5. Perform train-test split using `train_test_split()`
6. Train a Decision Tree Classifier on the training set
7. Predict on the test set
8. Evaluate model performance using accuracy score, classification report, and confusion matrix

## How to Run

1. Clone the repository or download the `.ipynb` notebook
2. Install the required libraries using pip:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
