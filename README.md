# Dementia Detection — Machine Learning Project

##  Overview
End-to-end ML pipeline predicting early-stage Dementia in 
patients using clinical and lifestyle data. Compares 
SelectKBest vs RFE feature selection with Logistic 
Regression and Decision Tree classifiers.

## Dataset
- 2,149 patients
- 35 features (demographic, lifestyle, clinical, cognitive)
- Target: Diagnosis (0 = No Dementia, 1 = Dementia)

## Methodology
1. Data Preprocessing
2. Exploratory Data Analysis
3. Feature Selection (SelectKBest & RFE)
4. Classification Models (Logistic Regression & Decision Tree)
5. Model Evaluation & Comparison

## Results

| Model | Features | Accuracy | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | SelectKBest | 82.09% | 75.00% | 0.7475 |
| Logistic Regression | RFE | 81.16% | 74.34% | 0.7362 |
| **Decision Tree** | **SelectKBest** | **93.49%** | **90.79%** | **0.9079** |
| **Decision Tree** | **RFE** | **93.49%** | **90.79%** | **0.9079** |

## Best Model
Decision Tree achieved 93.49% accuracy and 0.9079 F1-Score,
correctly identifying 90.79% of dementia patients.

## Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Repository Structure
```
Dementia-Detection-ML/
├── README.md
├── Dementia_Detection_ML.ipynb
├── data/
│   └── dementia.csv
└── outputs/
    ├── target_distribution.png
    ├── selectkbest_scores.png
    ├── confusion_matrix_lr.png
    └── confusion_matrix_dt.png
```

## Author
Buhlebemvelo Nandi Malinga | Assignment | Eduvos | 2026
