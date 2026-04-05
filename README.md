# Transaction Approval Rate Prediction — Solidgate INT20H Challenge

> **Note on Data:** This model was developed during the **INT20H 2026 Hackathon** on Kaggle within a strict 20-hour time limit. The submitted solution was trained on a real payment transaction dataset provided by Solidgate. The version of the notebook published in this repository uses a **synthetic dataset** that is structurally identical to the original but contains no real transaction data to comply with privacy constraints.

## Project Overview
Approval Rate (AR) is one of the most critical KPIs in the payment processing industry, reflecting the percentage of transactions successfully authorized by issuing banks. 

This project aims to forecast the outcome of online payment transactions (`is_success`) based on input parameters and historical behavioral signals. By accurately predicting approval probabilities, payment orchestrators can optimize their cascading logic (routing payments through different acquiring banks) to maximize overall revenue.

## Authors
Developed by students of the Institute for Applied System Analysis (IASA) at Igor Sikorsky Kyiv Polytechnic Institute (KPI):
* Yuriy Greben
* Maryna Borovska 
* Tymofii Shalman 

## Repository Structure
```text
├── notebooks/          # Jupyter notebooks for EDA and modeling
│   └── int20h-ds-transactions-approval-rate-prediction.ipynb
├── .gitignore          # Ignored files and virtual environments
├── README.md           # Project documentation
├── LICENSE.txt         # Project license
└── requirements.txt    # Python dependencies