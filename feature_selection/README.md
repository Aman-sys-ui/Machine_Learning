# Feature Selection in Machine Learning  

Feature selection is a **critical step** in building robust and efficient Machine Learning models.  
The goal is simple: **keep only the features that matter**, remove noise, and make models generalize better.  

In this repository, I document my learning journey on **Feature Selection**, covering **theory, intuition, code implementations, and experiments** — all in a clean, hands-on way.  
This repo is designed to be a **one-stop reference** for anyone who wants to master feature selection from scratch.

---

## Repository Structure

| Folder / Notebook | Description |
|-------------------|-------------|
| `filter_methods/` | Covers **Filter-based feature selection** (Variance Threshold, Correlation, Chi-Square, ANOVA, Mutual Information). |
| `wrapper_methods/` | Covers **Wrapper methods** (Forward Selection, Backward Elimination, RFE). |
| `embedded_methods/` | Covers **Embedded methods** (Lasso, Ridge, ElasticNet, Tree-based feature importance). |

Each notebook contains:
- **Theory + Why** (short, intuitive explanation)
- **Mathematics** (key formulas in LaTeX for clarity)
- **Code Implementation** (sklearn, pandas, matplotlib)
- **Visualizations** (wherever helpful)
- **Baseline Model vs Selected Features Performance Comparison**
- **Takeaways** (my own reflections after running experiments)

---

## Key Topics Covered

- **Filter Methods:** Variance Threshold, Correlation, Chi², ANOVA, Mutual Information  
- **Wrapper Methods:** Forward Selection, Backward Elimination, RFE  
- **Embedded Methods:** Lasso (L1), Ridge (L2), Elastic Net, Tree-Based Feature Importances  

I not only implemented these techniques but also compared model performance **before and after feature selection**, so you can see the real impact.

---

## 🚀 How to Use

Clone this repository:

```bash
git clone https://github.com/Aman-sys-ui/Machine_Learning.git
cd Machine_Learning/feature_selection
