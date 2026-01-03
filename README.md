# Statistical Learning — Practical Exam (R)

This repository contains my solution to the **practical part** of the *Statistical Learning* exam (RMarkdown report).  
The exam also included an oral discussion.

## Contents
- `Solution.Rmd`: full analysis and answers (code + comments).
- `main.pdf`: exam text / assignment (included only if sharing is allowed).
- `output/` (optional): exported figures or intermediate results.

## Methods used (high level)
The solution covers typical Statistical Learning topics, including:
- Unsupervised learning (k-means clustering, selection of `k` via loss curve and inspection)
- Classification with SVM (confusion matrix, ROC/AUC, interpretation of sensitivity/specificity)
- GAM modelling (smooth terms, interpretation, Holm correction for multiple tests)
- Gradient boosting regression (tuning `interaction.depth`, MSE on internal validation split, variable importance)

### How to run
1. Open `Solution.Rmd` in RStudio.
2. Make sure the working directory is set to the repository root.
3. Knit the document (HTML/PDF depending on your setup).

> Note: If the report expects a dataset file, place it in the repo root or update the path in the RMarkdown accordingly.

## Notes
- The analysis follows the exam instructions (fixed random seed where required, consistent train/test split for supervised methods).
- Comments are aligned with the code and reported outputs (figures, tables, metrics).
