# Task-3-Exploratory-Data-Analysis-EDA-Elevate_Labs
# 📊 Exploratory Data Analysis (EDA) on Iris Dataset

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the classic **Iris dataset** using Python libraries:
- **Pandas** for data handling
- **Matplotlib** and **Seaborn** for visualization

The goal is to understand feature distributions, relationships, and identify which features are most important for predicting species.

---

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (recommended)

---

## 📂 Dataset
- **Iris Dataset**: Contains 150 samples of iris flowers across 3 species (*Setosa, Versicolor, Virginica*).
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species (target)

---

## 🔎 EDA Steps

### 1. Distribution of Numerical Features
- Histograms plotted for sepal and petal measurements.
- **Insight**: Petal features show bimodal distributions → strong species separation.

### 2. Categorical Features
- Count plot of species.
- **Insight**: Dataset is balanced (50 samples per species).

### 3. Outlier Detection
- Box plots for each feature grouped by species.
- **Insight**: Sepal width shows mild outliers; petal features clearly separate *Setosa*.

### 4. Correlation Heatmap
- Heatmap of feature correlations.
- **Insight**: Strong correlation between petal length and petal width; weak correlation among sepal features.

---

## 📈 Key Insights
- Petal length and petal width are the most discriminative features for classification.
- Sepal features overlap across species, making them less predictive.
- Dataset is balanced, so no class imbalance issues.
- Mild outliers exist in sepal width but do not significantly affect classification.


