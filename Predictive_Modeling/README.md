# Predictive Modeling (Later Stage)

Owner: Ramma (Data Analyst — Predictive Modeling), with Sambat (PM) coordinating.

## What goes here

- **`model_training.ipynb`** or **`model_training.py`** — script/notebook for
  the churn prediction model(s) (e.g. logistic regression, random forest, XGBoost).
- **`model_evaluation.md`** (or `.pdf`) — metrics used (accuracy, precision,
  recall, F1, ROC-AUC) and comparison across model candidates.
- **`trained_model.pkl`** (or equivalent) — the final trained model file.
- **`feature_importance.md`** — which features drive churn predictions and why,
  translated into plain-language business insight.

## Notes

This stage builds on the outputs of `Data_Preparation/` (train/test sets,
scaling) and can incorporate cluster labels from `Clustering_Analysis/` as an
additional feature if useful.
