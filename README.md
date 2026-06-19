# 📊 Correlation Analysis and Visualization

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=28&duration=3500&pause=1000&color=00C9A7&center=true&vCenter=true&width=700&lines=Correlation+Analysis+%26+Visualization;California+Housing+Dataset;Python+%7C+Machine+Learning+%7C+Data+Analysis" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas">
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge">
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn">
</p>

---

## 📂 Project Structure

```text
Correlation-Analysis-and-Visualization/
│
├── Correlation_Analysis.ipynb      # Jupyter Notebook
├── Correlation_Report.pdf          # Project Report
├── requirements.txt                # Required Libraries
└── README.md                       # Project Documentation
```

---

## 🎯 Objective

The objective of this project is to analyze relationships between numerical variables using the **California Housing Dataset**. Correlation analysis helps determine how strongly features are related and assists in feature selection for machine learning models.

---

## 📊 Dataset

- **Dataset:** California Housing Dataset
- **Source:** Scikit-Learn
- **Samples:** 20,640
- **Features:** 8 Numerical Attributes
- **Target Variable:** Median House Value

---

## 🛠 Technologies Used

| Library | Purpose |
|----------|---------|
| 🐍 Python | Programming Language |
| 🐼 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Computation |
| 📈 Matplotlib | Data Visualization |
| 🎨 Seaborn | Statistical Graphics |
| 🤖 Scikit-Learn | Dataset Loading |

---

## 📌 Techniques Used

- ✔ Pearson Correlation Coefficient
- ✔ Correlation Matrix
- ✔ Heatmap Visualization
- ✔ Scatter Plot Analysis
- ✔ Feature Relationship Interpretation

---

## 📷 Visualizations

### 🔥 Correlation Heatmap

Shows the correlation among all numerical features.

```
Strong Positive  →  +1
No Correlation   →   0
Strong Negative  →  -1
```

---

### 📈 Scatter Plot

Visualizes the relationship between:

- Median Income
- Median House Value

A positive trend indicates that higher median income generally corresponds to higher house values.

---

## 📈 Correlation Strength Guide

| Correlation (r) | Interpretation |
|-----------------|----------------|
| 0.90 – 1.00 | Very Strong Positive |
| 0.70 – 0.89 | Strong Positive |
| 0.50 – 0.69 | Moderate Positive |
| 0.30 – 0.49 | Weak Positive |
| 0.00 – 0.29 | Very Weak / None |
| Negative Values | Negative Relationship |

---

## 🔍 Key Findings

✅ **Median Income (MedInc)** has the strongest positive correlation with **Median House Value**.

✅ Heatmaps make it easier to identify highly correlated variables.

✅ Scatter plots confirm positive linear relationships.

✅ Correlation analysis helps identify important features before training machine learning models.

---

## 🚀 Applications

Correlation analysis is widely used for:

- Feature Selection
- Data Exploration
- Multicollinearity Detection
- Regression Analysis
- Predictive Modeling
- Machine Learning Preprocessing

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Correlation-Analysis-and-Visualization.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook Correlation_Analysis.ipynb
```

---

## 📄 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## 📚 Learning Outcomes

After completing this project, you will understand:

- Pearson Correlation
- Correlation Matrix
- Heatmap Interpretation
- Scatter Plot Analysis
- Feature Selection
- Data Visualization

---

## 🎯 Conclusion

Correlation analysis is an essential step in Exploratory Data Analysis (EDA). It helps identify relationships among variables, remove redundant features, and improve machine learning model performance. Using heatmaps and scatter plots provides an intuitive understanding of data patterns and supports informed decision-making during model development.

---

## ⭐ If you found this project useful, consider giving it a Star!
