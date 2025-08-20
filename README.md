# FD-TASK-6-
# FD_OB_TASK-6-
# Fraud Detection System using Machine Learning

This project was developed as part of my internship at **Oasis Infobyte**. The goal is to detect fraudulent credit card transactions using machine learning models on a real-world, highly imbalanced dataset.

---

##  Dataset

- **Name**: `creditcard.csv`
- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Features**:
  - Anonymized transaction features (`V1` to `V28`)
  - `Amount` and `Time`
  - **Target**: `Class` → `0` (Legit), `1` (Fraud)

---

##  Project Objectives

- Detect and classify fraudulent transactions accurately
- Handle missing values and class imbalance
- Evaluate model performance using real-world metrics
- Visualize and interpret fraud detection results

---

##  Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data handling
- **Matplotlib**, **Seaborn** – Visualizations
- **Scikit-learn** – Machine learning models and evaluation

---

##  Workflow Summary

### 1. Data Preprocessing
- Loaded and verified the dataset
- Scaled `Amount` and `Time` columns using `StandardScaler`
- Dropped original `Amount` and `Time` to avoid redundancy

### 2. Handling Missing Values
- Used `SimpleImputer` with mean strategy to fill missing values

### 3. Model Training
- **Random Forest Classifier**
- **Logistic Regression**

### 4. Evaluation Metrics
- Accuracy Score
- Classification Report
- Confusion Matrix (Plotted via `Seaborn`)

---

##  Results & Outputs

- Built and evaluated two models for classification
- Used confusion matrices to visualize performance
- Handled NaNs in labels (`y_test`) before evaluating

---

