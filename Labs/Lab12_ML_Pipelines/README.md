# Lab 12 – ML Pipelines

## Overview
This final lab brought everything together by introducing ML pipelines — a way to package the full ML workflow into a clean, reproducible, and production-ready process.

## What I Learned
- What an **ML pipeline** is and why it's important for reproducibility
- How to use scikit-learn's `Pipeline` class to chain preprocessing and modeling steps
- How pipelines prevent **data leakage** by keeping transformations inside cross-validation folds
- How to combine pipelines with **GridSearchCV** for clean hyperparameter tuning
- The concept of **model deployment** — how a trained pipeline can be saved and reused

## Challenges Faced
Understanding why pipelines prevent data leakage (and what data leakage even is) was the most conceptually difficult part. Seeing it demonstrated with an example made it much clearer.

## Key Takeaway
Pipelines are the bridge between experimentation and production. Everything I've learned in this course comes together here — clean data prep, good modeling, proper evaluation — all packaged in a way that's reliable and repeatable.

## Tools Used
- Python
- Google Colab
- scikit-learn (Pipeline, ColumnTransformer)

---
*ITAI 1371 – Oludamilola Alonge*
