# 📊 Predictive Modeling for Life Insurance Cross-Selling

A machine learning project focused on identifying health insurance policyholders who are most likely to buy vehicle insurance. The goal is to assist insurance companies in increasing cross-sell conversions using data-driven strategies.

---

## 🎯 Objective

To build a predictive model that helps insurance companies identify existing health insurance customers who are likely to purchase vehicle insurance, improving marketing targeting and cross-sell efficiency.

---

## 📌 Key Features

- 🧼 **Data Cleaning & Preprocessing**
- 📊 **Exploratory Data Analysis (EDA)** to understand key trends
- 🤖 Applied multiple **ML models**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- ⚖️ **Handled class imbalance** using SMOTE
- 📈 **Evaluated model performance** with accuracy, precision, recall, F1-score, ROC-AUC

---

## 📁 Dataset

The dataset contains anonymized customer features such as:
- Age, region, vehicle damage status
- Previously insured status
- Annual premium
- Policy sales channel, etc.

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (for SMOTE)

---

## 📉 Problem Type

**Binary Classification**  
Target: `Response`  
> 1 → Will buy vehicle insurance  
> 0 → Will not buy

---

## 🧠 EDA Highlights

- Customers with damaged vehicles and no previous insurance are more likely to buy.
- Certain age groups and sales channels show higher conversion.
- Premium ranges help segment potential buyers.

---

## 🧪 Model Evaluation (Example)

| Model              | Accuracy | ROC-AUC | F1 Score |
|-------------------|----------|---------|----------|
| Logistic Regression | 87.2%    | 0.79    | 0.73     |
| Decision Tree       | 89.0%    | 0.82    | 0.76     |
| Random Forest       | 91.3%    | 0.86    | 0.81     |
| Gradient Boosting   | **92.1%** | **0.89** | **0.83** |

> Final model: **Gradient Boosting Classifier**

---

---

## 🌟 Impact

This model can help insurers:
- Identify high-potential customers
- Run targeted campaigns
- Improve cross-sell conversion rates

---

## 🧑‍💻 Team

Built as a collaborative project by a team of student data science.  
Focus: Real-world application, teamwork, and ML pipeline execution.

---

## 📜 License

# ⚠️ Usage Notice

This project is for educational and portfolio purposes only.  
If you wish to use, modify, or distribute any part of this code, please contact me first at [your email or LinkedIn].


---

## 🚀 Future Enhancements

- Build a Flask web app interface
- Add SHAP/LIME for interpretability
- Include automated report generation
