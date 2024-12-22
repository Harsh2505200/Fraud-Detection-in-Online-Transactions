# Fraud-Detection-in-Online-Transactions
Fraud Detection in Online Transactions
This project focuses on detecting fraudulent online transactions using machine learning models. It includes data preprocessing, visualization, and model evaluation.

Dataset
The dataset contains:

type: Transaction type (e.g., PAYMENT, TRANSFER).
amount: Transaction amount.
oldbalanceOrg: Sender's balance before the transaction.
newbalanceOrig: Sender's balance after the transaction.
isFraud: Fraud label (1 for Fraud, 0 for No Fraud).
Workflow
Data Preprocessing:

Handled missing values.
Encoded categorical features (type) into numerical values.
Exploratory Data Analysis:

Visualized transaction type distribution using pie charts.
Analyzed fraud and non-fraud transaction counts.
Model Training & Evaluation:

Trained models: Logistic Regression, Decision Tree, KNN, Naive Bayes, SVM.
Evaluated using K-Fold Cross-Validation.
Fraud Prediction:

Predicted fraud status for new transactions.
How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/fraud-detection.git
cd fraud-detection
Install dependencies:

bash
Copy code
pip install pandas numpy seaborn matplotlib plotly scikit-learn
Run the script:

bash
Copy code
python fraud_detection.py
Key Libraries
pandas, numpy, seaborn, matplotlib, plotly
scikit-learn
Future Enhancements
Add advanced models like Random Forest and Gradient Boosting.
Implement real-time fraud detection with deployment.
