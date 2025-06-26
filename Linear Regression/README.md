# Linear Regression - Housing Price Prediction 🏠

This project implements **Simple and Multiple Linear Regression** on the **Housing Price Prediction Dataset** from Kaggle.

---

## 📌 Objective:
To build a regression model that predicts house prices based on features like number of bedrooms, bathrooms, square footage, etc.

---

## 📂 Project Structure:

Linear Regression (Housing Price Prediction)/
├── data/
│ └── Housing.csv
├── notebooks/
│ └── linear_regression.ipynb
├── visuals/
│ ├── feature_correlation_heatmap.png
│ ├── predicted_vs_actual.png
│ └── residuals_distribution.png
├── requirements.txt
└── README.md


---

## 🧰 Libraries / Tools Used:

- **Python 3.x**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 🛠️ Key Steps:

1. **Data Import and Cleaning**
   - Loaded Housing Dataset
   - Checked and handled missing values
   - Converted categorical features using encoding (if any)

2. **Feature Exploration**
   - Visualized feature distributions
   - Plotted **Correlation Heatmap** to understand feature relationships

3. **Model Building**
   - Split dataset into **training** and **testing** sets
   - Applied **Linear Regression** using `sklearn.linear_model.LinearRegression`

4. **Model Evaluation**
   - Metrics: **MAE**, **MSE**, **RMSE**, **R² Score**
   - Plotted **Predicted vs Actual values**
   - Plotted **Residuals Distribution**

---

## 📈 Results:
📊 Model Performance Summary:
The initial linear regression model showed low performance and needs improvement.

Metric	  Value
MAE	      1,265,275.67
MSE	      2,750,040,479,309.05
RMSE	  1,658,324.60
R² Score  0.46 (Approx 46% variance explained)

> 💡 Note: Room for Improvement:

Apply feature scaling (StandardScaler / MinMaxScaler)

Try regularized regression models (Ridge, Lasso)

Engineer new features or remove outliers

Handle categorical variables more carefully

---

## 📌 Learning Outcomes:

- Linear Regression fundamentals
- Model evaluation metrics
- Visualization of regression results
- Recognizing when a simple model underperforms and how to improve

---

## 🏅 Interview Prep - Quick Questions:

1. What assumptions does Linear Regression make?
2. How do you interpret the coefficients?
3. What is R² score and why is it important?
4. When would you use MSE over MAE?
5. What is multicollinearity and how do you check for it?
6. Difference between simple and multiple regression?
7. Can linear regression handle classification tasks?
8. What happens if regression assumptions are violated?

---

✅ **Kaggle Dataset:**  
[Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

