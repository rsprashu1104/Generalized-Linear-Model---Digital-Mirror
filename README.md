# Generalized-Linear-Model---Digital-Mirror  
A GLM-based analysis of social media and self-esteem perceptions

## 📱 Digital Mirror: Modeling the Impact of Social Media on Self-Esteem

This repository showcases my individual contribution to a collaborative academic project titled:

> **"Digital Mirror: A Glimpse into Smartphone Use and Mental Health"**

The project investigates how social media usage correlates with self-esteem, using data collected through a structured questionnaire and analyzed using **Generalized Linear Models (GLMs)** and **network analysis**.

---

## 🎯 Research Question

**Does social media negatively affect self-esteem?**

- **Dependent Variable (D1)**: Self-reported impact on self-esteem (Yes/No)
- **Independent Variables**: Age, social media engagement, satisfaction, platform preference, FOMO, social comparison, conformity pressure, and mental health perception

---

## 👤 My Contributions

- 🧾 Designed the **questionnaire**
- 🧠 Performed **GLM modeling** in Python using `statsmodels`
- 🌐 Built a **Directed Acyclic Graph (DAG)** to visualize causal relationships
- 📊 Created **conditional probability heatmaps** to interpret variable influence
- 📈 Interpreted model coefficients, p-values, log-likelihood, and pseudo R²
- 🧩 Highlighted **direct and mediated effects** between variables

---

## 📊 Model Summary & Key Insights

### 🔸 GLM Model Results

- **Pseudo R-squared**: 0.5564 — explains 55.6% of variation in self-esteem outcome
- **Significant Predictors**:
  - **Q1** (FOMO): OR↑ — p = 0.006
  - **Q2** (Mental Health Impact): OR↑ — p = 0.001
- **Marginal Predictor**:
  - **Q5** (Satisfaction): OR↓ — p = 0.054
- **Non-significant Predictors**: Age (Q6), engagement (Q8), comparison (Q4), conformity (Q3), and platform preference (Q7)

---

### 🔸 Network Diagram (DAG) Findings

- **Outcome Node**: D1 – perceived negative impact on self-esteem
- **Direct Predictors**: Q1, Q2, Q3, Q4, Q5, Q7, Q8
- **Mediated Path**: Age (Q6) indirectly affects D1 through Q2
- **Notable Interactions**:
  - Q1 (FOMO) ↔ Q4 (Comparison)
  - Q3 (Conformity) ↔ Q7 (Platform Preference)
- **Q5** acts as an **exogenous factor**, directly influencing D1
- Emphasizes the **complex, multidimensional** nature of social media’s psychological effects

---


## 📂 Repository Structure

