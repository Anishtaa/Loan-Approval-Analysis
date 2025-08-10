# Loan Approval Analysis - Power BI Dashboard

## 📌 Project Overview
This Power BI dashboard analyzes loan application data to identify trends in approvals and rejections. It examines applicant demographics, loan grades, loan intent, credit history, income levels, and home-ownership types to provide insights for credit risk assessment.

## 📂 Repository Structure
```
Loan-Approval-Analysis/
│
├── data/
│   └── credit_risk_dataset.csv
│
├── reports/
│   ├── Final_Report.pdf
│   └── screenshot/
│       └── Loan_Approval_Analysis_Dashboard.png
│
├── src/
│   ├── Loan_Approval_Analysis.pbix
│   └── queries/
│       └── DAX.txt
│
├── README.md
└── .gitattributes
```

## 🧾 Dataset
- Total loans: ~33K  
- Total approved: 7,108  
- Total rejected: 25,473  
- Approval rate: ~22%  
- Rejection rate: ~78%  
- Average income: 66.07K  
- Average credit history: 5.80  

## 📊 Key Visuals
![Loan Approval Analysis Dashboard](reports/dashboard_screenshots/Loan_Approval_Analysis_Dashboard.png)

- Approval rate by risk level (Medium = 0.23, Low = 0.21)  
- Loan distribution by grade and status  
- Loan applications by home ownership type (RENT ≈ 50.48%, MORTGAGE ≈ 41.26%, OWN ≈ 7.93%)  
- Loan intent categories: Education, Medical, Venture, Personal, Debt Consolidation, Home Improvement  

## 🔍 Key Findings
- Approval rates are low (~22%) and rejection rates high (~78%).  
- Medium and Low risk categories have similar approval percentages.  
- Loan grades A–C show higher rejection counts despite large application volumes.  
- Most applicants are renters or mortgage holders, with fewer owning their homes outright.  

## 🛠 Tools & Techniques
- Power BI Desktop for dashboard creation  
- DAX for calculated measures  
- Power Query for data cleaning and transformations  

## 📌 Notes
- The DAX measures are documented in `src/queries/DAX.txt`.  
- The full report is available in `reports/Final_Report.pdf`.  
- Dashboard screenshots are stored in `reports/screenshot/`.  
