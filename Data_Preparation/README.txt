Training and Testing Sets — Size and Composition
==================================================

Source: Dataset_ATS_Stage2_Preprocessed.csv (6,741 rows, post Stage 1 cleaning + Stage 2 feature engineering)
Split method: 80/20, stratified on Churn, random_state=42 (scikit-learn train_test_split)

| Set          | Rows  | % of total | Churn rate |
|--------------|-------|------------|------------|
| Full dataset | 6,741 | 100%       | 26.57%     |
| Training set | 5,392 | 80.0%      | 26.58%     |
| Testing set  | 1,349 | 20.0%      | 26.54%     |

Files:
- train_set.csv / test_set.csv           -> scaled (StandardScaler), ready for clustering/modelling
- train_set_unscaled.csv / test_set_unscaled.csv -> unscaled, retained for reference/auditing

Stratifying on Churn keeps the ~26.6% churn rate consistent across both sets, which matters
because churn is an imbalanced class in this dataset.
