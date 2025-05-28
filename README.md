# LoanTap_Logistic-Regression

# LoanTap Personal Loan Creditworthiness Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/raghav1saboo/LoanTap_Logistic-Regression/blob/main/LoanTap_Logistic_Regression.ipynb)

## Overview

This repository contains a Jupyter Notebook that focuses on building a logistic regression model to predict the creditworthiness of individuals applying for a Personal Loan through LoanTap. The goal is to determine whether a credit line should be extended to an applicant based on a set of provided attributes.

LoanTap is an online platform offering customized loan products to millennials. This project specifically addresses the underwriting process for their Personal Loan product.

## Problem Statement

Given a set of attributes for an individual, the task is to determine if a credit line should be extended to them. Furthermore, the analysis explores potential repayment terms as business recommendations.

## Dataset

The dataset used for this project is `[LoanTapData.csv]'.

## Data Dictionary

| Feature                 | Description                                                                                                                                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `loan_amnt`             | The listed amount of the loan applied for by the borrower.                                                                                                                                           |
| `term`                  | The number of payments on the loan (36 or 60 months).                                                                                                                                                 |
| `int_rate`              | Interest Rate on the loan.                                                                                                                                                                            |
| `installment`           | The monthly payment owed by the borrower if the loan originates.                                                                                                                                      |
| `grade`                 | LoanTap assigned loan grade.                                                                                                                                                                         |
| `sub_grade`             | LoanTap assigned loan subgrade.                                                                                                                                                                      |
| `emp_title`             | The job title supplied by the Borrower when applying for the loan.                                                                                                                                     |
| `emp_length`            | Employment length in years (0: < 1 year, 10: 10+ years).                                                                                                                                               |
| `home_ownership`        | The home ownership status provided by the borrower.                                                                                                                                                    |
| `annual_inc`            | The self-reported annual income provided by the borrower.                                                                                                                                            |
| `verification_status`   | Indicates if income was verified by LoanTap.                                                                                                                                                           |
| `issue_d`               | The month which the loan was funded.                                                                                                                                                                   |
| `loan_status`           | Current status of the loan - **Target Variable**.                                                                                                                                                     |
| `purpose`               | A category provided by the borrower for the loan request.                                                                                                                                            |
| `title`                 | The loan title provided by the borrower.                                                                                                                                                               |
| `dti`                   | A ratio calculated using the borrower’s total monthly debt payments divided by their monthly income.                                                                                                   |
| `earliest_cr_line`      | The month the borrower's earliest reported credit line was opened.                                                                                                                                   |
| `open_acc`              | The number of open credit lines in the borrower's credit file.                                                                                                                                        |
| `pub_rec`               | Number of derogatory public records.                                                                                                                                                                   |
| `revol_bal`             | Total credit revolving balance.                                                                                                                                                                        |
| `revol_util`            | Revolving line utilization rate.                                                                                                                                                                       |
| `total_acc`             | The total number of credit lines currently in the borrower's credit file.                                                                                                                            |
| `initial_list_status`   | The initial listing status of the loan (W or F).                                                                                                                                                       |
| `application_type`      | Indicates whether the loan is an individual or joint application.                                                                                                                                      |
| `mort_acc`              | Number of mortgage accounts.                                                                                                                                                                         |
| `pub_rec_bankruptcies`  | Number of public record bankruptcies.                                                                                                                                                                  |
| `Address`               | Address of the individual.                                                                                                                                                                           |

## Concepts Used

The Jupyter Notebook implements the following concepts:

* **Exploratory Data Analysis (EDA):** To understand the data and identify patterns.
* **Feature Engineering:** To create new features or transform existing ones to improve model performance.
* **Logistic Regression:** A statistical model used for binary classification to predict the likelihood of loan approval.
* **Precision Vs Recall Tradeoff:** Understanding and potentially adjusting the classification threshold to balance precision and recall based on business needs.

## Getting Started

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/raghav1saboo/LoanTap_Logistic-Regression.git](https://github.com/raghav1saboo/LoanTap_Logistic-Regression.git)
    ```
2.  Navigate to the repository directory:
    ```bash
    cd LoanTap_Logistic-Regression
    ```
3.  Open and run the Jupyter Notebook `LoanTap_Logistic_Regression.ipynb`.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

[Optional: Add a license if you have one, e.g., MIT License]
