# XAI-Diabetes-Prediction 🚀

**Predict Diabetes with Transparency: Stacking Ensemble + LIME for Explainable AI**  

---

## 🌟 Project Overview

This project leverages **Explainable Artificial Intelligence (XAI)** to predict diabetes using the **Pima Indians Diabetes Dataset**.  

We combine **high-accuracy ensemble learning** with **interpretability**:  

- **Stacking Classifier**: KNN, SVM, XGBoost as base learners with Random Forest as the meta-model.  
- **Data Balancing**: SMOTE + ENN for handling imbalanced classes.  
- **Anomaly Detection**: One-Class SVM for removing outliers.  
- **Explainability**: LIME provides interpretable explanations for each prediction.  

> The workflow ensures that predictions are **accurate, robust, and explainable**, which is crucial for healthcare applications.  

---

## ⚡ Key Features

- **Stacking Ensemble**: Combines multiple models for better performance  
- **Data Cleaning**: Handles missing values and anomalies effectively  
- **Balanced Training**: SMOTE + ENN ensures fair learning on imbalanced data  
- **Interpretability**: LIME explains individual predictions feature-wise  
- **Reproducible Workflow**: Complete Python notebook ready for experimentation  

---

## 📊 Dataset

- **Source:** [Pima Indians Diabetes Dataset] 
- **Features:**  
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
- **Target:** Outcome (0 = No Diabetes, 1 = Diabetes)  

> The dataset contains missing values, outliers, and class imbalance — making it ideal to showcase **XAI techniques**.

---

## References

Pima Indians Diabetes Dataset
(https://www.researchgate.net/publication/384220180_Explainable_Artificial_Intelligence_for_Prediction_of_Diabetes_using_Stacking_Classifier)

---

## 🛠 Installation

```bash
# Clone this repository
git clone https://github.com/fatimasood/XAI-Diabetes-Prediction.git
cd XAI-Diabetes-Prediction

# Install dependencies
pip install -r requirements.txt



