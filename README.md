# 🧠 ASD Prediction System (Hybrid Machine Learning Model)

## 📌 Project Objective

The objective of this project is to develop an intelligent system for the **early prediction of Autism Spectrum Disorder (ASD)** using machine learning techniques.
The system combines multiple models with a **rule-based approach** to improve prediction accuracy and provide reliable risk assessment (Low, Moderate, High).

---

## 📊 Dataset Used

* The dataset used is a **synthetic dataset of 30,000 records** containing:

  * Behavioral features (A1–A10 questionnaire)
  * Demographic details (Age, Gender, Family History, Jaundice)
* Target variable:

  * **ASD Traits (Yes/No)**
* Data preprocessing steps applied:

  * Removal of duplicates
  * Handling missing values (Median Imputation)
  * Encoding categorical variables
  * Feature scaling (StandardScaler)
  * Feature selection (Top 20 features using SelectKBest)

---

## 🛠️ Tools & Technologies

### 💻 Programming Language

* Python

### 📚 Libraries Used

* Pandas & NumPy → Data handling
* Scikit-learn → Preprocessing, model evaluation
* XGBoost → Advanced boosting model
* TensorFlow (Keras) → Artificial Neural Network (ANN)
* Matplotlib → Data visualization
* Joblib → Model saving/loading
* Gradio → User interface deployment

---

## 🤖 Machine Learning Models

* XGBoost Classifier
* Random Forest Classifier
* Artificial Neural Network (ANN)

👉 A **hybrid approach** is used:

* Combines ML model predictions
* Integrates rule-based scoring (A1–A10 responses)

---

## 📈 Results

* The system successfully predicts ASD risk using multiple models.

* Performance evaluated using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score

* Outputs include:

  * 📊 Model comparison graph
  * 📉 ROC Curve
  * 📊 Confusion Matrix
  * 📉 ANN Loss Curve

* Final prediction is categorized into:

  * 🟢 Low Risk
  * 🟡 Moderate Risk
  * 🔴 High Risk

---

## 🌐 Deployment

* A **Gradio-based web interface** is developed
* Allows users to:

  * Input personal & behavioral data
  * Get real-time ASD risk prediction
  * View results in a simple dashboard

---

## 🚀 Conclusion

This project demonstrates how **machine learning combined with rule-based logic** can be used to build an effective and user-friendly ASD screening tool, enabling **early detection and better healthcare support**.

---
