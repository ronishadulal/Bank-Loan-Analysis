# Bank-Loan-Analysis
# Bank Loan Analysis

Data analyst portfolio project analyzing a bank's loan portfolio (38,576 records) 
to monitor lending performance and loan quality using Python.

## Objective
Assess loan quality (Good Loan vs Bad Loan), track KPIs (applications, funding, 
repayment, interest rate, DTI), and surface risk trends for a lending operations team.

## Tools Used
Python (pandas, NumPy) · Matplotlib/Seaborn/Plotly/Squarify · 

## Key Findings
- 86.2% of loans are Good Loans; 13.8% are Charged Off, resulting in ~$28.2M in 
  unrecovered principal
- Applications, funding, and repayments all grew double-digit % month-over-month
- debt_consolidation drives ~$230M in lending, more than double the next category
- Renters account for over 40% of funded value — a relevant risk factor given 
  lower collateral

## Process
1. **Data Cleaning** – handled nulls, standardized categories, flagged income outliers
2. **Feature Engineering** – built loan_category (Good/Bad), date breakdowns, 
   ordinal employment length
3. **KPI Analysis** – Total/MTD/MoM metrics for applications, funding, repayment
4. **Visualizations** – monthly trends, state map, term/purpose/ownership breakdowns
5. **Recommendations** – target underwriting review by grade/purpose/ownership segment

## Files
- `notebooks/Banking_Analysis.ipynb` – full Python analysis

