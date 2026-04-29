# ARTI-308_lab9
This lab analyzes LendingClub loan data (2007–2010) to build a classification model that predicts whether a borrower will fully repay their loan. LendingClub connects borrowers with investors, making accurate prediction of loan repayment important for reducing financial risk.

The dataset includes financial and credit-related features such as interest rate, FICO score, income, and debt-to-income ratio. 
We perform exploratory data analysis, preprocessing, and build machine learning models including Decision Trees and Random Forests

The goal is to evaluate model performance and compare how well different algorithms handle an imbalanced classification problem in a real-world financial dataset.



What performed better the random forest or the decision tree?

The Random Forest model achieved higher overall accuracy than the Decision Tree (0.85 vs 0.72). However, the Decision Tree performed better at identifying the minority class (not fully paid loans), while the Random Forest was heavily biased toward the majority class and failed to correctly detect most risky loans


Random Forest

Accuracy: 0.85 (higher)

Class 1 recall: 0.02 (very bad)

Only 9 correct predictions of class 1


Meaning:

It almost ignores the risky loans

It predicts most cases as “0”









Decision Tree

Accuracy: 0.72 (lower)

Class 1 recall: 0.24 (better)

105 correct predictions of class 1

 Meaning:
 
It detects more risky loans

But makes more overall mistakes
