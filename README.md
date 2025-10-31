
# Loan Approval Prediction

This project builds predictive models to determine whether a loan application will be approved based on applicant information. The workflow includes data preprocessing, feature selection, handling class imbalance, and model evaluation using F1 score as the main metric.

---

## Objective
Develop a classification model to predict loan approval, evaluate performance on imbalanced data, and explore improvements using SMOTE to balance the training dataset.

---

## Project Structure
```
|- data/
   |- loan_approval_preprocessed.csv
|- results/
   |- evaluation.csv
|- src/
   |- loan_approval_prediction.ipynb
|- .gitignore
|- README.md
|- requirements.txt
```

---

## Methodology
- **Dataset:** Loan Approval Prediction Dataset (via KaggleHub)  
- **Preprocessing:** Handle missing values, encode categorical features, clean column names  
- **Feature Selection:** ANOVA F-test to select top features  
- **Train-Test Split:** 80% train, 20% test with stratification  
- **Models:** Logistic Regression, Decision Tree Classifier  
- **Class Imbalance Handling:** SMOTE applied on training set  
- **Evaluation:** Precision, Recall, and F1 Score (F1 used for model comparison)  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Tasneem-Helal/loan-approval-prediction.git
   cd loan-approval-prediction/src
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook src/loan_approval_prediction.ipynb
   ```

---

## Author
**Tasneem Helal**  
Mechatronics Engineer | Machine Learning Enthusiast  
[LinkedIn](https://linkedin.com/in/tasneemhelal) | [GitHub](https://github.com/Tasneem-Helal)

