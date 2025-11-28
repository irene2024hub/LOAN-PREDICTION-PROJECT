# LOAN-PREDICTION-PROJECT
Manual loan processing is time-consuming, often leading to delays 

# STUDY BACKGROUND
- Traditional loan approval methods rely heavily on manual reviews, which can be slow and
inconsistent.
- Machine learning offers a faster, more accurate way to evaluate loan applications using historical
data. 
- Financial indicators like income, credit score (CIBIL), assets, and employment status are key features
in prediction.
  - ML models help identify patterns in applicant data, enabling smarter, data-driven lending decisions.
- Automating the loan process reduces administrative workload and enhances operational efficiency. 
  - The study also aims to uncover influential factors in loan approvals, promoting transparency and
financial literacy.

# PROBLEM STATEMENT
- Manual loan processing is time-consuming, often leading to delays in decision-making
and customer dissatisfaction. §Inconsistent approval criteria across different loan officers can result in biased
or unfair decisions. 
- Limited predictive insight into applicants’ financial behavior makes risk assessment
less effective and prone to errors.
- Repetitive administrative tasks consume valuable staff time that could be better
used for strategic operations.
-  Lack of data-driven analysis hinders understanding of which financial indicators
truly affect loan approval outcomes

# Aim and Objectives
<img width="1152" height="465" alt="image" src="https://github.com/user-attachments/assets/305f3562-7a2b-49d4-bd62-ec76905b742d" />

# DATA DESCRIPTION

1. Loan ID – Unique identifier for each loan application. 
2. No of Dependents – Number of financial dependents the applicant has. 
3.  Education – Applicant’s education level, which may affect earning potential. 
4. Self Employed – Indicates whether the applicant is self-employed.
5.  Income Annum – Annual income of the applicant.  Loan Amount – Requested loan amount.
6. Loan Term – Duration for which the loan is granted.  CIBIL Score – Credit score reflecting the applicant’s repayment history. 
7. Residential, Commercial, and Luxury Assets Value – Financial assets owned by the applicant.
8. Bank Asset Value – Total bank balance and financial holdings.
9. Loan Status – Final decision on loan approval (Approved/Rejected).

# METHODOLOGY OVERVIEW
- EXPLORATORY DATA ANALYSIS
- EDA is a crucial step in understanding the dataset before model training.
-  EDA helps in refining the dataset and ensuring high-quality inputs
for the machine learning model
- It involves:  Checking missing values and handling them appropriately.
-  Visualizing data distributions using histograms and Box count plots.
- Identifying correlations between features using heatmaps.
-  Detecting outliers that may affect model performance.
-  
  <img width="1287" height="348" alt="image" src="https://github.com/user-attachments/assets/e5de9c08-b128-40a5-bfac-bb7b609448b2" />

  # HISTOGRAM
  <img width="1152" height="567" alt="image" src="https://github.com/user-attachments/assets/ff407f25-6640-43bf-9e2a-be9f0d40b6ad" />

  # A BREIF INSIGHTS ON EDA CARRIED OUT
 1. BOX PLOT-MISSING VALUES (BOTTOMS SECTION)
-  No_of_dependents has the most missing entries (712), possibly due to applicant omission or data collection issues.,
-   Commercial_assets_value has 107 missing values,
-   Residential Asset Value has 45 missing values , while other columns are fully complete.
-   v Key demographic and financial variables like education,
-    income_anum, and loan_amount are complete, which is good for predictive analysis. q BOX PLOTS
-  Loan Amount vs. Loan Status: Likely reveals that larger loan amounts may be more frequently rejected, suggesting risk-based filtering.
-   CIBIL Score vs. Loan Status: Shows higher scores are associated with approvals, highlighting its predictive value
-   
  2.  SCRIPTIVE STATISTICS OVERVIEW
- The Table Presents Summary Statistics For Various Numerical Columns In The Dataset.
- The Key figures Reveals;
  - income_annumUN
  -  Mean (average): around 2.23e+06, meaning 2.23 million
  -  Min: 180,000, Max: 9 million, showing a wide range with some high earners
- Cibil_score:Centered around 757, with a minimum of 300 and
-  a high of 939. This aligns with typical CIBIL score ranges (300–900), suggesting valid data.
- Asset Values (residential, commercial, luxury, bank): Most values have minimums of 0, indicating many applicants may not own assets in certain categories
     Luxury assets and bank assets have lower means and max values

3.LOAN APPROVAL BAR CHART

