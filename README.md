# Fraud Detection in Online Transactions

This project focuses on detecting fraudulent online transactions using machine learning models. It includes data preprocessing, visualization, and model evaluation.

---

## Dataset Description

The dataset contains the following columns:

- **step**: Represents a unit of time where 1 step equals 1 hour.
- **type**: Type of online transaction (e.g., PAYMENT, TRANSFER).
- **amount**: The amount of the transaction.
- **nameOrig**: Customer initiating the transaction.
- **oldbalanceOrg**: Customer's balance before the transaction.
- **newbalanceOrig**: Customer's balance after the transaction.
- **nameDest**: Recipient of the transaction.
- **oldbalanceDest**: Initial balance of the recipient before the transaction.
- **newbalanceDest**: New balance of the recipient after the transaction.
- **isFraud**: Indicates if the transaction is fraudulent (1 for Fraud, 0 for No Fraud).

---

## Workflow

### Data Preprocessing:
- Handled missing values.
- Encoded categorical features (`type`) into numerical values.

### Exploratory Data Analysis:
- Visualized transaction type distribution using pie charts.
- Analyzed fraud and non-fraud transaction counts.

### Model Training & Evaluation:
- Trained models: Logistic Regression, Decision Tree, KNN, Naive Bayes, SVM.
- Evaluated using K-Fold Cross-Validation.

### Fraud Prediction:
- Predicted fraud status for new transactions.

---

Key Libraries
pandas
numpy
seaborn
matplotlib
plotly
scikit-learn

