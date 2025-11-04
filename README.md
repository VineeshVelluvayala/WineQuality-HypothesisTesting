# 🍷 Wine Quality Hypothesis Testing (Applied Statistics)

**Objective:**  
Analyze whether alcohol content differs across wine quality ratings using **Parametric (ANOVA)** or **Non-Parametric (Kruskal-Wallis)** tests depending on data distribution.

---

## CRISP-DM Framework

### 1️⃣ Business Understanding
Goal: Assess if alcohol percentage varies significantly among wine quality categories (5, 6, 7).  
Stakeholder: Wine certification board.
### 2️⃣ Data Understanding
Dataset: `winequality-red.csv`  
Key Features: alcohol, pH, acidity, sulphates, quality (0–10).
### 3️⃣ Data Preparation
- Removed missing values  
- Checked variable distributions (Shapiro-Wilk, histograms)
  <img width="846" height="547" alt="distribution" src="https://github.com/user-attachments/assets/7977034f-aefa-4cc1-9ef4-2f7260516f36" />


---<img width="1278" height="423" alt="Quality wine" src="https://github.com/user-attachments/assets/51bf13e9-331d-4295-b563-9081790f6cc2" />

### 4️⃣ Modeling
- If normal → One-Way ANOVA  
- If not → Kruskal-Wallis Test  

---
### 5️⃣ Evaluation
- Test statistic & p-value  
- Visualizations: boxplot and histogram  

---<img width="723" height="242" alt="p value" src="https://github.com/user-attachments/assets/2df63541-ef2b-470a-b10f-dffaa879b951" />

### 6️⃣ Insights
- If p < 0.05 → alcohol levels differ significantly among wine grades.  
- If p ≥ 0.05 → no significant difference detected.
