# MSBA-Practice-Project
Predictive Model for Home Credit Loan Repayment Capability

**Business Problem**
Financial institutions and lenders often use a customer’s credit history to approve loans and set interest rates. Individuals who lack a traditional credit history are frequently denied loans or offered higher interest rates, despite their potential to repay loans. This creates a missed opportunity for both the borrower and the creditor. Home Credit seeks to solve this problem by using alternative data sources to better assess applicants' creditworthiness and reduce barriers to access.

**Project Objective**
This project aims to build a predictive model that evaluates loan repayment capability for individuals with limited or no traditional credit history. Financial institutions typically rely on credit scores, but many individuals lack comprehensive credit records, limiting their access to credit or subjecting them to higher interest rates. A successful model will allow Home Credit to assess applicants based on alternative data, expanding credit access responsibly.

**Individual Contributions**
Penalized Regression
Naive Bayes
Random Forest

**Business Value of Solution**
The model that performed best was Random Forest, achieving the highest AUC-ROC and F1-Score, which balanced accuracy and recall. The addition of Ensemble Methods further improved model performance by combining predictions from multiple models, reducing bias and variance.

Individuals with limited or no credit history can still be accurately assessed for loan repayment capabilities when alternative data is used, such as housing information and vehicle age.
By leveraging feature engineering and balancing class distributions, we can increase loan approval rates while maintaining an acceptable risk threshold for lenders.
The business value of this model is significant as it opens the door to extending credit to a larger portion of the population, increasing Home Credit’s customer base.
Business Impact

**Difficulties Encountered**
During the project, we encountered several challenges:

**Handling Missing Data:** The substantial amount of missing values in several features (such as OWN_CAR_AGE) required us to carefully consider the best way to handle missingness without introducing bias or distorting relationships in the data.
**Feature Complexity: ** High cardinality in categorical variables (such as occupation type) introduced complexity in the modeling process, requiring us to consider dimensionality reduction techniques and adjust encoding strategies.
**Imbalanced Target Variable: **With significantly more non-default cases than default cases, we had to use resampling techniques (like SMOTE) to address the class imbalance, ensuring that the model was not biased towards predicting the majority class.

**What I Learned in the Project**

This project provided valuable insights into machine learning model development and data preprocessing for financial applications:

Handling Real-World Data: We learned how to handle missing values, deal with high-cardinality features, and address class imbalances, all of which are common challenges in financial data science.
Feature Engineering: Creating new features from raw data significantly improved model performance, especially when dealing with non-traditional data sources.
Model Evaluation: Evaluating models using multiple metrics (AUC-ROC, precision, recall, F1-Score) is crucial for understanding their strengths and weaknesses, especially in business applications where decision-making is key.
