# PersonalLoanApprovalPredictionModel
Classification model to predict personal loan purchases using decision trees with pruning, handling class imbalance and business insights.
![Loan image](https://github.com/vaishnavipalyam/PersonalLoanApprovalPredictionModel/blob/main/bank-loan-successfully-illustration-concept-on-white-background-vector.jpg)

## 🔍 Problem Statement
Banks want to identify potential customers likely to opt for personal loans so they can run targeted marketing campaigns. The target variable is highly imbalanced (only 9% success rate), so the model needs to maximize recall without sacrificing too much precision.

## 📂 Project Structure
- `PersonalLoanCampaign_VaishnaviHP.ipynb`: Jupyter notebook with EDA, model building, evaluation, and business recommendations.
- `Loan_Model.csv` : The dataset used for building the model.

## ✅ Techniques Used
- Exploratory Data Analysis (EDA)
- Decision Tree Classifier
- Class Imbalance Handling (Pruning, Class Weights)
- Model Evaluation using Accuracy, Precision, Recall, and F1 Score
- Business Recommendations based on feature splits and model insights

## 🧠 Best Model
- **Post-Pruned Decision Tree**
  - Recall: 0.993
  - Precision: 0.66
  - F1 Score: 0.79
  - Chosen for maximizing recall while maintaining a reasonable false positive rate.

## 💼 Business Recommendations
- Target high-income and well-educated segments
- Consider potential in high-credit-spend low-income groups
- Deploy model in campaigns and monitor precision over time

## 📌 Author
Vaishnavi H P

## 📄 License
This project is for academic and educational purposes.
