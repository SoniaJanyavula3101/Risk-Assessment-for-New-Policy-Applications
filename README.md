# Automated Underwriting Risk Assessment System

This repository contains an automated underwriting system that evaluates insurance applications and determines **acceptance**, **rejection**, or **need for additional information** based on a combination of:

✅ **Rule-based logic**  
✅ **Machine Learning risk scoring**

---

## 🚀 **Project Overview**

Insurance underwriting is the process of assessing risk and determining whether to approve or reject an application. This project automates the underwriting process using:

1. **Rules Engine:** Implements underwriting guidelines such as age limits, occupation risk, smoker status, and medical report requirements.
2. **ML Risk Scoring:** Uses a Decision Tree Classifier to predict the risk category based on historical data.

---

## 🔧 **Files in this Repository**

| File | Description |
|------|-------------|
| `risk_assessment.ipynb` | Jupyter notebook implementing rules-based and ML-based underwriting system. |

---

## 🧠 **How it Works**

1. **Application intake**: Receives structured application data as input.
2. **Rules evaluation**: Applies business rules to determine eligibility.
3. **ML risk scoring**: Computes risk probability using a trained Decision Tree Classifier.
4. **Decision output**: Returns `Accept`, `Reject`, or `Needs Additional Information` with reasons.

---

## ⚙️ **Technologies Used**

- Python
- Pandas
- Numpy
- Scikit-learn (DecisionTreeClassifier)
- Jupyter Notebook

---

## 💻 **Running the Notebook**

1. Clone the repository:

```bash
git clone https://github.com/SoniaJanyavula3101/Risk-Assessment-for-New-Policy-Applications.git
cd Risk-Assessment-for-New-Policy-Applications


 Results
The system outputs underwriting decisions with clear reasoning for each test application input. It is designed for scalability and future integration with APIs for production deployment.

