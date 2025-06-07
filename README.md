# Bank-Marketing-ML-Project
Developed a supervised ML pipeline to predict term deposit subscriptions using bank marketing data. Performed data preprocessing, outlier handling, EDA, and feature engineering. Trained and evaluated models (Decision Tree, Logistic Regression, Naive Bayes) using ROC-AUC, F1-score, and confusion matrix.

This project applies supervised machine learning to predict whether a customer will subscribe to a term deposit using a real-world bank marketing dataset. Originally implemented using RapidMiner, the workflow has been recreated in Python for version control, learning, and sharing purposes.

---

## 🧰 Tools & Technologies
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- RapidMiner (original project)
- GitHub

---

## 📂 Project Structure
- `bank 2.csv` – Original dataset
- `Bank_Marketing_Project_Report.pdf` – Final project report with visuals and business insights
- `Bank_Marketing_ML_Project.ipynb` – Python notebook with full ML pipeline
- `README.md` – Project summary and instructions

---

## ⚙️ Machine Learning Pipeline
- Data Cleaning (handling 'unknown' values)
- Label Encoding for categorical variables
- Feature Scaling (StandardScaler)
- Train-test split (70/30)
- Model Training: 
  - Logistic Regression  
  - Decision Tree  
  - Naive Bayes  
- Evaluation: Accuracy, Precision, Recall, F1-Score, ROC-AUC

---

## 📊 Model Performance Comparison

| Model               | Accuracy | Precision | Recall  | F1-Score | AUC     |
|--------------------|----------|-----------|---------|----------|---------|
| Logistic Regression| 0.782    | 0.804     | 0.721   | 0.760    | 0.873   |
| Decision Tree       | 0.769    | 0.762     | 0.755   | 0.759    | 0.769   |
| Naive Bayes         | 0.745    | 0.783     | 0.647   | 0.709    | 0.827   |

> 🚀 Logistic Regression showed the highest AUC and balanced performance, while Decision Tree achieved stronger recall.

---

## 📌 Business Insights
- Longer call durations and prior positive interactions increase the chance of deposit subscription.
- Decision Trees offer useful if-then patterns for marketing teams.
- Logistic Regression provides explainable results for stakeholder communication.

---

## 📄 Original Project Report
📎 [Bank_Marketing_Project_Report.pdf](./Bank_Marketing_Project_Report.pdf)


