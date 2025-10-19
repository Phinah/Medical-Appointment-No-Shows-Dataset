# Clinic Appointment No-Show Prediction (Brazil)

**Goal:** Predict no-shows using classical ML vs Deep Learning (Sequential & Functional TF APIs).

**Dataset:** Kaggle — *Medical Appointment No Shows* (`joniarroba/noshowappointments`).

## Quick Start

### Kaggle API (auto-download)
1. Create Kaggle API token (Account → Create New API Token) → saves **kaggle.json**.
2. In Colab: upload `kaggle.json` when prompted. Locally: place it at `~/.kaggle/kaggle.json` (permission 600).

Run **notebook.ipynb** top-to-bottom:
- Installs/sets up Kaggle
- Downloads dataset to `./data/`
- Cleans & engineers features (lead time, DOW, etc.)
- Trains ML baselines (LogReg, RF, XGBoost) and DL MLPs (Sequential & Functional)
- Produces ROC, PR, confusion matrices, learning curves
- Appends results to **experiment_log.csv**

## Experiments (≥7)
1) LogReg baseline (±class_weight)  
2) RF grid (n_estimators, max_depth)  
3) XGBoost grid (eta, depth, subsample, colsample)  
4) MLP-Seq width/depth/dropout sweep  
5) MLP-Func with skip/concat vs plain  
6) Imbalance: class_weight vs SMOTE vs focal loss (DL)  
7) Calibration & threshold tuning by business costs

## Rubric Alignment
- Problem & mission alignment ✔
- 10+ scholarly sources (IEEE) ✔
- ML vs DL (Sequential & Functional) ✔
- ≥7 experiments with insights ✔
- Learning curves, confusion matrices, ROC/PR ✔
- Error analysis & bias–variance ✔
- Reproducibility ✔