

# Logistic Regression Project

**Note:** This project was developed and tested primarily in **Google Colab**. All instructions and code are fully compatible with Colab, and the recommended way to run and reproduce results is via the Colab badge below.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/logistic-regression/blob/main/Logistische_regression.ipynb)

## Overview
This project demonstrates how to build and evaluate a logistic regression model using Python and scikit-learn. The model predicts whether a user will click on an ad based on features from the Advertising dataset. The notebook includes data exploration, visualization, model training, and evaluation.

## Contents
- `Logistische_regression.ipynb`: Jupyter notebook with the full workflow
- `Advertising.csv`: Dataset used for training and evaluation
- `requirements.txt`: List of required Python packages

## Dataset
The dataset (`Advertising.csv`) contains user information and whether they clicked on an ad. It is loaded automatically from the repository when running in Colab or Binder.

## How to Run


### Google Colab (Recommended)
1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom. The dataset loads automatically from the repository.
4. No manual data upload or extra setup is required.


### Local (Jupyter, also possible)
1. Clone or download this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook with Jupyter: `jupyter notebook Logistische_regression.ipynb`
4. Run all cells.

## Expected Results
- Data exploration and visualizations of user features
- Training of a logistic regression model
- Classification metrics (accuracy, confusion matrix, precision, recall, F1-score)
- Example output:

```
Accuracy: 0.9667
Confusion Matrix:
[[158   4]
 [  7 161]]
```


Example installation:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
