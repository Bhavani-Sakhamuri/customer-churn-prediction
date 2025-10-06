# 📊 Customer Churn Prediction

### 👩‍💻 Author: Bhavani Sakhamuri  
📧 [bhavani.sakhamuri@gmail.com](mailto:bhavani.sakhamuri@gmail.com)  
📍 Bengaluru, India  
🌐 [GitHub Profile](https://github.com/Bhavani-Sakhamuri)

---

## 🎯 Objective
This project predicts whether a telecom customer will **churn (leave the company)** based on their usage patterns and demographic information.

It demonstrates a **complete Machine Learning workflow** — from data cleaning and preprocessing to model training, evaluation, and visualization.

---

## 🧠 Project Workflow
1. **Data Loading** – Automatically downloads the dataset using KaggleHub.  
2. **Data Cleaning** – Handles missing values and type conversions.  
3. **Feature Encoding & Scaling** – Prepares categorical and numerical data.  
4. **Model Training** – Uses a Random Forest Classifier.  
5. **Evaluation** – Accuracy, classification report, and confusion matrix.  
6. **Feature Importance** – Finds key factors influencing churn.

---

## 🧰 Tech Stack
- **Python 3.x**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **KaggleHub** (for automatic dataset download)

---

## 📊 Dataset
**Source:** [Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
**Records:** 7,043 customers  
**Features:** Customer demographics, services subscribed, and billing information.

---

## 📈 Results
- Achieved **~80–85% accuracy** using Random Forest.  
- **Top features influencing churn:**
  - MonthlyCharges  
  - Contract Type  
  - Tenure  

---

## 📷 Visualizations

#### 🔹 Confusion Matrix
Shows how well the model classifies churned vs non-churned customers.
![Confusion Matrix](images/confusion_matrix.png)

#### 🔹 Feature Importance
Top 10 features that most influence churn prediction.
![Feature Importance](images/feature_importance.png)

---

## ⚙️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Bhavani-Sakhamuri/customer-churn-prediction.git
cd customer-churn-prediction


### Install Dependencies

pip install -r requirements.txt


#### Run the Notebook

jupyter notebook customer_churn_prediction.ipynb


### Project structure

customer-churn-prediction/
│
├── customer_churn_prediction.ipynb      # Main Jupyter notebook
├── requirements.txt                     # Libraries used
├── README.md                            # Project documentation
└── images/
    ├── confusion_matrix.png
    └── feature_importance.png


