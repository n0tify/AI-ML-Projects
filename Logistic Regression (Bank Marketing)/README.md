📈 Classification with Logistic Regression - Bank Marketing Campaign
📌 Objective:
Build a binary classification model to predict whether a customer will subscribe to a term deposit using Logistic Regression.
---
📂 Dataset Used:
Bank Marketing Campaign Dataset

📥 Kaggle Link: Bank Marketing Dataset : https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
---

🛠️ Tools & Libraries Used:
Python

Pandas (Data handling)

Matplotlib / Seaborn (Visualization)

Scikit-learn (sklearn) (ML modeling, evaluation)
---

✅ Folder Structure:
Logistic Regression/
├── data/
├── notebooks/
├── visuals/
├── README.md
└── requirements.txt
---
🔍 Project Workflow:
Data Loading & Exploration

Preprocessing

Encoding categorical variables

Scaling numerical features

Splitting Data (Train-Test)

Logistic Regression Model Building

Model Evaluation Metrics:

Confusion Matrix

Classification Report

ROC-AUC Curve
---
Visualizations:

Target Class Distribution

Confusion Matrix Heatmap

ROC-AUC Curve
---
✅ Model Performance:
Metric	Value
Accuracy	0.7976 (~80%)
Precision	0.7959
Recall	0.7703
F1 Score	0.7829

              precision    recall  f1-score   support

           0       0.80      0.82      0.81      1175
           1       0.80      0.77      0.78      1058

    accuracy                           0.80      2233
   macro avg       0.80      0.80      0.80      2233
weighted avg       0.80      0.80      0.80      2233
---
📌 Interview Level Learnings:
Difference between Linear Regression vs Logistic Regression

What is a Sigmoid Function

Precision, Recall, F1-score definitions

ROC-AUC Curve meaning

Handling Class Imbalance

How to interpret a Confusion Matrix

Threshold tuning and its impact on Precision vs Recall
---
📊 Output Visuals:
All generated output plots are saved in the /visuals/ folder, including:

✅ Target Class Distribution

✅ Confusion Matrix Heatmap

✅ ROC-AUC Curve

✅ Classification Report Heatmap
---
✅ Requirements:
Install dependencies with:
pip install -r requirements.txt

---
This project provided hands-on experience in binary classification using Logistic Regression on real-world marketing data.
