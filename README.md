# 🩺 Chronic Kidney Disease Prediction

This project aims to **predict Chronic Kidney Disease (CKD)** using machine learning techniques.  
It applies multiple classification algorithms to medical diagnostic data to identify whether a patient is likely to have CKD.  
By analyzing patterns in the dataset, the project supports **early diagnosis and preventive healthcare** through data-driven insights.

---

## 📊 Project Overview

Chronic Kidney Disease is a serious condition where the kidneys gradually lose their ability to filter waste from the blood.  
Early detection is crucial for preventing severe complications.  
This project uses **machine learning models** to predict CKD based on patient data such as age, blood pressure, blood sugar, and other lab test results.

The workflow includes:
1. **Data preprocessing** – handling missing values, encoding categorical data, and normalizing features.  
2. **Exploratory Data Analysis (EDA)** – generating correlation heatmaps and visualizing feature relationships.  
3. **Model training & evaluation** – comparing several algorithms on performance metrics.  
4. **Result interpretation** – identifying the most accurate model for CKD prediction.

---

## 🧠 Machine Learning Models Used

The following models were trained and evaluated:

- **Naive Bayes (GaussianNB)**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**
- **Decision Tree Classifier**
- **Support Vector Machine (SVM)**

---

## ⚙️ Tools and Libraries

| Category | Tools Used |
|-----------|-------------|
| **Programming Language** | Python |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn |
| **Development Environment** | Jupyter Notebook |

---

## 📈 Model Results

| Model | Accuracy | Recall | F1 Score | Key Observations |
|--------|-----------|---------|-----------|------------------|
| **Naive Bayes (GaussianNB)** | 0.95 | 0.92 | 0.96 | Performs well with simple assumptions; quick and interpretable. |
| **K-Nearest Neighbors (KNN, k=8)** | 0.76 | 0.71 | 0.79 | Moderate performance; sensitive to scaling and data distribution. |
| **Random Forest Classifier** | 🥇 **0.98** | **1.00** | **0.98** | Best accuracy and recall; highly robust and reliable. |
| **Decision Tree Classifier** | 0.96 | 0.97 | 0.97 | Strong performance; slightly prone to overfitting. |
| **Support Vector Machine (Linear Kernel)** | 0.96 | 0.98 | 0.97 | Excellent recall; works well for high-dimensional data. |

---

## 🔍 Summary of Findings

- **Random Forest Classifier** delivered the highest accuracy (**98%**) and perfect recall (**100%**), making it the most effective model for CKD prediction.  
- **SVM** and **Decision Tree** also produced strong results, confirming the dataset’s predictive reliability.  
- The model results emphasize the **potential of machine learning in medical diagnostics** — providing accurate predictions that could assist healthcare professionals in early detection of Chronic Kidney Disease.

---

## 📚 Future Improvements

- Incorporate **deep learning models** for improved accuracy.  
- Deploy the trained model as a **web application** for clinical use.  
- Add **explainability techniques** (e.g., SHAP, LIME) to interpret model decisions.

---

## 🧑‍💻 Author

**Project by:** Chittesh S  
Machine Learning & Data Science Enthusiast  

---

## 🏁 Conclusion

This project demonstrates how **data preprocessing, EDA, and ML modeling** can be combined to create an accurate and interpretable **Chronic Kidney Disease prediction system**.  
The results highlight the effectiveness of ensemble learning methods, particularly **Random Forest**, in identifying CKD patients with high precision.

---
