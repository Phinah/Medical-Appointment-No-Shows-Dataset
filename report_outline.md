# Title: Predicting Outpatient Appointment No-Shows in Brazil: Classical ML vs Deep Learning
**Author:** Nelly Murekatete  
**Date:** 2025-10-16  

## Abstract
*(150–250 words.)*

## 1. Introduction
- Impact of no-shows on health operations; research questions; contributions.

## 2. Literature Review & Theory
- ≥10 sources (IEEE). Compare prior ML/DL, class imbalance, calibration, scheduling ops.

## 3. Data
- Kaggle *noshowappointments*; variables & preprocessing; leakage checks; splits.

## 4. Methodology
### 4.1 Classical ML (sklearn): LogReg, RF, XGBoost
### 4.2 Deep Learning (TF): Sequential MLP, Functional MLP
- Class weights, early stopping; optional `tf.data`.
### 4.3 Evaluation
- ROC-AUC, PR-AUC, F1, balanced accuracy, Brier, calibration.

## 5. Experiments & Results
- Reference `experiment_log.csv`; figures (ROC/PR, confusion, learning curves).

## 6. Error Analysis & Discussion
- Segment-wise errors (age, neighbourhood, SMS); bias–variance; limitations; ethics.

## 7. Conclusion & Future Work
- Final model; external validation (Colorado); richer features.

## References (IEEE)
[1] ...