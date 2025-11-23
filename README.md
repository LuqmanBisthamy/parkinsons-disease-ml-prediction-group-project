# 🧠 Parkinson’s Disease Prediction – Machine Learning Group Project  

This repository contains a complete machine learning workflow for predicting **Parkinson’s Disease** using biomedical voice measurements.  
The project includes data cleaning, exploratory data analysis, feature scaling, model training, cross-validation, and algorithm performance comparison.

---

## 🧠 Project Overview (Professional Summary)
This project applies machine learning to classify whether a person has Parkinson’s Disease using voice-related biomarkers.

Traditional diagnosis is slow and subjective.  
Using ML, we aim to improve **early detection accuracy**, streamline clinical decision-making, and compare multiple algorithms to identify the best model.

---

## 📌 Project Highlights
- 🔍 Comparative analysis of:
  - **Logistic Regression**
  - **Support Vector Machine (SVM)**
  - **Naive Bayes**
  - **Gradient Boosting**
  - **XGBoost**
- 📊 Evaluation metrics:
  - Accuracy  
  - Precision, Recall, F1-score  
  - Confusion Matrix  
  - ROC Curve & AUC  
- ⚙️ Machine learning workflow:
  - Data preprocessing  
  - Feature scaling  
  - Train-test split  
  - Cross-validation  
  - Hyperparameter tuning  

---

## 🧬 Dataset Summary
Source: **Parkinson’s Disease Dataset - Kaggle**  
https://www.kaggle.com/code/muhammadfaizan65/parkinsons-disease-analysis/input

Dataset details:
- **195 samples**
- **22 biomedical voice features**
- **Target:** `status` (1 = Parkinson’s, 0 = Healthy)

Key voice features include:
- MDVP: Fo(Hz), Jitter(%), Shimmer, NHR  
- Amplitude & frequency variation  
- Known biomarkers linked to early Parkinson’s detection  

*(Dataset is not included in the repo — link only.)*

---

## 🔧 ML Workflow Summary
### **1️⃣ Data Cleaning**
- Removed missing values  
- Standardized numerical features  
- Checked distributions & correlations  

### **2️⃣ Feature Engineering**
- Feature scaling  
- Identification of strongest predictors  

### **3️⃣ Model Training**
Algorithms trained:
- Logistic Regression  
- Naive Bayes  
- SVM (linear & RBF kernel)  
- Gradient Boosting  
- XGBoost  

### **4️⃣ Evaluation**
Metrics used:
- Accuracy  
- Precision, Recall, F1-score  
- AUC  
- Confusion Matrix  

---

## 🏆 Model Performance (Summary)
| Model | Performance Summary |
|-------|---------------------|
| Logistic Regression | Good baseline, interpretable |
| Naive Bayes | Fast but weaker accuracy |
| SVM | Strong results with correct kernel |
| Gradient Boosting | High accuracy & robust |
| **XGBoost** | ⭐ Best overall performance |

**XGBoost achieved the highest test accuracy and AUC**, making it the most reliable classifier for this dataset.

---

## 📈 Model Comparison (Inside Notebook)
You will find:
- Metric comparison tables  
- Confusion matrices  
- ROC curves  
- Best model selection  

👉 Full implementation is inside:  
**`ML_Group_Project.ipynb`**

---

## 📂 Repository Contents
| File | Description |
|------|-------------|
| `ML_Group_Project.ipynb` | Full Jupyter Notebook for analysis, modeling, and evaluation |

---

## 🚀 How to Run
```bash
jupyter notebook ML_Group_Project.ipynb
```

---
👨‍💻 My Contribution
- Conducted data preprocessing & feature scaling
- Trained SVM and XGBoost models
- Performed cross-validation & hyperparameter tuning
- Produced evaluation metrics and visualizations
- Summarized model comparison findings
