# Diabetes Prediction using SVM

🔍 Built an SVM-based classifier to predict diabetes from clinical features (PIMA dataset).

📊 Key Steps: Data standardization, stratified train-test split, linear SVM training (~77% test accuracy).

🛠 Tech Stack: Python, Scikit-learn, Pandas, NumPy.

📌 Insights: Analyzed feature correlations and handled class imbalance.

🚀 Next Steps: Hyperparameter tuning, deployment via Streamlit

## Overview
A machine learning model to predict diabetes based on clinical features from the PIMA dataset. Achieved **77.3% accuracy** with SVM.

## Steps
- Data standardization (`StandardScaler`)
- Stratified train-test split
- SVM model training/evaluation

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook DiabetesPrediction(SVM).ipynb
