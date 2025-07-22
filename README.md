# 🫀 Predicting Heart Disease using Machine Learning

This project attempts to build a machine learning model capable of predicting whether a patient has heart disease based on a range of medical features. The model is developed using Python and several data science and machine learning libraries.

---

## 🧠 Problem Statement

Cardiovascular diseases are among the leading causes of death worldwide. Early diagnosis can help in timely treatment and prevention. This project leverages patient data to build a predictive model to assist in early detection of heart disease.

---

## 📊 Technologies & Libraries Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 📁 Dataset

The dataset used is the **Cleveland Heart Disease dataset**, available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

### 🔑 Key Features:
- Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps)
- Cholesterol (chol), Fasting Blood Sugar (fbs), Resting ECG (restecg)
- Max Heart Rate (thalach), Exercise-Induced Angina (exang)
- ST Depression (oldpeak), Slope, Number of Major Vessels (ca), Thalassemia (thal)
- **Target:** Presence (1) or Absence (0) of heart disease

---

## 🧪 Approach

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Histograms, pair plots, box plots

3. **Model Building**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Random Forest Classifier
   - Support Vector Machines (SVM)

4. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-Score
   - ROC-AUC Curve

---

## ✅ Results

- **Best Model:** Random Forest Classifier  
- **Accuracy:** `92%`  
- **ROC-AUC Score:** `0.94`

---

## ▶️ Run the Notebook

