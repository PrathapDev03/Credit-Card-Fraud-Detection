# Credit Card Fraud Detection

## Task Objectives:
The goal of this project is to develop a classification model to detect fraudulent credit card transactions efficiently. The dataset consists of transaction data including amounts, merchant details, and timestamps. The challenge involves addressing class imbalance and improving model performance to minimize false positives while maintaining high accuracy.

## Steps to Run the Project:
1. **Preprocessing**:
    - Scale the `Amount` and `Time` features using standard scaling.
    - Handle class imbalance using undersampling techniques.
   
2. **Feature Engineering**:
    - The dataset consists of anonymized features from PCA (V1 to V28), along with `Scaled_Amount` and `Scaled_Time` replacing the original amount and time fields.

3. **Model Training**:
    - A Random Forest classifier was trained on the balanced dataset using 80% of the data for training and 20% for testing.

4. **Model Evaluation**:
    - Accuracy: 92.89%
    - Precision: 98.67%
    - Recall: 85.06%
    - F1 Score: 91.36%

## Key Techniques:
- **Class Imbalance**: Addressed by undersampling the majority class (non-fraudulent transactions).
- **Model Evaluation**: Focused on minimizing false positives while ensuring high recall for fraudulent transactions.


