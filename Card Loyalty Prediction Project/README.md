# Bank Card Transaction and User Loyalty Analysis

This repository contains the code and analysis for the bank card transaction and user (card) loyalty analysis project. The dataset provided by a bank in Brazil aims to practice topics including data quality analysis, statistical analysis, and regression analysis.

## Dataset Description
- **userscore.csv**: Contains card IDs and information about the card itself, including the first month the card was active and the loyalty score calculated by the bank.
- **merchants.csv**: Provides aggregate information for each merchant ID represented in the dataset and can be joined with transaction sets to provide additional merchant-level information.
- **historical_transactions.csv**: Contains up to 3 months' worth of transactions for every card at any of the provided merchant IDs.
- **new_merchant_transactions.csv**: Contains transactions at new merchants (merchant IDs that the card has not yet visited) over two months.

## Tasks
### Data Exploration
- **Q1**: Describe how to utilize merchants.csv, historical_transactions.csv, and new merchant transactions.csv for user loyalty prediction.
- **Q2**: Discuss the quality of the dataset, considering missing values, missing value patterns, missing value mechanism, and noise.
- **Q3**: Perform necessary data cleaning based on the assessment in Q2.

### Statistics and Hypothesis Test
- **Q4**: Report important statistics in the preprocessed data, including the target user loyalty score.
- **Q5**: Propose two hypothesis tests exploring information related to the user loyalty score.

### Regression Analysis
- **Q6**: Create a regression model for user loyalty score prediction based on the analysis.
- **Q7**: Detect if multicollinearity exists in selected features.
- **Q8**: Build one regression model and report its performance on the train and test datasets.

## Dependencies
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
