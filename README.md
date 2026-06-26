# 💳 Credit Risk Assessment using Machine Learning

A Machine Learning project that predicts the **creditworthiness of loan applicants** using historical financial data. This project compares the performance of multiple classification algorithms—**Logistic Regression, Random Forest, and XGBoost**—to determine the most effective model for credit risk prediction.

---

## 📌 Project Overview

Financial institutions must evaluate whether a loan applicant is likely to repay a loan. This project develops a credit scoring model that classifies applicants into different risk categories based on demographic and financial attributes.

The project includes data preprocessing, feature engineering, model training, evaluation, and comparative performance analysis.

---

## ✨ Features

* 📊 Credit risk prediction using supervised machine learning
* 🧹 Data preprocessing and cleaning
* 🔠 Categorical feature encoding
* ✂️ Train-test data splitting
* 🤖 Multiple classification models
* 📈 Performance comparison using evaluation metrics
* 📉 Confusion Matrix visualization
* 🎯 Accuracy, Precision, Recall, and F1-Score evaluation

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

---

## 📂 Dataset

**Dataset:** `credit_risk_assessment_500_samples.csv`

The dataset contains applicant information such as:

* Age
* Income
* Employment Status
* Credit History
* Loan Amount
* Existing Debt
* Other financial attributes
* Credit Risk (Target Variable)

---

## 🤖 Machine Learning Models

The following algorithms are implemented and compared:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

---

## ⚙️ Project Workflow

```text
Data Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Encoding
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
 ├── Logistic Regression
 ├── Random Forest
 └── XGBoost
        │
        ▼
Prediction
        │
        ▼
Performance Evaluation
```

---

## 📊 Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help compare the predictive performance of each algorithm.

---

## 📁 Project Structure

```text
Credit-Risk-Assessment/
│── credit_risk_assessment.ipynb
│── credit_risk_assessment_500_samples.csv
├── README.md
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/credit-risk-assessment.git
cd credit-risk-assessment
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

### Run the Notebook

```bash
jupyter notebook
```

Open:

```
credit_risk_assessment.ipynb
```

---

## 📈 Expected Output

The notebook performs:

* Dataset loading
* Data preprocessing
* Model training
* Credit risk prediction
* Comparative model analysis
* Accuracy and classification report generation
* Confusion matrix visualization

---

## 🎯 Learning Outcomes

This project demonstrates:

* Data preprocessing techniques
* Label Encoding
* Supervised Machine Learning
* Binary Classification
* Model comparison
* Performance evaluation
* Credit scoring applications
* End-to-end machine learning workflow

---

## 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Feature importance analysis
* ROC-AUC Curve
* Model deployment using Flask/FastAPI
* Interactive dashboard using Streamlit
* Real-time credit scoring API

---

## 👨‍💻 Author

Harshit Singh

---

## 📄 License

This project is intended for educational and research purposes.
