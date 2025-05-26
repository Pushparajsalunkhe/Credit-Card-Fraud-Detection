# Credit-Card-Fraud-Detection
### 🎯 **Project Goal**
Build a machine learning model to detect fraudulent credit card transactions from a dataset.
---
## 🔹 Step 1: **Define the Problem**

* **Objective**: Classify transactions as fraudulent or legitimate.
* **Type of Problem**: Binary classification.
  ---
## 🔹 Step 2: **Collect & Understand the Data**

* Use a dataset like the **Kaggle Credit Card Fraud Detection** dataset:

    * [Kaggle dataset link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* Data features:

  * **Time**, **Amount**, **V1–V28** (PCA components), **Class** (0 = normal, 1 = fraud)

---

## 🔹 Step 3: **Data Preprocessing**

* **Handle Imbalanced Data**:

  * Fraud cases are often <1% of the data.
  * Use techniques like:

    * **Under-sampling**
    * **Over-sampling (SMOTE)**
    * **Class weights**
* **Data Cleaning**:

  * Check for missing values
* **Feature Scaling**:

  * Scale `Amount` and `Time` using **StandardScaler** or **MinMaxScaler**
* **Train-Test Split**:

  * Use `train_test_split` from `sklearn.model_selection`

---

## 🔹 Step 4: **Exploratory Data Analysis (EDA)**

  * Fraud vs. Non-Fraud distribution
  * Amount distribution in fraud cases
  
* Use libraries:

  *  `pandas` 'numpy'

---

## 🔹 Step 5: **Model Selection**

Try multiple models:

* **Logistic Regression**
* **Random Forest**
* **Gaussian Distribution**
* **Support Vector Machine**

---
## 🔹 Step 6: **Model Training**

* Fit models using training data.
---

## 🔹 Step 9: **Uses Streamlit 

*Open-source python framework
*Transform python scripts into interactive web apps




