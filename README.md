# 🧠 Diabetes Prediction using ANN

## 🚀 Project Overview

This project builds a high-performance Artificial Neural Network (ANN) model to predict whether a patient has diabetes based on medical attributes.

It combines deep learning with advanced exploratory data analysis (EDA) to uncover patterns and deliver strong predictive accuracy.

---

## 📊 Features

* High-level Exploratory Data Analysis (EDA)
* Data visualization (Seaborn + Plotly 3D)
* Feature engineering (encoding + scaling)
* Deep Learning model using ANN
* Performance evaluation (Accuracy, Confusion Matrix, Classification Report)
* Training vs Validation analysis

---

## 🧾 Dataset

The dataset contains medical and demographic information such as:

* Age
* BMI
* HbA1c Level
* Blood Glucose Level
* Hypertension
* Heart Disease
* Smoking History

Target Variable:

* `diabetes` → 0 (No), 1 (Yes)

---

## 🔍 Exploratory Data Analysis

The following visualizations are used:

* Histogram with KDE (Age Distribution)
* Countplot (Diabetes Distribution)
* Scatter Plot (Age vs BMI)
* Correlation Heatmap
* Pairplot (Feature Relationships)
* 3D Scatter Plot (Interactive)

---

## 🧠 Model Architecture

* Input Layer
* Dense Layer (128 neurons, ReLU)
* Dropout Layer (0.3)
* Dense Layer (64 neurons, ReLU)
* Dropout Layer (0.3)
* Dense Layer (32 neurons, ReLU)
* Output Layer (Sigmoid)

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Seaborn, Matplotlib, Plotly
* Scikit-learn
* TensorFlow / Keras

---

## 📈 Model Performance

* Accuracy: ~95% - 98% (depending on training)

Additional Metrics:

* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📉 Training Insights

* Accuracy vs Validation Accuracy Graph
* Loss vs Validation Loss Graph

These help identify overfitting or underfitting.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/diabetes-ann-project.git
cd diabetes-ann-project
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the script

```bash
python main.py
```

---

## 📌 Future Improvements

* Hyperparameter tuning (Keras Tuner)
* ROC-AUC Curve analysis
* Model comparison (ANN vs XGBoost)
* Deployment using Streamlit

---

## 🌟 Project Highlights

* Combines deep learning with rich EDA
* Includes interactive visualization
* Strong accuracy with clean pipeline
* Portfolio-ready ML project

---

## 📎 Connect with Me

If you found this useful, feel free to connect and share feedback!

---

## ⭐ Give a Star

If you like this project, consider giving it a ⭐ on GitHub!
