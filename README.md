# Alkemists-on-AI-productivity

What truly happens to margins when AI enters operational processes.

**Team Members:**  
- Amanda Ambrosone
- Giulio Presaghi
- Beatrice Rossi 

---

## Section 1 — Introduction  
This project investigates how **Artificial Intelligence influences operational productivity**, with a specific focus on quantifying changes in **execution time, cost efficiency, workforce leverage, and process-level performance** after integrating AI‑assisted workflows.

The goal is to design a **data-driven framework** capable of measuring productivity deltas attributable to AI. The project combines:

- feature engineering for process-level metrics  
- predictive modeling to quantify productivity change  
- counterfactual evaluation for “AI vs. no‑AI” scenarios  
- visualization of operational bottlenecks and efficiency gains  

This work is conducted in collaboration with **Alkemy**, as part of LUISS’ Machine Learning Projects course.

---

## Section 2 — Methods  
### 2.1 Problem Framing  
We aim to model the relationship between **AI assistance** and **productivity KPIs**, estimating how performance changes across different workflows (e.g., marketing content generation, analytics tasks, customer support workflows).

### 2.2 Features and Data  
Key feature groups include:

- **Operational metrics** (task duration, iterations, error rate)  
- **Workforce dynamics** (seniority, team size, task complexity)  
- **AI intervention markers** (type of model, assistance intensity)  
- **Output quality metrics**  

### 2.3 Modeling Approach  
We experiment with:

- Regression models (baseline)  
- Gradient boosting models  
- Tree-based interpretable models (e.g., SHAP-equipped models)  
- Time‑series deltas for before/after AI adoption  

A conceptual flowchart of our pipeline is shown below (placeholder):