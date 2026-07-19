# Contributing — Retention Radar

Quick guide for the team on how to work in this repo.

## Getting started

```
git clone <repo-url>
cd retention-radar
```

## Branching

- Don't push directly to `main`. Create a branch per task:
  - `data-prep/<short-description>` — e.g. `data-prep/encode-categoricals`
  - `clustering/<short-description>` — e.g. `clustering/elbow-method`
- Open a Pull Request into `main` when ready. Tag Sambat as reviewer.

## Where things go

| You're working on... | Put files in |
|---|---|
| Missing values, encoding, train/test split, scaling | `Data_Preparation/` |
| Elbow method, K-Means training, cluster plots | `Clustering_Analysis/` |

Each folder has its own README listing exactly what's expected — check it before
adding files so naming stays consistent.

## Commit messages

Keep them short and specific: `Add scaling documentation`, not `updates`.

## Notebooks

Clear cell outputs before committing where possible, to keep diffs readable.
If a notebook is meant to be run top-to-bottom, note that at the top of the file.

## Questions / blockers

Raise it on the Jira board (KAN) or the team channel rather than sitting on it —
Stage 2 has a shared deadline.
