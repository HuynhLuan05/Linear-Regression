# Student Performance Prediction – Linear Regression Models

This project analyzes student performance data and builds multiple regression models to predict the **Performance Index** using provided features. The work includes **exploratory data analysis (EDA)**, **statistical insights**, **visualizations**, and **multiple regression models** with cross-validation.

---

## 1) Project Tasks & Requirements

### A) Exploratory Data Analysis (EDA)
- Perform descriptive statistics on all features.
- Visualize data using **bar, box, heatmap, scatter, line** plots.
- Derive initial insights about relationships between features and target.

### B) Regression Models
1. **Model 2a – Full Model**
   - Use **all 5 features** at once.
   - Train once on the training set.
   - Derive the **regression formula** with 5 coefficients.
   - Evaluate on test set with **MAE**.

2. **Model 2b – Single Feature Models**
   - Build **5 separate models**, each using only one feature.
   - Use **k-Fold Cross Validation (k ≥ 5)** on the training set.
   - Report average MAE for each feature; select the **best single feature**.
   - Show regression formula and test MAE for the best single-feature model.

3. **Model 2c – Student-Designed Models**
   - Propose **m new models (m ≥ 3)** using:
     - Feature transformations (e.g., squared terms, interaction terms).
     - Combinations of features (e.g., sum of two features).
   - Use **k-Fold Cross Validation (k ≥ 5)** for all models.
   - Report MAE for each; pick the **best-designed model**.
   - Derive regression formula and test MAE for the best model.

---

## 2) Evaluation Metric
- **Mean Absolute Error (MAE)** for:
  - Cross-validation (average MAE)
  - Final test set evaluation

---

## 3) Deliverables
- **Jupyter Notebook** (`Linear Regression.ipynb`)  
  Includes EDA, visualizations, all models, evaluation, and analysis.
- **Report** (`Report.pdf`)  
  Covers methods, formulas, results tables, discussions, references.

---

## 4) Tools & Libraries
- **pandas, numpy**: Data handling & calculations
- **matplotlib, seaborn**: Data visualization
- **scikit-learn**: Regression models, k-Fold Cross Validation, metrics

---

