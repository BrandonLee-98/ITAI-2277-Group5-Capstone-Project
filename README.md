# Real Estate Cost-of-Living Prediction Model

An advanced machine learning pipeline and predictive analytics platform designed to forecast comprehensive localized cost-of-living metrics by ZIP code. Moving beyond traditional median home values, this project integrates property valuation with localized secondary expenses—such as insurance premiums, utility usage rates, and regional grocery price indexes—to provide a holistic financial outlook for prospective homebuyers and real estate investors.

---

## Repository Description

> A machine learning-driven real estate cost-of-living prediction platform that dynamically estimates localized expenses—including insurance requirements, utility rates, and grocery costs—segmented by ZIP code.

---

## Class & Project Information

* **Institution:** Houston City College
* **Program:** Associate Degree in Artificial Intelligence and Robotics
* **Course:** ITAI-2277-Artificial Intel Resource
* **Project Type:** 16-Week Academic Capstone Project

---

## Project Team

* **Team Member:** Brandon Matias
* **Team Member:** Jonah Joseph
* **Team Member:** Taki Eddine Boubekri
* **Team Member:** Khadijah Patience

---

## Key Features

* **Granular ZIP Code Analytics:** Delivers localized predictive breakdowns rather than broad city or county averages.
* **Multi-Factor Expense Modeling:** Estimates structural upkeep, projected insurance liabilities, energy/utility footprints, and everyday basket goods.
* **Scalable Data Pipeline:** Built with automated data ingestion, feature engineering, and robust model evaluation metrics.
* **API & Integration Ready:** Designed to plug smoothly into modern real estate platforms and decision-support dashboards.

---

## Tech Stack

* **Language:** Python 3.10+
* **Core Libraries:** Pandas, NumPy, Scikit-Learn, Statsmodels
* **Machine Learning:** Regression Ensembles, Gradient Boosting (XGBoost/LightGBM)
* **Version Control:** Git & GitHub

---

## Project Architecture

```text
├── documentation/         # Technical PDF Documentation week by week
├── presentations/         # PDF formatted class phase presentations
├── data/                  # Raw and processed datasets (ZIP code aggregates)
├── demos/                 # Recorded video demos of the application
├── notebooks/             # Exploratory Data Analysis (EDA) and model prototyping
├── src/                   # Source code for data pipelines, feature engineering, and training
│   ├── ingestion.py       # Data gathering and cleaning scripts
│   ├── features.py        # Feature engineering pipeline
│   └── train.py           # Model training and hyperparameter tuning
├── models/                # Serialized production models (.pkl / .joblib)
├── outputs/               # Generated evaluation reports, charts, and predictions
├── requirements.txt       # Project dependencies
└── README.md
