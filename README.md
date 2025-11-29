# Skin Cancer Classification Project

STAT 101C Kaggle Competition

## Project Overview
Predicting skin cancer status (Benign vs Malignant) using patient-level features.

## Files
- `eda.ipynb`: Exploratory data analysis and preprocessing pipeline
- `SkinCancerTrain_processed.csv`: Preprocessed training data (ready for modeling)
- `SkinCancerTest_processed.csv`: Preprocessed test data (ready for modeling)

## Preprocessing Steps
1. Missing value imputation (median for numeric, mode for categorical)
2. Special handling for `family_history` (missing → "Unknown")
3. One-hot encoding for categorical variables

## Next Steps
- Model experimentation (XGBoost, LightGBM, etc.)
- Hyperparameter tuning
- Feature selection