# Data

## Dataset

This project uses the **Credit Risk Dataset** published on Kaggle by **laotse**.

Source:
https://www.kaggle.com/datasets/laotse/credit-risk-dataset

The dataset contains borrower and loan characteristics used for credit-risk modeling.

The original dataset contains **32,581 observations**. After data-quality filtering, **32,409 observations** were retained for modeling.

## Target Variable

The modeling target is `loan_status`:

- `0` — non-default
- `1` — observed default outcome

## Download Instructions

The raw dataset is not included in this repository.

Download `credit_risk_dataset.csv` from the Kaggle dataset page and place it in:

data/raw/credit_risk_dataset.csv

Expected project structure:

data/
├── raw/
│   └── credit_risk_dataset.csv
└── README.md

The `data/raw/*.csv` files are excluded from version control through `.gitignore`.

## Scope

This dataset is used for an educational credit-risk modeling project.

The target variable is treated as an observed default outcome and should not be interpreted as a regulatory definition of default under Basel or IFRS 9.

The dataset should also not be interpreted as representative of a current bank lending portfolio.