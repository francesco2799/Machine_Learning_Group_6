# Machine Learning Group 6 — Final Project

## Mortgage Lending Fairness Analysis

This project examines predictive modeling and algorithmic fairness in mortgage lending using the 2024 HMDA dataset published by the Consumer Financial Protection Bureau (CFPB).

## Research Questions

- **RQ1 — Predictive Performance & Key Lending Drivers:** How well can mortgage approval outcomes be predicted, and which factors drive these decisions?
- **RQ2 — Algorithmic Fairness Audit:** Do prediction outcomes differ systematically across racial, ethnic, or gender groups?
- **RQ3 — Applicant Profiling via Clustering & Dimensionality Reduction:** Can we identify natural groupings among applicants associated with different lending outcomes?

## Repository Structure

```
├── data/                     # Raw and cleaned datasets (see note below)
├── notebooks/
│   ├── RQ1_Predictive_Models.ipynb
│   ├── RQ2_Fairness_Audit.ipynb
│   ├── RQ3_Clustering_PCA.ipynb
│   └── Final_Analysis.ipynb
├── report/                   # Final report (Word/PDF)
├── presentation/             # Slide deck
└── README.md
```

## Data

The dataset is too large for GitHub. Download the 2024 HMDA Modified LAR data from:
https://ffiec.cfpb.gov/data-publication/modified-lar/2024

Place raw and cleaned files in the `data/` folder locally. See the data cleaning notebook from the proposal for preprocessing steps.

## Setup

```bash
git clone git@github.com:francesco2799/Machine_Learning_Group_6.git
cd Machine_Learning_Group_6
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Team Members

- Francesco Biedermann
- Phoebe Zhao
- Chun-Wei Hsu
