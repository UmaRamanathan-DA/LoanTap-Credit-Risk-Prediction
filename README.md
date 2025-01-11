# LoanTap Credit Risk Prediction

A Regression Model to predict loan repayment outcomes and assess the creditworthiness of borrowers based on their employment and financial behavior.

- Predicted loan repayment outcomes using customer employment and financial behavior data.
- Developed a Logistic Regression model leveraging data such as income level, employment status, and past loan repayment history.
- Delivered actionable insights that enhanced risk assessment strategies for loan approvals.

---

## Problem Statement
- **Primary Goal**: Predict whether a credit line should be extended to an individual (Binary Classification: "Yes" or "No").
- **Secondary Goals**:
  - Provide recommendations on repayment terms for approved credit lines.
  - Suggest actions to reduce risk and improve repayment rates.

---

## Key Insights
- Identified high-risk borrowers using features such as loan amount, interest rate, DTI (Debt-to-Income) ratio, and annual income.
- Discovered trends, including that longer-term loans have a higher probability of being charged-off.
- Recommended adjustments to pricing and underwriting standards to enhance risk mitigation strategies.

---

## Data and Preprocessing
- **Dataset**: Includes numerical and categorical features such as loan amount, interest rate, employment title, and loan purpose.
- **Preprocessing Steps**:
  - Handled missing data with imputation.
  - Cleaned outliers using robust IQR-based clipping.
  - Encoded categorical variables and performed feature reduction using PCA.
