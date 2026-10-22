# Prosper Lending Loan Risk Factors EDA
Udacity Data Analyst Nanodegree Project 3

> As the Data Analyst in my cohort, I spearheaded the aggregation and cleaning of Prosper’s loan data, focusing on creating an optimized flow of data ready to analyze. This comprehensive project involved advanced cleaning techniques while optimizing computing resources.

## Business Case:

- **Clean & Aggregate Data for Use:** Utilized Python to analyze 114,000 peer-to-peer lending loans with 81 variables on each loan. Performed data cleaning and EDA to explore and analyze borrower profiles, loan characteristics, and risk factors in Prosper’s peer-to-peer lending ecosystem
- **Discover Increased Risk Predictors:** Identify key indicators that predict loan outcomes and inform risk-based decision-making


![Screenshot of Loan Status by Credit Score Range chart](https://github.com/sarahbeze/Prosper-Loans-Communicate-Data-Findings/blob/main/prosper01-1024x599.webp)

![Screenshot of Monthly Payment vs Loan Amount by Loan Term Scatter Plot](https://github.com/sarahbeze/Prosper-Loans-Communicate-Data-Findings/blob/main/prosper02-1024x599.webp)

## Insights & Impact:

- **Loan Purpose Affects Risk Levels:** Categories such as “Debt Consolidation” dominate volume, but riskier categories like “Business” or “Medical” show a higher incidence of default.
- **Credit Health and Debt To Income Impact Loan Performance:** Loans associated with low credit scores and high debt-to-income ratios have higher default rates.
- **Interest Rates Are Tied to ProsperScore:** Borrowers with lower ProsperScores or lower credit scores are charged significantly higher interest rates, reflecting higher perceived risk.

_For Peer Lenders:_ Risk-adjusted lending should consider ProsperScore, credit metrics, and loan purpose as primary filters.

_For Prosper:_ Optimize automated lending decision systems using historic default trends by borrower profile.

The Prosper loan data revealed how credit risk (via ProsperScore, CreditScoreRange, DebtToIncomeRatio) correlates with the terms and costs of loans (e.g., BorrowerRate, MonthlyLoanPayment). We also observed how loan status outcomes depend on borrower characteristics, with high-risk individuals more likely to default. These insights can guide better loan underwriting or investment decisions.
