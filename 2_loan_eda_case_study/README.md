# 💸 Loan Default Risk – EDA Case Study (Gramener)

## Objective
Perform exploratory data analysis (EDA) on loan applicants to uncover patterns that lead to loan defaults. Help the company reduce financial losses by identifying risky applicants.

## Business Context
The company is a large online loan marketplace providing personal, business, and medical loans. Each loan decision must balance two risks:
- Rejecting good borrowers → revenue loss
- Approving defaulters → credit loss

This case study uses historical applicant data to identify drivers of loan default such as loan grade, term, employment, and geography.

## Tools Used
- Python: Pandas, Matplotlib, Seaborn
- Jupyter Notebook

## EDA Approach
- Cleaned raw dataset and handled missing values
- Performed univariate analysis on loan term, grade, amount, etc.
- Conducted bivariate analysis (e.g., Grade vs Status, Employment vs Default)
- Used correlation heatmaps and visualizations to summarize key findings

## Key Business Insights
- 🔻 **Grade D–G loans have the highest default rate**
- 📈 **Interest rates rise as loan grade decreases**
- 💼 **Longer employment = lower default risk**
- 📍 **States like CA, TX, NY have higher loan volumes — risk clustering**
- 💳 **Most loans are short-term (~36 months) and under $15,000**

## Outcome
Insights from this EDA can be used to:
- Improve loan approval policies
- Flag high-risk profiles in advance
- Reduce credit losses through better targeting

## Files Included
- `loan_eda.ipynb`: Cleaned and annotated Python notebook
- `EDA_Case_Study_Maanik_Sharma.pdf`: Executive summary of findings
