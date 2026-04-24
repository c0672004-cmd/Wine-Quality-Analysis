# 🍷 Wine Quality Prediction: A Chemical & Statistical Analysis

## Sommaire du Projet (Version Française)
Cette étude explore l'efficacité des modèles de régression linéaire et polynomiale pour prédire la qualité du vin rouge en fonction de ses propriétés physico-chimiques. En utilisant l'optimisation par descente de gradient, j'ai comparé différents degrés de complexité de modèle pour identifier les facteurs clés influençant la qualité. Les résultats démontrent que la relation entre les composants chimiques et la perception de la qualité est intrinsèquement non linéaire.

**By: Yuanyuan (Coco) Wei** | *Maths & Stats Graduate* | 📍 Montreal, QC (PR Holder)

---

## 📌 Project Overview
This project investigates the relationship between a wine's chemical properties and its quality rating. Using the UCI Red Wine Quality dataset, I conducted a deep dive into feature engineering and model optimization to determine which chemical factors most accurately define a "premium" wine.

## 🔍 Key Research Questions
1. **Linearity:** Is wine quality a linear function of its chemical components, or are the relationships more complex?
2. **Key Drivers:** Which specific chemical features (e.g., Alcohol, Acidity) are the strongest predictors of quality?
3. **Model Accuracy:** Can higher-degree polynomial models significantly reduce prediction error compared to standard linear regression?

## 🛠 Technical Toolkit
- **Language:** Python, R
- **Libraries:** `numpy`, `pandas`, `matplotlib`, `seaborn`
- **Statistical Methods:** Multivariate Linear Regression (from scratch), Polynomial Regression (Degrees 2 & 3), Correlation Matrices, and Gradient Descent Optimization.

## 📊 Major Findings
- **Non-Linear Dynamics:** The standard Linear Regression model was insufficient ($R^2 = 0.050$), while a **Degree 2 Polynomial** model significantly improved predictive power ($R^2 = 0.428$).
- **Chemical Correlation:** Alcohol content ($r = 0.48$) and Volatile Acidity ($r = -0.39$) were identified as the primary drivers of quality ratings.
- **Model Efficiency:** Moving to a Degree 3 polynomial showed diminishing returns ($R^2 = 0.331$), suggesting an optimal balance of complexity at Degree 2.

## 📂 Project Assets
To ensure transparency and reproducibility, all source files are provided below:
- **Analysis Script:** `analysis_script.py` — *Contains full data cleaning, regression modeling, and gradient descent logic.*
- **Primary Dataset:** `winequality-red.csv` — *The processed dataset featuring 1,599 samples.*
- **Full Report:** 📄 [View Full Statistical Report (PDF)](#)
- **Visualizations:** `EDA_plots/` — *Includes distribution histograms, heatmaps, and residual plots.*

## 🚀 How to Run the Analysis
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/yourusername/wine-quality-analysis](https://github.com/yourusername/wine-quality-analysis)
