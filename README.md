# Loan Approval Analysis - Power BI Dashboard

## 📌 Project Overview
This repository contains the Power BI project for a Loan Approval Analysis dashboard. The dashboard explores patterns in loan approvals and rejections across applicant demographics, loan grades, loan intent, credit history, income, and home-ownership type to derive actionable insights for risk and credit decisions.

_Source dashboard:_ Power BI Desktop (see `src/Loan_Approval_Analysis.pbix`).

## 📂 Repository Structure
```
Loan-Approval-Analysis/
│
├── data/
│   ├── loan_dataset.csv            # Original dataset (if available)
│   └── data_dictionary.xlsx        # Column descriptions (optional)
│
├── reports/
│   ├── dashboard_screenshots/      # Screenshots of the dashboard
│   │   ├── overview.png
│   │   ├── approval_rate.png
│   │   └── rejection_rate.png
│   └── Loan_Approval_Report.pdf    # Full written report (this repo)
│
├── src/
│   ├── Loan_Approval_Analysis.pbix # Power BI file (main)
│   └── queries/
│       ├── data_cleaning_steps.txt
│       └── calculated_measures.txt
│
├── README.md                       # This file
└── LICENSE
```

## 🧾 Dataset (as shown in dashboard)
- **Total loans (approx):** 33K  
- **Total Approved:** 7,108  
- **Total Rejected:** 25,473  
- **Approval Rate:** ~22% (0.22)  
- **Rejection Rate:** ~78% (0.78)  
- **Average income:** 66.07K  
- **Average credit history:** 5.80  

## 📊 Key Visuals
- Overview dashboard screenshot
- Approval Rate (%) by Risk Level (Medium = 0.23, Low = 0.21)
- Loan Distribution by Grade and Status
- Loan Applications by Home Ownership Type (RENT ≈ 50.48%, MORTGAGE ≈ 41.26%, OWN ≈ 7.93%)
- Loan Intent breakdown (EDUCATION, MEDICAL, VENTURE, PERSONAL, DEBT CONSOLIDATION, HOME IMPROVEMENT)

## 🔍 Key Findings
- Approval rate is low (~22%), rejection high (~78%)
- Approval similar for Medium (23%) and Low (21%) risk levels
- Loan grades A–C have high rejections despite large volumes
- Most applications come from renters (50.48%) and mortgage holders (41.26%)

## 🛠 Tools & Techniques
- Power BI Desktop (data ingestion, transformations, visualizations)
- Power Query (M language) for data cleaning
- DAX for calculated measures

## 🔁 How to reproduce locally
1. Clone repo: `git clone <repo-url>`  
2. Place dataset in `data/loan_dataset.csv`  
3. Open `src/Loan_Approval_Analysis.pbix` in Power BI Desktop  
4. Update data source settings if paths differ  
5. Refresh visuals

## ⚠️ Data Sensitivity & Privacy
- Ensure dataset is anonymized before sharing publicly
- Remove PII and sensitive numeric identifiers

## 📌 Notes & Next Steps
- Export and store key DAX measures and Power Query steps as `.txt`
- Add `data_dictionary.xlsx` for clarity
- Include the narrative PDF report in `reports/`
