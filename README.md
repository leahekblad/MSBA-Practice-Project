# MSBA-Practice-Project
Predictive Model for Home Credit Loan Repayment Capability

**Business Problem**
Financial institutions and lenders often use a customer’s credit history to approve loans and set interest rates. Individuals who lack a traditional credit history are frequently denied loans or offered higher interest rates, despite their potential to repay loans. This creates a missed opportunity for both the borrower and the creditor. Home Credit seeks to solve this problem by using alternative data sources to better assess applicants' creditworthiness and reduce barriers to access.

**Project Objective**
The goal of this project is to develop a predictive model that can evaluate an individual’s loan repayment potential without relying on traditional credit scores. Specifically, the model will leverage alternative data, such as transactional data, to assess the likelihood that an applicant will successfully repay a loan without defaulting. This approach will allow Home Credit to:

- Expand credit access to underserved individuals who lack a traditional credit history.
- Provide fairer interest rates and more accurate loan terms for applicants based on their repayment potential.
- Reduce the risk of defaults by using more comprehensive and predictive identifiers.

A successful model will increase approval rates for creditworthy individuals, enabling Home Credit to grow its customer base responsibly while balancing risk and opportunity.

**Solution to Business Problem**
To solve the business problem, we used a supervised machine learning approach to build a model capable of predicting loan repayment success or failure. Key steps in our solution included:

1. Data Preprocessing: Cleaning the data and handling missing values, ensuring that the dataset was ready for model training.
2. Feature Engineering: Creating new features based on transactional data, such as housing information and vehicle age, to improve model accuracy.
3. Model Selection: We tested several machine learning algorithms
4. Ensemble Methods: We combined predictions from multiple models to create an ensemble approach, improving model robustness by reducing variance and bias.
   
The Random Forest model emerged as the most effective, with the highest AUC-ROC and F1-Score, indicating the best balance of accuracy and recall. Additionally, ensemble methods further improved the model’s performance by integrating predictions from multiple models and producing the highest Kaggle submission score.

**Individual Contributions**
- EDA
- Modeling
1. Penalized Regression
2. Naive Bayes
3. Random Forest

**Difficulties Encountered**
During the project, we encountered several challenges:

*Handling Missing Data:* The substantial amount of missing values in several features (such as OWN_CAR_AGE) required us to carefully consider the best way to handle missing values without introducing bias or distorting relationships in the data.

*Feature Complexity:* High cardinality in categorical variables (such as occupation type) introduced complexity in the modeling process, requiring us to consider adjusting encoding strategies.

*Imbalanced Target Variable:* With significantly more non-default cases than default cases, we had to use resampling techniques to address the class imbalance, ensuring that the model was not biased towards predicting the majority class.

**What I Learned in the Project**

This project provided valuable insights into machine learning model development and data preprocessing for financial applications:

*Handling Real-World Data:* I learned how to handle missing values, deal with high-cardinality features, and address class imbalances, all of which are common challenges in financial data science.

*Feature Engineering:* Creating new features from raw data significantly improved model performance, especially when dealing with non-traditional data sources. 

*Model Evaluation:* Evaluating models using multiple metrics (AUC-ROC, precision, recall, F1-Score) is crucial for understanding their strengths and weaknesses

*Interpreting Results:* As important as it is to create successful models and generate results, it's more important how you propose to implement these changes. Being able to transcribe data-driven results into  business solutions for stakeholders is crucial in driving change and providing successful results.
