# Loan_Approval_AIM_Capstone_Project
Post Graduate Diploma in Artificial Intelligence and Machine Learning-Capstone Project


# =============================================================================
ML-Driven Loan Approval Prediction
# =============================================================================

A supervised machine learning binary classification engine designed to predict borrower borrower solvency and provide data-driven repayment probabilities

# =============================================================================
Problem Statement
# =============================================================================

Traditional lending workflows are frequently hampered by manual intervention, leading to operational bottlenecks and subjective bias. For financial institutions, these inefficiencies manifest in two critical areas:

  -Operational Friction: High-resource allocation toward manual reviews of low-quality applications.

  -Capital Risk & Opportunity Loss: Inaccurate risk modeling results in "Type I errors" (Creditworthy rejections) and "Type II errors" (Default approvals), both of which directly impact the bank's bottom line.

Solution Framework: This project develops a Binary Classification engine using supervised machine learning to predict borrower solvency. By analyzing historical features—including credit architecture, liquidity ratios (DTI), and employment stability—the model provides a data-driven probability of repayment.

Success Benchmarks: The model aims for an optimized threshold where Precision, Recall, and AUC all exceed 95%. This ensures a robust balance between minimizing credit default risk and maximizing market share. Integrated with existing risk controls, this tool empowers senior leadership to make high-velocity, evidence-based lending decisions.

# =============================================================================
Data Source and Description
# =============================================================================


Data Overview: 

This project utilizes a synthetic financial dataset (20,000 samples) designed for Binary Classification of loan approvals. The features span demographic, employment, and credit-specific domains, providing the necessary complexity for high-accuracy predictive modeling.

Source Information:

Original Source: Kaggle: Financial Risk for Loan Approval 
(https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval)

Original Script: CSV Generation.py

Pre-Processing & Modifications:

To improve the data's utility for time-series and relational analysis, the original generation script was modified (CSV Generation_edited.py) to:

-Standardize the ApplicationDate with a 2025 cutoff.
-Assign unique AccountID identifiers to each record to simulate a master customer file.

Edited Script: CSV Generation_edited.py

Data Dictonary: Please see attached file--> Data Dictionary_Loan Approval_Final.xlsx



