# 🔐 Logistic Regression from Scratch

Implementation of a **Logistic Regression model from scratch**, without using `scikit-learn`.  
Only **NumPy**, **Pandas**, and **Matplotlib** are used for numerical operations and visualizations.

This repository includes both a practical application on a real dataset and additional visualizations for better conceptual understanding.

---

## 📊 Dataset
- The dataset used is **[possum data](https://www.kaggle.com/datasets/abrambeyer/openintro-possum)** from Kaggle.  
- The main logistic regression model determines the **sex of a possum** based on multiple features in the dataset.  

---

## 🚀 Model Performance

- **Optimization:** Gradient Descent  
- **Evaluation Metric:** Accuracy  
- **Final Accuracy:** `73.63%`  
- **Training Visualization:** Convergence of the cost function over iterations  

![Cost vs Iteration](Images/output.png)

---

## 📂 Additional Visualizations
A separate notebook (`Logistic_Regression_Visuals.ipynb`) is included for better intuition.  
This notebook uses **synthetic data** and provides visualizations:

- **Sigmoid Function Alignment & Decision Boundary Visualization**  
  Shows how the sigmoid curve fits to the data distribution.
  
![sigmoid](Images/logistic.gif)

- **Contour Plot of Cost Function**  
  Demonstrates the optimization path taken by gradient descent.

![contour](Images/contour.gif)

---
