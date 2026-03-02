# Crime Type Prediction in Bangladesh (ML)

This project predicts the **type of crime** in Bangladesh using **machine learning** (multi-class classification).

## Project Goal
Given incident-related features (time, location, context, etc.), predict the crime category among:
- murder
- bodyfound
- rape
- assault
- kidnap
- robbery

## Team Workflow (GitHub)
- We collaborate using GitHub.
- Each member works on **separate files** to avoid merge conflicts.
- One notebook is dedicated to **Logistic Regression**, and another to **Random Forest**.

## Repository Structure

CrimeDataBD/
├─ data/
│ ├─ raw/ # dataset goes here (NOT pushed to GitHub)
│ └─ processed/ # processed data outputs (local)
├─ notebooks/
│ ├─ logistic_regression.ipynb
│ └─ random_forest.ipynb
├─ src/ # future python scripts (optional)
├─ reports/
│ └─ figures/ # saved plots/images for report
├─ .gitignore
├─ requirements.txt
└─ README.md


## Dataset Setup (Local)
1. Put the dataset CSV file inside:
   - `data/raw/`
2. Example file name:
   - `data/raw/Bangladesh-Crime-Dataset.csv`

The dataset is **ignored by Git** (not uploaded) because `.gitignore` excludes `data/` and `*.csv`.

## Models (Planned)
- Logistic Regression (baseline) → `notebooks/logistic_regression.ipynb`
- Random Forest (non-linear) → `notebooks/random_forest.ipynb`

## Evaluation Metrics (Planned)
- Accuracy
- Macro F1-score
- Confusion Matrix

## Environment Setup
### Using VS Code + Python
1. Create virtual environment:
   - `python -m venv .venv`
2. Activate:
   - PowerShell: `.\.venv\Scripts\Activate.ps1`
3. Install dependencies:
   - `pip install -r requirements.txt`

## Notes
- Empty folders may not appear on GitHub until they contain at least one file.
- Keep outputs/plots in `reports/figures/` for the final report.

---
**Course:** CSE 445  
**Topic:** Predicting Crime Type in Bangladesh using Machine Learning
