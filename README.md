# Credit-Card-Fraud-Detection-ML
Project Overview
This project focuses on detecting fraudulent transactions using machine learning models. The dataset used contains credit card transactions from European cardholders in September 2013, with fraud cases highly imbalanced.

Problem Statement
Credit card fraud is a significant financial risk, leading to losses for banks and merchants. The challenge is to accurately detect fraud while minimizing false positives, ensuring legitimate transactions are not blocked unnecessarily.
📂 Dataset Details
- Source: Kaggle
- Time Period: September 2013
- Features: 30 anonymized transaction variables (V1 to V28), Amount, Time
- Target Variable: Class (0 = Non-fraud, 1 = Fraud)
- Imbalance: Only 0.172% of transactions are fraudulent
🛠️ Technologies & Libraries Used
- Programming Language: Python
- Libraries:
- Data Handling: pandas, numpy
- Visualization: matplotlib, seaborn
- Preprocessing: sklearn.preprocessing
- Feature Engineering: Recursive Feature Elimination (RFE)
- Model Training: Logistic Regression, Random Forest, Decision Tree
- Evaluation: Confusion Matrix, Accuracy Score, AUC-ROC Curve
- Imbalance Handling: Undersampling
🏗️ Project Workflow
1️⃣ Data Preprocessing
- Loaded dataset and checked missing values
- Standardized Amount feature, and removed unnecessary variables
2️⃣ Exploratory Data Analysis (EDA)
- Visualized fraud distribution using boxplots & violin plots
- Identified correlations between fraud occurrences and transaction features
3️⃣ Feature Engineering
- Selected top features using RFE
- Addressed class imbalance using undersampling
4️⃣ Model Building & Evaluation
- Trained three models: Logistic Regression, Random Forest, Decision Tree
- Compared performance using:
- Confusion Matrix (False Positives vs. False Negatives)
- Precision-Recall tradeoff
- AUC-ROC Curve (99% AUC for Random Forest)
- Best Model: Random Forest (Highest recall & precision balance)
📈 Results & Conclusion
- Random Forest outperformed other models, correctly detecting fraud while keeping false positives minimal.
- AUC-ROC = 0.99, showing strong fraud detection capability.
- Fraud patterns revealed that most fraudulent transactions have lower amounts and distinct feature distributions.
💡 Business Impact
This model can help financial institutions and payment platforms:
- Reduce financial losses by proactively flagging fraudulent transactions.
- Enhance security while ensuring smooth transactions for valid customers.
- Optimize fraud detection systems with machine learning-driven insights.
📜 Next Steps
- Implement real-time fraud detection by integrating API-based transaction screening.

  Example: https://github.com/Tanushkasoni/Credit-Card-Fraud-Detection-ML/blob/main/Python-%20Credit%20Card%20Fraud%20Detection.png

