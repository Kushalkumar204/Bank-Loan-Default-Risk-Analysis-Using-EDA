# Bank-Loan-Default-Risk-Analysis-Using-EDA
Project Overview:
This case study focuses on applying Exploratory Data Analysis (EDA) to understand risk analytics in banking and financial services. The aim is to analyze patterns in loan data to minimize the risk of financial loss due to loan defaults while ensuring that applicants capable of repaying loans are not unjustly rejected.

Business Understanding:
Loan providing companies face challenges in approving loans for applicants with insufficient or non-existent credit histories. This can lead to potential defaulters exploiting the system. The objective is to analyze data to identify patterns that indicate loan repayment difficulties and to use these insights to make informed lending decisions.

Scenarios:

Approved: Loan application is approved.
Cancelled: Loan application is cancelled by the client.
Refused: Loan application is rejected by the company.
Unused Offer: Loan offer is cancelled by the client at various stages of the process.
Business Objective:
The goal is to identify patterns indicating difficulties in paying installments. This analysis can be used to make decisions such as denying loans, reducing loan amounts, or lending at higher interest rates to risky applicants. The company aims to understand the driving factors behind loan defaults to enhance risk assessment and portfolio management.

Methodology and Tools Used:
1. Data Collection and Preprocessing:

Data Sources: Loan application data containing client information, payment histories, and loan statuses.
Cleaning and Manipulation: Handling missing values, correcting data types, and normalizing data to ensure consistency and accuracy.
2. Exploratory Data Analysis (EDA):

Imbalance Analysis: Evaluating the distribution of default and non-default cases to understand class imbalance.
Categorical Variable Analysis: Analyzing categorical features such as loan status, loan type, and client demographics.
Numerical Variable Analysis: Examining numerical features like loan amount, interest rate, and installment amounts.
3. Identifying Patterns and Insights:

Correlation Analysis: Assessing the relationships between variables to identify potential predictors of loan default.
Visualizations: Using histograms, box plots, scatter plots, and heatmaps to visually explore data distributions and relationships.
Risk Factors: Identifying key variables that indicate higher risks of default, such as high debt-to-income ratios, low credit scores, and late payment histories.
4. Implementation and Tools:

Python Libraries: Utilizing libraries such as pandas for data manipulation, matplotlib and seaborn for visualizations, and scikit-learn for initial data preprocessing.
Jupyter Notebooks: Documenting the EDA process and findings in an interactive and shareable format.
Detailed Steps:
Data Cleaning:

Removed or imputed missing values.
Corrected inconsistencies in data entries.
Standardized data formats.
Data Exploration:

Analyzed distributions of key variables.
Examined relationships between variables using correlation matrices.
Visualized data to identify trends and outliers.
Feature Engineering:

Created new features from existing data to enhance predictive power.
Grouped similar categories to reduce complexity.
Pattern Identification:

Conducted statistical tests to identify significant predictors of loan default.
Used visualizations to highlight key insights and patterns.
Reporting and Recommendations:

Summarized findings in a comprehensive report.
Provided actionable insights and recommendations for risk management.
Suggested potential adjustments to lending criteria based on identified risk factors.
Conclusion:
By applying EDA to the loan application data, significant insights were gained into the factors influencing loan default risk. This analysis can help the company make informed decisions to mitigate financial risks while ensuring deserving applicants are not unfairly denied loans. The identified patterns and driving factors provide a robust foundation for further predictive modeling and risk assessment strategies.
