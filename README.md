# mohd-saad-choudhary.github.io

Personal portfolio site for **Mohd Saad Choudhary** — AI researcher and aspiring AI Product Manager, B.Tech IT '27, NSUT Delhi.

## What's here

A single-page portfolio built in vanilla HTML/CSS/JS. No frameworks, no build step — just drop `index.html` and it works.

**Sections:**
- Hero with key research stats
- About & PM strengths
- Featured research: EMSWOA-KS (see below)
- Skills & background
- PM philosophy
- Contact

## Featured Research — EMSWOA-KS

**A Novel Hybrid Metaheuristic Framework for Credit Risk Feature Selection in MSMEs under Industry 4.0**

*Equal first authors: Mohd Saad Choudhary & Naman Kumawat · Advisor: Dr. Mohit Sajwan · NSUT Delhi · In Preparation*

A three-phase ML pipeline for MSME credit risk assessment:

1. **KS Pre-Screening** — Kolmogorov–Smirnov filter reduces 88 raw indicators to 29
2. **EMSWOA-KS Selection** — Dynamic multi-swarm Whale Optimisation Algorithm with Opposition-Based Learning initialisation and Elite Tuning, using KS-statistic as the fitness function. Reduces 29 → 4 features
3. **Risk-Weighted Ensemble** — Bayesian hyperparameter optimisation (Optuna) across six classifiers with asymmetric cost weighting (λFN = 3×)

**Results:**
- 95.5% feature reduction (88 → 4 indicators)
- Competitive AUC maintained across RF, GBDT, SVM, LR, KNN, XGBoost
- Statistically significant superiority over BWOA and BPSO baselines (Wilcoxon rank-sum, p < 0.001, effect r > 0.59) over 30 independent runs

## Running locally

No dependencies.

```bash
git clone https://github.com/mohdsaad/mohdsaad.github.io
open index.html
```

## Live site

[view it here]([https://saad01042005.github.io/Credit-Risk-AI-Framework-MSME-Industry-4.0-/]) — hosted via GitHub Pages

## Contact

- Email: mohd.saad.ug23@nsut.ac.in
- Co-author: [Naman Kumawat](https://github.com/namankumawat)
