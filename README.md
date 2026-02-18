# probability-bayes-decision-trees

This repository contains my work for an assignment on probability, Naïve Bayes classification, and decision trees.

## Contents

- `notebook.ipynb`: Main Jupyter notebook with all parts (A–D).
- Additional notebooks or scripts if applicable.
- This `README.md`.

## Part A: Probability in Practice

- Simulated 1000 experiments of 10 fair coin flips.
- Plotted the distribution of the number of heads.
- Computed the empirical probability of getting exactly 5 heads.
- Used the Titanic dataset to compute:
  - P(Survived | Female)
  - P(Female | Survived)

## Part B: Naïve Bayes Classification

- Used the Titanic dataset with features: sex, class, and age.
- Encoded categorical variables using one-hot encoding.
- Trained a Gaussian Naïve Bayes classifier.
- Evaluated the model using accuracy and a confusion matrix.
- Discussed strengths (simplicity, speed) and weaknesses (independence assumption, sensitivity to correlated features).

## Part C: Decision Trees

- Trained a `DecisionTreeClassifier` on the same features.
- Visualized the tree structure.
- Evaluated accuracy and confusion matrix.
- Analyzed feature importances (e.g., sex and class as key predictors).
- Experimented with different `max_depth` values to observe underfitting/overfitting behavior.

## Part D: Responsible AI Reflection

- Reflected on ethical issues such as bias and fairness in models trained on historical data.
- Discussed how to communicate uncertainty and model limitations to non-technical audiences.

## How to Run

1. Clone the repository.
2. Install dependencies (e.g., `pip install -r requirements.txt` or ensure `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn` are installed).
3. Open `notebook.ipynb` in Jupyter Lab/Notebook and run all cells.
