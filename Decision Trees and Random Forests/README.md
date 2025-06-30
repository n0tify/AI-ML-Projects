 Decision Trees and Random Forests - Heart Disease Classification
✅ Objective:
To build and evaluate tree-based models (Decision Tree and Random Forest) to classify whether a patient has heart disease or not.

🛠️ Tools Used:
Python

Scikit-learn

Pandas

Matplotlib

Seaborn

Graphviz (for tree visualization, optional)

📂 Dataset:
Dataset Name: Heart Disease UCI Dataset

Source: Kaggle

Link: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

Target Variable: target (1 = Disease, 0 = No Disease)

✅ Project Highlights:
🎯 Tasks Performed:
Loaded and explored the dataset.

Checked target class distribution.

Preprocessed features (if needed).

Split data into train-test sets.

Trained a Decision Tree Classifier (max depth = 4).

Visualized the decision tree.

Trained a Random Forest Classifier (100 trees, max depth = 6).

Evaluated and compared both models.

Analyzed feature importance for Random Forest.

Saved all relevant visualizations.

✅ Model Performance:
Model	Accuracy
Decision Tree	~0.8390
Random Forest	~0.8511

✅ Visualizations Included:
🎨 Target Class Distribution (target_class_distribution.png)

🎨 Decision Tree Visualization (decision_tree_plot.png)

🎨 Random Forest Feature Importance (random_forest_feature_importance.png)

✅ Interview Level Learnings:
How decision trees work

Concept of entropy & information gain

Overfitting in decision trees and pruning (via max depth)

Why Random Forest reduces overfitting (bagging technique)

Feature importance interpretation

Model evaluation using Accuracy, Precision, Recall, F1 Score

✅ Folder Structure:
Decision Trees and Random Forests/
├── data/
│   └── heart.csv
├── notebooks/
│   └── decision_tree_random_forest.ipynb
├── visuals/
│   ├── target_class_distribution.png
│   ├── decision_tree_plot.png
│   └── random_forest_feature_importance.png
├── README.md
└── requirements.txt
