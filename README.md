InternIntelligence_HyperparameterOptimization
This project was completed as part of my internship with @InternIntelligence, where I optimized the hyperparameters of a machine learning model to improve its performance. The techniques employed include Grid Search, Randomized Search, and Cross-Validation for fine-tuning the model.

📌 Objective
The primary objective of this task was to enhance the performance of a machine learning classification model by experimenting with different hyperparameters and evaluating their impact. The dataset used is the Breast Cancer dataset from scikit-learn.

🛠️ Techniques Used
Grid Search: Exhaustively searches through a manually specified subset of the hyperparameter space.

Randomized Search: Randomly samples a specified number of hyperparameter combinations from a specified range, providing a good balance between exploration and computational cost.

Cross-Validation: Used to assess the model's generalizability by splitting the data into training and validation sets multiple times.

📊 Model Performance
The project involved tuning the following hyperparameters:

n_estimators (number of trees)

max_depth (depth of each tree)

learning_rate (learning rate)

The model used is XGBoost (XGBClassifier), a powerful gradient-boosted tree algorithm.

📈 Key Results:
Improved model accuracy after hyperparameter optimization

Reduced overfitting and increased generalization
