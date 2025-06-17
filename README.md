# AlphaCare Insurance Solutions: Car Insurance Risk & Premium Optimization

This repository contains the full analysis, modeling, and reporting pipeline for risk-based car insurance pricing, conducted by the marketing analytics team at **AlphaCare Insurance Solutions (ACIS)**.

---

## 📁 Project Structure
```
acis-risk-analysis/
├── 01_eda.ipynb                   # Exploratory Data Analysis
├── 02_dvc_setup.ipynb             # Data Version Control setup
├── 03_ab_testing.ipynb            # A/B Hypothesis Testing
├── 04_modeling.ipynb              # Regression, classification, SHAP
├── MachineLearningRating_v3.txt   # Raw dataset (tracked by DVC)
├── MachineLearningRating_v3.txt.dvc # DVC metadata file
├── .dvc/                          # DVC internal tracking
├── .git/                          # Git repository
├── .gitignore                     # Files ignored in Git
├── README.md                      # Project overview and instructions
└── requirements.txt               # Python dependencies
```

---

## 🚀 Getting Started

### 🔧 Install Required Packages
```bash
pip install -r requirements.txt
```

### 📦 Set Up DVC (Optional)
If you want to pull the dataset tracked by DVC:
```bash
dvc pull
```

### 🧪 Run the Notebooks
1. Start Jupyter:
```bash
jupyter notebook
```
2. Open and run:
   - `01_eda.ipynb` → Data summary & insights
   - `02_dvc_setup.ipynb` → DVC steps (documented)
   - `03_ab_testing.ipynb` → Statistical hypothesis testing
   - `04_modeling.ipynb` → Machine learning models + SHAP

---

## 📊 Project Goals
- Identify low-risk and high-risk customer segments
- Use statistical testing to justify segmentation
- Train predictive models for claim amounts and probabilities
- Improve pricing strategies through explainable ML

---

## 📄 Report
See `final_report.md` (or exported PDF) for:
- Executive summary
- Methodology
- Key business insights
- Premium recommendations

---

## 🧠 Key Tools
- **Python** (pandas, seaborn, scikit-learn, shap, xgboost)
- **Jupyter Notebooks**
- **Git** for code versioning
- **DVC** for dataset tracking

---

## 🙌 Credits
Marketing Analytics Team – AlphaCare Insurance Solutions  
Data Period: Feb 2014 to Aug 2015

---

## 📬 License
Internal ACIS analytics project. Not for external redistribution.
