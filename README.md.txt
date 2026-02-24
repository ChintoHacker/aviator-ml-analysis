# Aviator Crash Game — ML Signal Analysis

## 🎯 Project Overview
Investigated whether ML can predict outcomes in a 
provably fair RNG-based crash game using 33,000+ rounds of data.

## 🔑 Key Finding
After detecting and fixing data leakage (AUC: 93% → 50%), 
all models performed at random baseline — confirming 
the game is mathematically unpredictable.

## 📊 What I Did
- Exploratory Data Analysis & outlier handling
- Statistical tests (Autocorrelation, Chi-Square, Cramér's V)
- Feature engineering (lag, rolling stats, streak)
- Detected & fixed data leakage in model pipeline
- Validated with shuffled baseline test

## 🛠️ Tech Stack
Python, Pandas, Scikit-learn, SciPy, Matplotlib, Seaborn

## ▶️ How to Run
pip install -r requirements.txt
# Open aviator_ml_analysis.ipynb in Jupyter or Google Colab