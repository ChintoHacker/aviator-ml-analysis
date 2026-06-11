# 🎯 Aviator Crash Game — ML Signal Analysis

**Author:** Abdul Hanan  
**Type:** Data Science / Statistical Research  
**Dataset:** 33,000+ real Aviator crash multiplier rounds  

---

## 📌 Project Goal

Investigate whether Machine Learning can predict outcomes in a 
provably fair RNG-based crash game (Aviator). Followed a rigorous 
ML pipeline: EDA → Feature Engineering → Leakage Detection → 
Model Evaluation → Statistical Validation.

## 🔑 Key Finding

> **After detecting and fixing data leakage (AUC: 93% → 50%), 
> all models performed at random baseline — confirming the game 
> is mathematically unpredictable.**

---

## 📊 What I Did

- Exploratory Data Analysis on 33,000+ rounds (distributions, zones, outliers)
- Statistical tests: Autocorrelation, Chi-Square, Cramér's V effect size
- Feature engineering: lag features, rolling stats, streak detection
- **Detected & fixed critical data leakage** in model pipeline
- Compared 3 ML models: Logistic Regression, Random Forest, Gradient Boosting
- Validated with shuffled baseline test (ground truth null model)

---

## 🛠️ Tech Stack

Python · Pandas · Scikit-learn · SciPy · Statsmodels · Matplotlib · Seaborn

---

## 📈 Results

| Model | AUC-ROC |
|-------|---------|
| Logistic Regression | ~0.50 |
| Random Forest | ~0.50 |
| Gradient Boosting | ~0.50 |
| Shuffled Baseline | ~0.50 |

All models = random baseline → **Zero predictive signal exists.**

---

## 💡 Key Skills Demonstrated

| Skill | Applied |
|-------|---------|
| Exploratory Data Analysis | ✅ |
| Statistical Testing | ✅ Chi-Square, Autocorrelation, Cramér's V |
| Outlier Detection | ✅ IQR method |
| Feature Engineering | ✅ Lag, rolling stats, streak |
| **Data Leakage Detection** | ✅ 93% → 50% AUC collapse |
| ML Model Comparison | ✅ Chronological split |
| Shuffled Baseline Test | ✅ Null hypothesis validation |
| Scientific Integrity | ✅ Honest null result reported |

---

## ▶️ How to Run

pip install -r requirements.txt
# Open aviator_ml_analysis.ipynb in Jupyter or Google Colab

---

## ⚠️ Conclusion

Any software claiming to "predict" Aviator outcomes is statistically 
a scam. This project proves it with data.
