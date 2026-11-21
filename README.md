# Machine Learning in Finance — Model Tuning and Ensemble Experiments

This repository contains Jupyter notebooks from machine-learning coursework and experiments. The current notebooks focus on classification, model selection, hyperparameter tuning, and ensemble comparison.

> **Scope clarification:** Despite the original repository and notebook filename, the checked-in notebooks do not currently provide a complete multi-asset financial-return forecasting system or implementations of CNN-GAF/LSTM architectures. The experiments include synthetic finance-style features and a breast-cancer classification benchmark. Results must be interpreted in that context.

## Notebooks

### 1. [Deep learning finance return prediction notebook](Deep_learning_finance_return_prediction.ipynb)

The notebook includes:

- A synthetic binary-classification dataset with finance-style feature names.
- Baseline logistic regression.
- Grid search for logistic regression and support vector machines.
- Randomised hyperparameter search for random forests.
- Five-fold stratified cross-validation.
- Out-of-sample model comparison using accuracy, precision, recall, F1-score, and ROC-AUC.
- Validation-curve analysis and ensemble experiments.

The notebook contains saved outputs from previous execution. Re-run the cells in order to reproduce the analysis in your environment.

### 2. [MScFE 632 Group Work Project 2](The%20project%2001.ipynb)

This group-work notebook includes separate coursework sections covering:

- Hyperparameter optimisation on a synthetic finance-style classification dataset.
- Decision-tree depth comparison using the scikit-learn breast-cancer dataset.
- Bagging, boosting, and stacking experiments using a recreated synthetic finance-style dataset.

## Open in Google Colab

- [Open the first notebook in Colab](https://colab.research.google.com/github/Hillaryirungu/notebooks-Deep_learning_finance_return_prediction.ipynb/blob/main/Deep_learning_finance_return_prediction.ipynb)
- [Open the group-work notebook in Colab](https://colab.research.google.com/github/Hillaryirungu/notebooks-Deep_learning_finance_return_prediction.ipynb/blob/main/The%20project%2001.ipynb)

## Reproducibility

The notebooks use Python and common scientific-computing and scikit-learn libraries. The original notebooks do not include a pinned environment file. For consistent results, create a virtual environment and install compatible versions of NumPy, pandas, Matplotlib, and scikit-learn before running all cells from top to bottom.

Some datasets are generated synthetically in the notebook; the breast-cancer benchmark is loaded through scikit-learn. These are educational experiments and should not be presented as evidence of live-market forecasting performance.

## Author

**Hillary Irungu** · [GitHub](https://github.com/Hillaryirungu) · [Portfolio](https://hillaryirungu.github.io)

## License

See [LICENSE](LICENSE).
