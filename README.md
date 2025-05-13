# ❤️ Heart Disease Prediction using Machine Learning

This project focuses on predicting the presence of heart disease using various machine learning algorithms. It involves a complete ML pipeline — from data cleaning and preprocessing to model evaluation and deployment. The final model is saved and ready for integration into applications.

---

## 📂 Project Structure

- `model.ipynb`: Serialized version of the best-performing model (Logistic Regression)
- `Heart_Disease_Algos.ipynb`: Implements multiple ML models and compares results
- `model.pkl`: Saved model

---

## 📊 Dataset

- **Source**: [Cleveland Heart Disease Dataset]
- The dataset consists of patient medical records with the goal of predicting the presence of heart disease.

### 🧬 Feature Description:

| Feature       | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `sex`         | Gender of the patient (1 = male; 0 = female)                                |
| `trestbps`    | Resting blood pressure (in mm Hg)                                           |
| `chol`        | Serum cholesterol in mg/dl                                                  |
| `fbs`         | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)                       |
| `restecg`     | Resting electrocardiographic results (0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hypertrophy) |
| `thalach`     | Maximum heart rate achieved                                                 |
| `exang`       | Exercise-induced angina (1 = yes; 0 = no)                                   |
| `oldpeak`     | ST depression induced by exercise relative to rest                          |
| `slope`       | The slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping) |
| `ca`          | Number of major vessels (0–3) colored by fluoroscopy                        |
| `thal`        | Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)            |
| `HeartDisease`| Target variable (1 = presence of heart disease, 0 = absence)                |

---

## 🧼 Data Preprocessing

- Handled missing values and outliers
- Converted categorical features using one-hot encoding
- Standardized numerical features
- Split data into training and testing sets

---

## 🤖 Machine Learning Models Used

Implemented and evaluated the following ML algorithms:

- **Logistic Regression** ✅ (Best Accuracy: **0.82**)
- Decision Trees
- Random Forests

### Techniques Applied:
- Feature Standardization using `StandardScaler`
- Hyperparameter Tuning using `GridSearchCV`

---

## ✅ Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

---

## 💾 Model Deployment

- Final Logistic Regression model saved as a `.pkl` file using `joblib`
- Ready for integration into a web or mobile application

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🚀 Future Work

- Deploy model using Flask or Streamlit
- Develop a web-based health diagnostic interface
- Expand model using additional datasets for better generalization

---
