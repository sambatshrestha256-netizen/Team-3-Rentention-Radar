# Data Preparation (Stage 2.1)

Owner: Diwakar Bhatta (Data Engineer), with Sambat (PM) coordinating.

## What goes here

- **`preprocessed_dataset.csv`** — the cleaned dataset: missing values handled,
  categorical variables encoded (one-hot or label encoding as appropriate).
- **`train/`** and **`test/`** — split dataset folders (or `train.csv` / `test.csv`).
  Document the split ratio and row counts in `split_documentation.md`.
- **`split_documentation.md`** — size and composition of the train/test sets
  (row counts, class/segment balance, random seed used).
- **`scaling_techniques.md`** (or `.pdf`/`.docx`) — which scaling method was used
  (e.g. StandardScaler, MinMaxScaler) and why, with the relevant code snippet.
- **`preprocessing.ipynb`** or **`preprocessing.py`** — the script/notebook that
  produced the outputs above, so the process is reproducible.

## Naming convention

Keep raw source data out of this folder if it contains client-sensitive info —
only commit the preprocessed/derived files unless the client has approved sharing
raw data in the repo.
