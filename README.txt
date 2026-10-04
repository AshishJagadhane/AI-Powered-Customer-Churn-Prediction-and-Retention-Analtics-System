# 📊 AI-Powered Customer Churn Prediction & Retention Analytics System

An end-to-end data intelligence solution that combines **Python-driven machine learning**, **automated data preprocessing**, and **Power BI dashboard analytics** to accurately predict customer churn, uncover underlying risk behavior, and deliver strategic retention frameworks.

---

## 🎯 Project Overview

Losing customers directly impacts business revenue and scales acquisition costs. This system replaces reactive approaches with a proactive, three-stage data pipeline that identifies high-risk customers before they terminate services:

1. **Synthetic Data Modeling:** Generating clean, multi-feature simulation profiles reflecting customer interaction records.
2. **Predictive Intelligence:** Preprocessing, cleaning, and encoding datasets to train machine learning models optimized for risk detection.
3. **Executive Presentation:** Exporting risk metrics into interactive analytical reporting layouts for customer success teams.

---

## 📂 Repository File Architecture

Based on the core structure of this repository, the files operate across the following sequential workflow:

```text
├── 01_data_generation.ipynb              # Notebook establishing raw customer baseline profiles
├── 02_data_cleaning.ipynb                # Data parsing, outlier handling, and missing values processing
├── 03_EDA.ipynb                          # Exploratory Data Analysis & Machine Learning modeling
├── customer_churn_data.csv               # Initial generated raw customer dataset
├── customer_churn_cleaned.csv            # Formatted dataset post data-cleaning execution
├── customer_churn_feature_engineered.csv  # Final training dataset with structured analytical variants
├── AI Customer Churn Dashboard.pdf       # Exported execution report of the Power BI analytics view
└── README.md                             # Project documentation
```

---

## 🛠️ Tech Stack & Core Libraries

- **Data Engineering & Simulation:** Python 3.x, NumPy, Pandas
- **Exploratory Data Analysis & Visualization:** Matplotlib, Seaborn
- **Machine Learning Infrastructure:** Scikit-Learn (Classification algorithms, validation pipelines)
- **Business Intelligence & Reporting:** Power BI (represented via executive PDF layout sheets)

---

## ⚙️ Analytical Processing Workflow

### 🚀 Step 1: Automated Data Generation
Run `01_data_generation.ipynb` to simulate realistic customer metrics (`customer_churn_data.csv`). Captured behavioral fields include:
- **Demographics:** Age, Gender, Geographic boundaries.
- **Account Profiles:** Subscription lengths, tenure tracking, contract structures.
- **Usage Metrics:** Bill variations, data/usage counts, and service tier configurations.

### 🧹 Step 2: Data Cleaning & Preprocessing
Run `02_data_cleaning.ipynb` to transform raw logs into analytical records (`customer_churn_cleaned.csv`):
- Imputation strategies for empty data cells.
- Standardisation of value categories.
- Outlier tracking to reduce bias on model weights.

### 🧠 Step 3: Exploratory Data Analysis & ML Training
Run `03_EDA.ipynb` to dive into visual churn markers and execute predictive modeling:
- Correlation maps assessing usage metrics against churn categories.
- Vector feature extraction and engineering (`customer_churn_feature_engineered.csv`).
- Classifier training loops assessing metrics like Accuracy, Precision, and Recall scores.

### 📈 Step 4: Executive Business Intelligence
Review `AI Customer Churn Dashboard.pdf` to inspect the visual business management layout. The analytics view focuses on:
- Highlighted KPI cards showing total churn rate and high-risk accounts.
- Cohort tracking charts evaluating subscription length vs tenure loss.
- High-risk target groups cross-referenced against high monthly bills for customer success outreach.

---

## 🚀 Getting Started

### 1. Clone this Repository
```bash
git clone https://github.com
cd AI-Powered-Customer-Churn-Prediction-and-Retention-Analtics-System
```

### 2. Prepare Environment Dependencies
Ensure python and standard data science libraries are installed locally:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Execution Pipeline
Open the root directory in your notebook server or local IDE:
```bash
jupyter notebook
```
Run the notebooks sequentially: `01_data_generation.ipynb` ➔ `02_data_cleaning.ipynb` ➔ `03_EDA.ipynb`.

---

## 📄 License

This repository is distributed under the MIT License - check the repository guidelines for usage terms.
