LoanTap Credit Risk Prediction

Regression Model to predict loan repayment outcomes, assess credit worthiness of borrowers using their employment and financial behavior.
	• Predicted loan repayment outcomes using customer employment and financial behavior data.
	• Developed a Logistic Regression model leveraging data such as income level, employment status, and past loan repayment history. Optimized feature engineering for improved precision-recall balance.
	• Delivered insights that enhanced risk assessment strategies for loan approvals.

Problem Statement
	• Primary Goal: Predict whether a credit line should be extended to an individual (Binary Classification: "Yes" or "No").
	• Secondary Goals:
		○ Provide recommendations on repayment terms for approved credit lines.
		○ Suggest actions to reduce risk and improve repayment rates.
Key Insights
	• Identified high-risk borrowers using features such as loan amount, interest rate, DTI (Debt-to-Income) ratio, and annual income.
	• Used data analytics to reveal trends, such as longer-term loans having a higher probability of being charged-off.
	• Recommended adjustments to pricing and underwriting standards to improve risk mitigation strategies.
Data and Preprocessing
	• The dataset includes numerical and categorical features such as loan amount, interest rate, employment title, and loan purpose.
	• Steps Taken:
		○ Handled missing data with imputation.
		○ Cleaned outliers using robust IQR-based clipping.
		○ Encoded categorical variables and performed feature reduction using PCA.
Model Development
	1. Feature Engineering
		○ Created new temporal and flagged features (e.g., issue year, loan grade, and employment length).
		○ Applied robust feature scaling techniques to handle data skewness.
	2. Feature Selection
		○ Used Variance Inflation Factor (VIF) and Recursive Feature Elimination (RFE) to identify and retain the most impactful features.
	3. Logistic Regression Models
		○ Developed and tested two Logistic Regression models with SMOTE resampling to address class imbalance (19.6% Charged-Off vs. 80.4% Fully Paid).
Model Performance
	• Accuracy Scores:
		○ Model 1: 77%
		○ Model 2: 80%
	• Evaluation Metrics:
		○ ROC AUC Score: 0.79 - 0.80
		○ The models showed confidence in identifying low-risk borrowers but required improvements for default predictions.
Recommendations
	• Adjust pricing strategies for high-risk groups with high interest rates and DTI ratios.
	• Focus on employment and grade features for more accurate risk segmentation.
	• Monitor and refine the model periodically with updated loan data to improve predictions.
Visualizations
	• Correlation heatmaps were used to highlight relationships between variables and target outcomes.
	• Precision-Recall and ROC curves were plotted to evaluate model trade-offs.
Tools and Technologies
	• Languages: Python
	• Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
Key Takeaways
This project demonstrates the power of Logistic Regression in binary classification tasks and emphasizes the importance of data preprocessing, feature engineering, and resampling techniques to improve model outcomes.
