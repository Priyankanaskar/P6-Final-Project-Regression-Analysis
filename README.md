# 📊 Regression Analysis: Insurance Cost Prediction

### 👨‍💻 Author:  **Priyanka Naskar** 

**Date:**9 April 2025

##### Git : https://github.com/Priyankanaskar/ml_regression_priyankanaskar

###### Notebook:https://github.com/Priyankanaskar/ml_regression_priyankanaskar/tree/main/Data
---

## 📁 Project Overview

This project applies regression analysis to predict **medical insurance charges** based on user attributes such as age, BMI, and smoking status using Python and scikit-learn.

The goal is to:
- Understand the relationships between personal health attributes and insurance cost.
- Train and evaluate linear regression models and advanced pipelines.
- Use exploratory data analysis (EDA) to inform feature selection and improve model performance.

---

## 📂 Files in This Repository

| File Name | Description |
|-----------|-------------|
| [`regression_priyanka.ipynb`](https://github.com/Priyankanaskar/ml_regression_priyankanaskar/blob/main/Data/regression_priyanka.ipynb) | Full EDA and regression notebook |
| [`peer_review.md`](https://github.com/Priyankanaskar/ml_regression_priyankanaskar/blob/main/peer_review.md)| Peer review for another classmate's project |
| `data/insurance.csv` | Cleaned dataset used for training the model |

---

## 🧪 Dataset

We use the **Medical Cost Personal Dataset** from Kaggle which contains:
- Age
- Sex
- BMI
- Number of children
- Smoker status
- Region
- Insurance charges (target variable)

---

## 🧰 Getting Started (Run Locally)

1. Clone this repo:
```bash
git clone https://github.com/Priyankanaskar/ml_regression_priyankanaskar
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  
```

3.Install required packages:
```bash
pip install -r requirements.txt
```

4.Open the Jupyter notebook:
```
https://github.com/Priyankanaskar/ml_regression_priyankanaskar/blob/main/Data/regression_priyanka.ipynb
```

## 📈 Key Findings
Age and smoking status are major predictors of insurance charges.

Regression models performed well (R² ≈ 0.85), with Random Forest and Pipeline Regression outperforming the basic linear model.

Polynomial transformations helped capture non-linear patterns in the data.

BMI, while influential, interacts heavily with smoking status.

### 🔗 Links
📓 Jupyter Notebook: https://github.com/Priyankanaskar/ml_regression_priyankanaskar/blob/main/Data/regression_priyanka.ipynb

📝 Peer Review: [peer_review.md](https://github.com/Priyankanaskar/ml_regression_priyankanaskar/blob/main/peer_review.md)

🙌 Acknowledgments
Dataset by Kaggle: Medical Cost Personal Dataset