# Logistic Regression Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/logistic-regression/blob/main/Logistische_regression.ipynb)

This repository reproduces the Logistic Regression exercise from the course `Python für Data Science, Maschinelles Lernen & Visualization` for `Prüfungsaufgabe 1`.

## Overview

This project demonstrates how to build and evaluate a logistic regression model using Python and scikit-learn. The model predicts whether a user will click on an ad based on features from the Advertising dataset. The notebook includes data exploration, visualization, model training, and evaluation.

## Contents

- `Logistische_regression.ipynb`: Jupyter notebook with the full workflow
- `Advertising.csv`: Dataset used for training and evaluation
- `requirements.txt`: List of required Python packages

## Dataset

The dataset (`Advertising.csv`) contains user information and whether they clicked on an ad. It is loaded directly from the repository when running the notebook.

## How to Run

### Google Colab (Recommended)

1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom in order.
4. No manual data upload is required.

### Local (Jupyter)

1. Clone or download this repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook with Jupyter:

```bash
jupyter notebook Logistische_regression.ipynb
```

4. Run all cells from top to bottom.

## Expected Results

The notebook should reproduce the logistic regression example on the Advertising dataset and show:

- data exploration and visualizations
- logistic regression model training
- classification report
- accuracy
- confusion matrix

Example output:

```text
Accuracy: 0.9667
Confusion Matrix:
[[158   4]
 [  7 161]]
```

## Notes

This repository is intended as one of the required exercise repositories for `Prüfungsaufgabe 1`.
