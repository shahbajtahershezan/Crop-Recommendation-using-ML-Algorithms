# 🌾 Crop Recommendation using Machine Learning

This project aims to build an intelligent system that recommends the most suitable crop to grow based on soil and climate parameters using various machine learning algorithms.

---

## 🧠 Project Overview

Agriculture is the backbone of many economies, and choosing the right crop based on environmental conditions is crucial for sustainable yield.  
This project leverages **supervised machine learning** to predict the optimal crop using features like:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

---

## 🧹 Data Preprocessing

1. Handled missing values and normalized the dataset.  
2. Applied **StandardScaler** for feature standardization.  
3. Used **PCA (Principal Component Analysis)** to reduce dimensionality and visualize data distribution.

---

## ⚙️ Machine Learning Models

The following models were trained and compared:

| Algorithm | Description |
|------------|--------------|
| SVM | Support Vector Machine for non-linear classification |
| Decision Tree | Simple and interpretable tree-based classifier |
| Random Forest | Ensemble method combining multiple decision trees |
| Logistic Regression | Linear model for baseline comparison |
| KNN | Distance-based classification method |
| Naive Bayes | Probabilistic approach based on Bayes' theorem |
| ANN | Artificial Neural Network for deep learning-based classification |

---

## 📊 Model Evaluation

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The **Random Forest** and **ANN** models achieved the best overall performance.

---

## 🧪 Technologies Used

- Python  
- Jupyter Notebook  
- NumPy, Pandas, Matplotlib, Seaborn  
- Scikit-learn  
- TensorFlow / Keras (for ANN)

---

## 📁 Project Structure

