EDA - Loan Default Risk Analysis
Problem Statement
This assignment focuses on performing Exploratory Data Analysis (EDA) to analyze and visualize data to understand the patterns and factors influencing loan defaults. The goal is to use EDA techniques to identify trends, relationships, and insights from loan application data that can be used to make better decisions in risk analytics.

Introduction
In the banking and financial services sector, loan providers often face challenges in assessing the creditworthiness of potential customers, particularly when they have limited or no credit history. This can lead to either rejecting applicants who can repay the loan or approving loans to those likely to default, resulting in financial losses.

In this assignment, we apply EDA techniques to understand how customer profiles and loan attributes influence the likelihood of default, thus enabling better-informed decisions by the loan-providing company.

Business Understanding
Loan providers need to carefully analyze loan applications to make two critical decisions:

Approve: If the applicant is likely to repay the loan, but rejecting them could result in lost business.

Reject: If the applicant is unlikely to repay the loan, approving them could result in a financial loss.

To understand this risk, we look at data from loan applications, with two major scenarios:

Clients with payment difficulties: These clients had late payments on at least one of the first few installments.

Clients with no payment difficulties: These clients made timely payments.

The decisions made by the company during the loan process can be classified into four categories:

Approved: Loan is approved for the applicant.

Cancelled: The applicant cancels the loan after approval.

Refused: Loan is rejected due to non-fulfillment of company requirements.

Unused Offer: Loan is canceled at different stages in the process.

Dataset
The dataset used in this assignment contains information about the loan application process, including customer details, loan characteristics, and the loan outcome. The goal is to analyze this data to determine which attributes contribute to the likelihood of a loan default.

Project Objective
Apply EDA techniques to identify patterns and correlations between customer attributes and loan outcomes.

Visualize insights that help understand the risk of loan defaults.

Support the development of better decision-making strategies for loan approvals and rejections.

Files Included
Loan_Default_EDA.ipynb: Jupyter Notebook containing the full EDA process.

Loan_Default_Assignment.pptx: Presentation slides containing subjective answers and insights from the assignment.

Usage
To run the Jupyter notebook, ensure you have the following Python libraries installed:

pandas

matplotlib

seaborn

numpy

scikit-learn
