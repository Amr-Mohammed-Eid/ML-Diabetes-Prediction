# Diabetes Prediction Project

This repository contains a simple machine learning project for predicting diabetes using the Pima Indians Diabetes Dataset.

## Files

- `diabetesprediction.ipynb` - Jupyter notebook with data loading, exploration, preprocessing, SVM model training, evaluation, and prediction example.
- `diabetes.csv` - Dataset used for training and testing the model.

## Project Overview

The notebook performs the following steps:

1. Load the diabetes dataset using `pandas`.
2. Explore the dataset shape, summary statistics, and outcome distribution.
3. Separate features (`x`) and target label (`y`).
4. Standardize feature values with `StandardScaler`.
5. Split the data into training and test sets.
6. Train an SVM classifier with a linear kernel.
7. Evaluate accuracy on training and test sets.
8. Demonstrate a prediction for one new sample.

## Requirements

Recommended Python packages:

- `numpy`
- `pandas`
- `scikit-learn`
- `jupyter` or `notebook`

## How to Run

1. Install required packages:

```bash
pip install numpy pandas scikit-learn jupyter
```

2. Open the notebook:

```bash
jupyter notebook diabetesprediction.ipynb
```

3. Run each notebook cell sequentially.

## Notes

- The notebook uses `svm.SVC(kernel='linear')` for classification.
- Input features are standardized before training and prediction.
- The example prediction takes a single record and prints whether the person is diabetic.

## License

This project is provided for educational purposes.
