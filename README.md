# 🔐 Logistic Regression from Scratch

An implementation of **Logistic Regression** built entirely from scratch,  
using only **NumPy**, **Pandas**, and **Matplotlib** — no `scikit-learn`.  

The repository contains:
- A practical application on a **real-world dataset**  
- Extra **visualizations with synthetic data** for better conceptual understanding  

---

## 📊 Dataset
- Dataset: **[OpenIntro Possum Data](https://www.kaggle.com/datasets/abrambeyer/openintro-possum)** from Kaggle  
- Task: Predict the **sex of a possum** based on multiple features  

---

## 🚀 Model Performance
- **Optimization:** Gradient Descent   
- **Final Accuracy:** `73.63%`  

📉 **Cost vs Iteration**  
Shows the convergence of the cost function as gradient descent progresses:  

![Cost vs Iteration](Images/output.png)

---

## 📂 Additional Visualizations
A second notebook (`Logistic_Regression_Visuals.ipynb`) provides visual intuition using **synthetic datasets**.  
This includes animated plots for step-by-step understanding:

- **Sigmoid Function & Decision Boundary**  
  - Demonstrates how the sigmoid curve aligns to the data  
  - Shows the decision boundary settling between two classes  

  ![Sigmoid & Boundary](Images/logistic.gif)

- **Cost vs W vs B Plot**

- ![cost](Images/cost.png)

- **Contour Plot of Cost Function**  
  - Visualizes the path taken by gradient descent while minimizing the cost  

  ![Contour Plot](Images/contour.gif)

---
## Installation & Usage 🚀

```bash
# Clone the repository
git clone https://github.com/aditya0x77/From-Scratch-Logistic-Regression-with-Visualizations.git
cd From-Scratch-Logistic-Regression-with-Visualizations

# Install dependencies
pip install numpy pandas matplotlib notebook

# Launch Jupyter Notebook
jupyter notebook

# Open the notebooks:
# Logistic_Regression_Notebook.ipynb  → Train logistic regression on the dataset, plot cost vs iteration, and visualize decision boundary
# Logistic_Regression_Visuals.ipynb   → Visual intuition with synthetic datasets (sigmoid curve, cost surface, animated plots)
```
