# Wine Quality Analysis
### 🇫🇷 Sommaire du Projet (Version Française)
Cette étude examine l'influence des facteurs socio-économiques (PIB et population) sur la performance olympique des nations. À l'aide de modèles de régression multivariée et de tests ANOVA réalisés sous R, j'ai identifié que la richesse nationale demeure le principal prédicteur du succès athlétique, tout en développant un indice d'efficacité pour mettre en lumière les pays surperformants.

**By: Yuanyuan Wei** | *Maths & Stats Graduate* | 📍 Montreal, QC (PR Holder)

## 📌 Project Overview
This project investigates the relationship between a nation's socio-economic factors (GDP and Population) and its performance in the Olympic Games. Using data from 1896 to 2016, I conducted a multivariate statistical analysis to determine the primary drivers of athletic success.

### 🔍 Key Research Questions
1. Is there a statistically significant correlation between a country's GDP and its medal count?
2. Does population size provide a significant advantage after controlling for wealth?
3. Which nations are most "efficient" at producing medals relative to their economic resources?

## 🛠️ Technical Toolkit
- **Language:** R
- **Libraries:** `dplyr` (data cleaning), `ggplot2` (visualization), `car` (VIF & Multicollinearity), `tidyr` (data reshaping).
- **Statistical Methods:** Multivariate Linear Regression, ANOVA, Hypothesis Testing (P-values), and Correlation Matrices.

## 📊 Major Findings
- **Economic Correlation:** Found a strong positive correlation (r = 0.77) between GDP and Total Medals.
- **Efficiency Index:** Developed a custom KPI to identify "over-performing" nations.
- **Log-Scale Modeling:** Used log-transformation to normalize highly skewed GDP data for more accurate regression results.
  
## 📂 Project Assets
To ensure transparency and reproducibility, all source files are provided below:

*   **R Analysis Script:** [analysis_script.R](2_MedalsStatsScript-220251110.Rmd) — *Contains full data cleaning, regression modeling, and ANOVA logic.*
*   **Primary Dataset:** [MedalsStatsData.csv](1_MedalsStatsData-220251110%20copy.csv) — *The processed dataset combining Olympic history and economic indicators.*
*   **Full Report:** [📄 View Full Statistical Report (PDF)](https://github.com/c0672004-cmd/olympic-stats-analysis/raw/main/2_MedalsStatsReport%20-%20220251110.pdf)

---

## 🚀 How to Run the Analysis
1. Clone the repo: `git clone https://github.com`
