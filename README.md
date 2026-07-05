# 📊 Customer Churn Prediction using Machine Learning

Predicting customer churn is one of the most important business problems in the telecom industry. This project builds and compares multiple machine learning models to predict whether a customer is likely to leave a telecom service based on customer demographics, subscription details, and billing information.

---

## 🚀 Project Overview

Customer retention is significantly more cost-effective than acquiring new customers. This project applies machine learning techniques to identify customers who are at risk of churning, enabling businesses to take proactive retention measures.

The complete pipeline includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Handling Missing Values
- Label Encoding
- Handling Class Imbalance using SMOTE
- Model Training
- Cross Validation
- Model Evaluation
- Model Serialization

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information including:

- Customer demographics
- Account information
- Internet services
- Phone services
- Contract type
- Payment method
- Monthly charges
- Total charges
- Customer tenure

**Target Variable**

- Churn
  - Yes
  - No

---

## 🛠 Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost |
| Handling Imbalanced Data | SMOTE (Imbalanced-learn) |
| Model Serialization | Pickle |

---

## 📊 Exploratory Data Analysis

The project includes:

- Distribution of numerical features
- Distribution of categorical features
- Correlation heatmap
- Histograms
- Boxplots
- Customer churn distribution

These visualizations help understand customer behavior and feature relationships before model training.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Converted TotalCharges to numeric values
- Handled missing values
- Label Encoding for categorical variables
- Train-Test Split
- SMOTE Oversampling for balancing the dataset

---

## 🤖 Machine Learning Models

The following algorithms were trained and compared:

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

Each model was evaluated using **5-Fold Cross Validation**.

---

## 📈 Evaluation Metrics

Model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Cross Validation Accuracy

---

## 📁 Project Structure

```
Customer_Churn_Prediction/
│
├── customer_churn_prediction.py
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── encoders.pkl
├── README.md
└── requirements.txt
```

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Customer_Churn_Prediction.git
```

Move into the project folder

```bash
cd Customer_Churn_Prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

```bash
python customer_churn_prediction.py
```

---

## 💡 Project Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Encoding
   │
   ▼
Train-Test Split
   │
   ▼
SMOTE Oversampling
   │
   ▼
Model Training
   │
   ▼
Cross Validation
   │
   ▼
Model Evaluation
   │
   ▼
Save Encoders
```

---

## 📌 Key Highlights

- End-to-End Machine Learning Pipeline
- Clean and Modular Python Code
- Multiple ML Algorithms Compared
- Class Imbalance Handling using SMOTE
- Cross Validation for Reliable Performance
- Ready for Deployment

---

## 🔮 Future Improvements

- Hyperparameter Optimization
- Streamlit Web Application
- Flask/FastAPI REST API
- Docker Containerization
- Model Deployment on Cloud
- Feature Importance Dashboard
- Real-time Customer Churn Prediction

---

## 👨‍💻 Author

**Sanjay Saravanan**

Machine Learning | Data Science | Artificial Intelligence

---

⭐ If you found this project useful, consider giving it a star!
