# Credit-Scoring-Project---Home-Credit
Home Credit’s initiative employs statistical and machine learning methods to predict credit scores, aiming to maximize the potential of their data. The project’s goal is to create models that ensure creditworthy customers are not denied loans and to offer loan terms that encourage successful repayment.

# Methodology
The CRISP-DM method was utilized to construct Logistic Regression, Advanced XGBoost, and Advanced LightGBM models. These models were compared to determine the most effective in predicting credit scores.

# Business Understanding:
Problem Statement: Credit scores, ranging from 300 to 850, reflect a consumer’s creditworthiness, which lenders use to assess the likelihood of timely loan repayment. High credit scores improve a borrower’s prospects in the eyes of lenders.

# Model Definition:
Data Integration: Eight primary datasets provided by Home Credit Indonesia were merged using key columns [‘SK_ID_CURR’, ‘SK_ID_PREV’] to streamline data preparation and modeling.
Data Handling: Addressed missing values by removing columns with over 70% missing data, eliminated columns with low variance, and filled empty rows with median values.

# Insights and Campaigns:
- Low-Risk Professions: Accountants, HR Staff, and IT Staff show low credit risk but have low borrowing rates. Campaigns targeting these professions could encourage more credit applications.
- High-Risk Professions: Low Skill Laborers exhibit high payment difficulties, suggesting a cautious approach to credit approvals for this group.
- Unemployed and Maternity Leave: These groups present very high credit risk with few loan applications, warranting careful consideration before extending credit.
- Working Individuals: Frequently apply for loans with low credit risk, indicating that campaigns should be increased to attract more credit applications.

# Model Performance
The Advanced XGBoost model outperformed others with an AUC score of 0.72372, indicating its superior accuracy in credit scoring.
