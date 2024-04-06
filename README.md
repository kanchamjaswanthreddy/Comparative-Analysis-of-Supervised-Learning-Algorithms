# Comparative-Analysis-of-Supervised-Learning-Algorithms

DATASET: The dataset comprises several columns including 'type', 'amount', 'nameOrig', 'oldbalanceOrg', 'newbalanceOrig', 'nameDest', 'oldbalanceDest', 'newbalanceDest', 'isFraud', and 'isFlaggedFraud'. These columns contain information regarding various attributes of financial transactions, such as transaction type, amount, origin and destination account details, balance before and after the transaction, and indicators of fraudulent activity.

The 'type' column denotes the type of transaction (e.g., cash transfer, debit, credit). 'amount' represents the monetary value of the transaction. 'nameOrig' and 'nameDest' contain unique identifiers for the origin and destination accounts, respectively. 'oldbalanceOrg' and 'newbalanceOrig' indicate the balance of the origin account before and after the transaction. Similarly, 'oldbalanceDest' and 'newbalanceDest' represent the balance of the destination account before and after the transaction. The columns 'isFraud' and 'isFlaggedFraud' serve as binary indicators, where 'isFraud' identifies whether the transaction is fraudulent, and 'isFlaggedFraud' flags transactions that are potentially fraudulent based on specific criteria.

The dataset can be accessed through the following link: https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data/data

This dataset provides a valuable resource for analyzing and detecting fraudulent financial transactions, and it serves as the foundation for conducting exploratory data analysis, feature engineering, and building predictive models to identify fraudulent activities within financial systems.

COMPARITIVE ANALYSIS: After thorough data cleaning and preprocessing to address missing values and outliers, an in-depth exploratory data analysis (EDA) was conducted, uncovering significant trends and patterns within the dataset. Subsequently, feature engineering techniques were applied to enhance the predictive power of the models, including the creation of new features and encoding categorical variables. Following this preparatory phase, various machine learning algorithms were trained and evaluated using rigorous cross-validation techniques.

The models were assessed based on a comprehensive set of evaluation metrics, including accuracy, precision, recall, F1-score, and ROC-AUC. Notably, Random Forest and Decision Tree models consistently outperformed other algorithms across multiple metrics, showcasing their robustness and reliability. Meanwhile, Neural Networks exhibited promising results, particularly in terms of accuracy and ROC-AUC, although there were challenges with precision and recall for minority classes.

Based on these findings, recommendations suggest Random Forest and Decision Tree algorithms as the most suitable choices for the dataset and problem type, given their strong performance and interpretability. However, further optimization and exploration of Neural Networks may yield improvements in addressing class imbalances and enhancing overall predictive performance.

