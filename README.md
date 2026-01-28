# Credit Risk Analysis & Loan Default Prediction
## Project Overview

Traditional financial institutions rely heavily on historical credit records when issuing loans. This approach leads to high rejection rates, especially for applicants with little or no formal credit history, despite many of them being financially capable of repayment.

This project aims to analyze loan applicant data to:

Identify credit-worthy customers overlooked by traditional systems

Improve loan decision accuracy

Reduce financial exclusion while managing default risk

# Business Problem

A significant portion of loan applications are rejected due to limited or missing credit history rather than actual inability to repay. As a result:

Banks miss out on profitable customers

Financial inclusion remains low

Risk models become overly conservative

# Main Objective

To develop a data-driven credit risk framework that identifies overlooked but credit-worthy loan applicants and improves loan approval decisions without increasing default risk.

# Criterion of Success

To reduce the rejection of creditworthy applicants by at least 30–40% among customers with thin or non-existent credit histories compared to a traditional credit-history-only baseline.
To lower False Negatives (good borrowers incorrectly declined) by a minimum of 50%, while keeping default risk within acceptable thresholds.
To demonstrate that ignored features (cash-flow stability, rent payment regularity, skill-based stability income, and first time employees) contribute significantly to credit decisions through measurable feature importance.
To increase approved loan volume by 8–12% without a corresponding increase in default rates, reflecting recovered missed lending opportunities.


# Dataset Description

The dataset contains applicant demographic, financial, employment, and loan information, including:

Income and employment details

Credit and annuity amounts

Loan history and application characteristics

Target variable indicating loan default

# Project Workflow

The project follows a structured data science pipeline:

Data Understanding

Review data sources, structure, and business context

Data Validation

Completeness checks

Accuracy validation

Consistency checks across fields

Range and logical validations

Detection of anomalies and inconsistencies

Exploratory Data Analysis (EDA)

Univariate analysis

Bivariate analysis with the target variable

Multivariate analysis and correlation assessment

Distribution, skewness, and outlier analysis

Feature Engineering

Creation of ratio-based financial features

Handling missing values

Scaling numerical features

Eliminating data leakage

Model Preparation

Clear separation of features and target

Train-test split

Feature selection and importance analysis

Key Techniques Used

Data validation and consistency checks

Statistical EDA

Correlation and distribution analysis

Feature engineering and scaling

Data leakage prevention

Business-driven evaluation metrics

# Tools & Technologies

Python

Pandas, NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook

# Key Insights

Several non-traditional features show strong predictive power

Income and credit ratios outperform raw values

Proper data validation significantly improves model reliability

Preventing data leakage is critical for realistic performance evaluation

Ethical Considerations

No personal identifiers are exposed

The model aims to promote fair lending and financial inclusion

Decisions are data-driven and auditable

# Future Improvements

Model comparison (Logistic Regression, Random Forest, XGBoost)

Fairness and bias analysis

Threshold optimization based on business cost



## Author

## Akau Bior Alier
