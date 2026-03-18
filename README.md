 Customer Score Prediction using Machine Learning & Deep Learning

 📌 Project Overview

This project focuses on predicting the **customer score (S)** using multiple Machine Learning and Deep Learning models.
It compares traditional models like **Random Forest** and **CatBoost** with deep learning models such as **LSTM** and **GRU**.

The goal is to identify the best-performing model based on evaluation metrics.



## 🚀 Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* CatBoost
* TensorFlow / Keras

---

## 📂 Dataset

* File: `finalproject.xlsx`
* Contains customer transaction and behavioral data
* Target Variable: **S (Customer Score)**

### Features include:

* Purchase-related attributes
* Customer behavior data
* Transaction details

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Removed non-numeric columns:

  * CustomerID
  * PartName
  * Brand
  * TransactionTime
* Split dataset into training and testing sets
* Applied feature scaling using **StandardScaler**

---

### 2️⃣ Models Used

#### 🌳 Random Forest

* Ensemble learning method
* Handles non-linear relationships effectively

#### ⚡ CatBoost

* Gradient boosting algorithm
* Performs well on structured/tabular data

#### 🧠 LSTM (Long Short-Term Memory)

* Deep learning model for sequential data
* Captures long-term dependencies

#### 🔄 GRU (Gated Recurrent Unit)

* Simplified version of LSTM
* Faster training with comparable performance

---

### 3️⃣ Evaluation Metrics

Models are evaluated using:

* **MSE (Mean Squared Error)**
* **MAE (Mean Absolute Error)**
* **RMSE (Root Mean Squared Error)**
* **R² Score (Coefficient of Determination)**

---

## 📈 Results

The performance of all models is displayed in a comparison table and visualized using graphs:

* Line Graph (Error comparison)
* Bar Chart (Model comparison)
* Scatter Plot (Prediction accuracy)
* Actual vs Predicted plot

---

## 📊 Visualizations Included

* 📉 Model Error Comparison
* 📊 Feature Importance (Random Forest)
* 📈 Actual vs Predicted Values
* 🔵 Scatter Plot for Prediction Accuracy

---

## ▶️ How to Run the Project

### Step 1: Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn catboost tensorflow openpyxl
```

### Step 2: Upload Dataset

Place `finalproject.xlsx` in the project directory.

### Step 3: Run the Script

```bash
python main.py
```

---

## 📁 Project Structure

```
├── finalproject.xlsx
├── main.py
├── README.md
```

---

## 🎯 Key Highlights

* Comparison of ML vs DL models
* Clean preprocessing pipeline
* Multiple performance metrics
* Easy-to-understand visualizations

---

## 🔮 Future Enhancements

* Add more advanced models (XGBoost, BiLSTM)
* Hyperparameter tuning
* Deploy as a web application
* Use real-time data

