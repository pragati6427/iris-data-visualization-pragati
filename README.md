# Iris Dataset — Data Visualization

**Name:** Pragati Mathur
**Domain:** Data Science Internship — Synent Technology
**Task:** Task 2 — Data Visualization

---

## Objective
Perform exploratory data analysis (EDA) and visualize patterns in the Iris dataset to understand differences between three flower species: Setosa, Versicolor, and Virginica.

---

## Dataset
Classic Iris dataset — 150 samples, 4 features (sepal length, sepal width, petal length, petal width), 3 species, 0 missing values.

---

## Steps Performed
1. **Data Cleaning** — checked for nulls and duplicates, verified class balance
2. **EDA** — descriptive statistics and correlation analysis
3. **Bar Chart** — compared mean feature values across species
4. **Histogram** — analyzed feature distributions; found bimodal pattern in petal length
5. **Scatter Plot** — visualized species clusters; petal dimensions gave perfect separation
6. **Modeling** — trained KNN (k=5) and Decision Tree classifier

---

## Outcome
- Petal length and width are the strongest features for classifying species
- Setosa is completely separable using petal length alone (< 2.5 cm)
- Both models achieved 100% accuracy on the test set

---

## Tools Used
Python, pandas, numpy, matplotlib, seaborn, scikit-learn, Jupyter Notebook
