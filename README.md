# Student Performance Prediction Using Machine Learning

A machine learning project for predicting students' final exam grades (G3) based on demographic, academic, and social features from the UCI Student Performance Dataset.

## 📋 Project Overview

- Dataset:  [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance)
- Goal: Predict final grade (G3, scale 0-20) using regression models
- Best Model: Gradient Boosting (R² = 0.85, RMSE = 1.89)

## 👥 Team

| Name | Role |
|------|------|
| Tulyugaliyev Alibek | Data preprocessing and cleaning |
| Rollanov Kaisar | EDA and visualization |
| Zaitov Ifrat | Model development and training |

Course: SIS-2207, IITU  
Instructor:  Abdul R.

## 🚀 Quick Start

# Clone repository
git clone https://github.com/veterinarr/student-performance-prediction.git
cd student-performance-prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook

## 📁 Project Structure

├── data/                    # Dataset files
│   ├── student-mat.csv
│   └── student-por.csv
├── notebooks/               # Jupyter notebooks
│   └── analysis.ipynb
├── images/                  # Plots and figures
├── requirements.txt         # Python dependencies
├── Project_Proposal.md      # Initial proposal
├── Project_Report.md        # Final report
└── README.md

## 📊 Results Summary

| Model | Train R² | Test R² | RMSE | MAE |
|-------|----------|---------|------|-----|
| Linear Regression | 0.82 | 0.78 | 2.15 | 1.65 |
| Random Forest | 0.96 | 0.82 | 1.95 | 1.52 |
| Gradient Boosting | 0.93 | 0.85 | 1.89 | 1.45 |

## 🔑 Key Findings

Top 5 predictive features:
1. G2 (second period grade) — 45.2%
2. G1 (first period grade) — 29.8%
3. avg_prev_grade — 8.7%
4. failures — 4.2%
5. absences — 3.1%

## 📦 Dependencies

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## 📚 References

1. Cortez, P., & Silva, A. (2008). *Using data mining to predict secondary school student performance*.  EUROSIS. 
2. [UCI ML Repository - Student Performance](https://archive.ics.uci.edu/ml/datasets/student+performance)
3. [Scikit-learn Documentation](https://scikit-learn.org/stable/)

## 📄 License

This project is for educational purposes only.
