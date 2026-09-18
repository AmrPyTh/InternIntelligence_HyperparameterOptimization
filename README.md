# XGBoost Hyperparameter Optimization

Hyperparameter optimization project completed during the InternIntelligence internship. It compares Grid Search and Randomized Search for an XGBoost classifier on the scikit-learn Breast Cancer dataset.

## Dataset

- 569 samples
- 30 numerical features
- Binary classification: malignant or benign
- Train/test split: 80/20 with random state 42

## Approach

- Built an XGBClassifier with mlogloss evaluation
- Tuned n_estimators, max_depth, and learning_rate
- Compared GridSearchCV and RandomizedSearchCV
- Used 3-fold cross-validation with accuracy as the scoring metric
- Evaluated the best estimators using precision, recall, F1-score, and accuracy

## Results

| Search method | Best parameters | Test accuracy |
|---|---|---:|
| Grid Search | learning_rate=0.1, max_depth=3, n_estimators=100 | 96% |
| Randomized Search | learning_rate=0.05, max_depth=3, n_estimators=150 | 96% |

Both approaches achieved a weighted F1-score of 0.96 on the 114-sample test set.

## Technologies

Python · XGBoost · Scikit-learn · Pandas · NumPy · Jupyter Notebook

## Repository contents

- Code.ipynb — data loading, model tuning, evaluation, and results
- Task.png — internship task reference
