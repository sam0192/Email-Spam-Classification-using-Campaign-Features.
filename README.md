# Email Spam Classification using Machine Learning

## 📌 Overview
This project classifies emails as **Spam or Not Spam** using structured email campaign data.
Machine learning models are trained using numerical and categorical features derived from email campaigns.

---

## 🎯 Problem Statement
Email spam impacts communication efficiency and user trust.
The goal of this project is to predict whether an email is spam based on campaign-related attributes.

---

## 📊 Dataset Description
The dataset contains **campaign-level features** related to emails.

### Input Features
- `Email_Type`
- `Subject_Hotness_Score`
- `Email_Source_Type`
- `Customer_Location`
- `Email_Campaign_Type`
- `Total_Past_Communications`
- `Time_Email_sent_Category`
- `Word_Count`
- `Total_Links`
- `Total_Images`

### Target Variable
- `Email_Status`
  - `0` → Not Spam
  - `1` → Spam

---

## 🛠️ Methodology
1. Data inspection and preprocessing
2. Handling categorical and numerical features
3. Feature-target separation
4. Train-test split
5. Classification model training
6. Model evaluation

---

## 🤖 Models Used
- Logistic Regression
- Naive Bayes

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

---

## 🔍 Key Insights
- Subject hotness score impacts spam classification
- Link and image count influence email status
- Simple classifiers perform well on structured data

---

## 🚀 Future Enhancements
- Advanced feature engineering
- Try ensemble classifiers
- Apply explainability (SHAP)
- Deploy as a web application

---

## 🧠 Learnings
- Binary classification on structured datasets
- Handling categorical campaign features
- Model evaluation for imbalance scenarios
