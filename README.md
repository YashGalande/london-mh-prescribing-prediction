# London Mental Health Prescribing Prediction

This repository supports a dissertation project on predicting mental health prescribing patterns in London using environmental features and deprivation data.

## Project Aim

The aim of this research is to test whether environmental factors can predict mental health prescribing outcomes, whether adding deprivation data improves prediction, and which features matter most.

## Research Questions

1. Can mental health prescribing outcomes be predicted using environmental features only?
2. Does adding Index of Multiple Deprivation (IMD) data improve the prediction?
3. Which environmental and deprivation features are most important in the model?

## Repository Structure

```text
london-mh-prescribing-prediction/
├── data/
│   ├── raw/          # Original source data, kept unchanged
│   └── processed/    # Cleaned and joined datasets used for modelling
├── notebooks/        # Exploration, cleaning, modelling, and analysis notebooks
├── outputs/          # Figures, model results, tables, and exported files
├── writing/          # Dissertation drafts, notes, references, and planning
├── dashboard/        # Dashboard code or exported dashboard files
└── README.md
```

## Data Notes

Raw data should be stored exactly as downloaded. Cleaned datasets should be saved in `data/processed/` with clear names and dates where useful.

Large files, private data, and sensitive records should not be committed to GitHub. If needed, store them securely outside the repository and document where they came from.

## Ethics Status

This project is expected to use secondary, aggregated, and publicly available data. No direct personal data collection is planned. The project should still follow university ethics guidance, data protection rules, and careful reporting practices so that areas or communities are not unfairly blamed or labelled.

## Current Status

Initial repository structure created.
