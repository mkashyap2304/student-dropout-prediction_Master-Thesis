# 🎓 Student Dropout Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting student outcomes (Dropout, Enrolled, Graduate) using machine learning techniques. Early prediction of at-risk students enables educational institutions to take preventive measures and improve academic success rates.

---

## 🎯 Business Problem
Student dropout is a major challenge in higher education. Identifying students at risk early can help institutions:
- Improve retention rates
- Optimize resource allocation
- Provide targeted academic support

---

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Dataset: Predict Students' Dropout and Academic Success
- Records: 4,424 students
- Features: 36 (demographics, academic performance, socio-economic factors)
- Target Classes:
  - Graduate
  - Dropout
  - Enrolled

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Missing value handling (Median & Mode)
- One-Hot Encoding for categorical variables
- Feature scaling using StandardScaler

### 2. Data Splitting
- Train: 70%
- Validation: 15%
- Test: 15%
- Stratified sampling used

### 3. Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting
- Neural Network (MLP)

### 4. Evaluation Metrics
- Accuracy
- Precision (Macro)
- Recall (Macro)
- F1 Score (Macro)
- ROC-AUC

---

## 📈 Key Results

- Models achieved strong predictive performance across all classes
- Ensemble models (Random Forest, Gradient Boosting) performed best
- Neural Network captured complex relationships in data

---

## 🔍 Key Insights

- Academic performance (semester grades & approvals) is the strongest predictor
- Financial factors (tuition fees status) impact dropout risk
- Demographic features have moderate influence
- Class imbalance handled effectively using weighted models

---

## 📊 Visualizations
- Target distribution
- Correlation heatmap
- ROC curves
- Confusion matrices
- Feature importance plots

---

## 💡 Business Impact

This model can help:
- Universities identify at-risk students early
- Improve retention strategies
- Enable personalized academic support
- Reduce dropout rates significantly

---

## ⚠️ Limitations
- Dataset limited to one institution
- Class imbalance (more graduates than dropouts)
- Real-world deployment requires continuous data updates

---

## 🚀 Future Improvements
- Deploy as real-time prediction system
- Use advanced models (XGBoost, Deep Learning)
- Integrate behavioral and attendance data
- Build student risk dashboard

---

## 📌 Conclusion
Machine learning can effectively predict student outcomes and provide actionable insights. This project demonstrates how data-driven approaches can improve educational outcomes and reduce dropout rates.

---

## 📂 Project Structure
