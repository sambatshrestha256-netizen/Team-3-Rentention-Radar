# Clustering Analysis (Stage 2.2)

Owner: Manisha (Data Analyst — Clustering), with Sambat (PM) coordinating.

## What goes here

- **`elbow_method_analysis.md`** (or `.pdf`) — the elbow plot and reasoning for
  the chosen optimal number of clusters (k).
- **`kmeans_model.pkl`** (or equivalent) — the trained K-Means model file.
- **`clustering.ipynb`** or **`clustering.py`** — the training script/notebook.
- **`cluster_visualisations/`** — plots of the resulting clusters (e.g. 2D/3D
  scatter, PCA-reduced views), each labelled with what that cluster represents
  (e.g. "high-value low-churn-risk", "price-sensitive at-risk").
- **`insights.md`** — plain-language interpretation of each cluster and the
  actionable insight it suggests for churn reduction.

## Notes

Clustering should run on the scaled data produced in `Data_Preparation/`, not
the raw preprocessed dataset — keep that dependency clear in the notebook.
