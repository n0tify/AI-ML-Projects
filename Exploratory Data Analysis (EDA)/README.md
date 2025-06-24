# 📊 Exploratory Data Analysis (EDA) - Titanic Dataset

This project performs Exploratory Data Analysis (EDA) on the Titanic Dataset to uncover patterns, trends, anomalies, and insights using visual and statistical techniques. The goal is to better understand the dataset and prepare for downstream machine learning tasks.

---

## 🧠 Objective

- Understand data using summary statistics and rich visualizations.
- Identify relationships, outliers, and patterns between variables.
- Build insights that can be leveraged for machine learning.

---

## 📂 Project Structure

Exploratory Data Analysis (EDA)/
├── data/
│ └── Titanic-Dataset.csv
├── notebooks/
│ └── eda.ipynb
├── visuals/
│ ├── missing_values_plot.png
│ ├── Embarked_distribution.png
│ ├── Sex_distribution.png
│ ├── Pclass_distribution.png
│ ├── Survived_distribution.png
│ ├── numeric_histograms.png
│ ├── pairplot_survived.png
│ ├── boxplot_*.png
│ ├── correlation_heatmap.png
│ └── interactive_scatter_plot.png
├── README.md
└── requirements.txt


## 📌 Key Tasks Performed

1. **Summary Statistics**  
   - Mean, median, standard deviation, etc.

2. **Missing Value Analysis**  
   - Detected and visualized missing values.

3. **Univariate Analysis**  
   - Histograms and boxplots for numeric features.

4. **Categorical Distributions**  
   - Count plots of `Sex`, `Pclass`, `Embarked`, etc.

5. **Bivariate & Multivariate Analysis**  
   - Correlation heatmaps
   - Pairplots by survival
   - Interactive scatter plots

6. **Outlier Detection**  
   - Visualized using boxplots.

---

## 📷 Sample Visualizations

Visuals are saved in the `visuals/` directory:
- Missing values bar chart
- Distribution plots
- Histograms for numerical features
- Correlation heatmap
- Interactive scatter plot using Plotly

---

## 📦 Libraries/Tools Used

| Library         | Purpose                                           |
|----------------|---------------------------------------------------|
| `pandas`       | Data manipulation and analysis                    |
| `numpy`        | Numerical operations                              |
| `matplotlib`   | Basic plotting and static visualizations          |
| `seaborn`      | Advanced statistical visualizations               |
| `plotly`       | Interactive plotting (used for scatter plots)     |
| `kaleido`      | Used with Plotly to export interactive plots as PNG |
| `jupyter`      | Interactive notebook environment                  |

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/n0tify/AI-ML-Projects.git
Navigate to the project:
cd "AI-ML-Projects/Exploratory Data Analysis (EDA)"

Install dependencies:
pip install -r requirements.txt

Launch the notebook:
jupyter notebook notebooks/eda.ipynb


❓ Interview Prep Questions
What is the purpose of EDA?

How do boxplots help in understanding a dataset?

What is correlation and why is it useful?

How do you detect skewness in data?

What is multicollinearity?

What tools do you use for EDA?

Can you explain a time when EDA helped you find a problem?

What is the role of visualization in ML?

🙌 Acknowledgements
Kaggle Titanic Dataset

Python Data Science Libraries

