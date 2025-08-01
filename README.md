# Disease Detection Using Random Forest

This project applies a **Random Forest Classifier** to predict disease diagnosis based on medical data. The model is trained using a dataset that was first cleaned and balanced using **SMOTE** (Synthetic Minority Over-sampling Technique).

---

# Files Included

- `report.docx`: The full project report including data handling, model logic, and outputs.
- `report.pdf`: PDF version of the report.
- `se22ucse003_predictions.csv`: Final predictions from the model on test data.

---

# Model Overview

- **Model**: Random Forest Classifier (50 trees, max depth 15)
- **Handling Imbalance**: SMOTE oversampling
- **Libraries used**: `pandas`, `numpy`, `sklearn`, `imbalanced-learn`

---

# Process Summary

1. Loaded and cleaned the dataset
2. Removed duplicates and checked for nulls
3. Separated features and target (`diagnosis`)
4. Used SMOTE to balance classes
5. Trained a Random Forest Classifier
6. Tested and evaluated accuracy
7. Applied model on test data and saved predictions

---

# Prediction Output

- Final CSV includes patient IDs and their predicted diagnosis.
- Unnecessary columns were dropped before saving.

---

# Notes

- Full implementation steps and analysis can be found in `report.docx`
- This repository does **not** include training/testing CSVs due to size/privacy
- Predictions are generated using clean and balanced training data
