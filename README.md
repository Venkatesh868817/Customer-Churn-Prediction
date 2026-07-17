# 📊 Customer Churn Prediction using Machine Learning

A Machine Learning project that predicts whether a telecom customer is likely to **Churn**, **Stay**, or **Join** based on customer demographics, subscription details, service usage, and account information.

---

## 📌 Problem Definition

The **Customer Churn** dataset contains information about **7,043 telecom customers** from a California-based telecommunications company.

Each record represents a single customer and includes information about:

- 👤 Customer Demographics
- 📍 Location
- 📅 Tenure
- 📱 Phone Services
- 🌐 Internet Services
- 💳 Payment Method
- 📜 Contract Type
- 💰 Monthly Charges
- 💵 Total Charges
- 📊 Customer Status (Joined, Stayed, Churned)

The objective of this project is to build a Machine Learning model capable of accurately predicting customer churn so businesses can improve customer retention strategies.

<br>

---

# 🚀 Project Workflow

```
Data Collection
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Handling
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Encoding & Scaling
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Customer Churn Prediction
```

---

# 📷 Project Screenshots

## 📊 Dataset Overview

<img src="assets/1.png" width="900">

---

## 📈 Exploratory Data Analysis

<img src="assets/2.png" width="900">

<img src="assets/3.png" width="900">

---

## 🤖 Model Evaluation

<img src="assets/4.png" width="900">

---

## 📌 Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| IDE | Jupyter Notebook |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn, XGBoost |

---

# 🤖 Machine Learning Models

The following models were trained and evaluated:

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **78.28%** |
| Decision Tree | **77.29%** |
| Random Forest | **78.11%** |
| Gaussian Naive Bayes | **36.77%** |
| XGBoost Classifier | **80.86%** ⭐ |

---

# 📊 Model Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

---

# 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── Customer_Churn.csv
├── Zip_Code_Population.csv
├── README.md
├── requirements.txt
│
├── assets/
│   ├── dataset.png
│   ├── eda1.png
│   ├── eda2.png
│   └── model.png
│
└── models/
```

---

# 📈 Exploratory Data Analysis

The following analysis was performed:

- Distribution of Customer Status
- Gender Analysis
- Contract Type Analysis
- Monthly Charges Distribution
- Total Charges Distribution
- Correlation Heatmap
- Churn by Internet Service
- Churn by Payment Method
- Tenure Distribution
- Feature Importance

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Venkatesh868817/Customer-Churn-Prediction.git
```

Move into the project folder

```bash
cd Customer-Churn-Prediction
```

Install required libraries

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 🎯 Applications

Customer churn prediction helps businesses identify customers who are likely to leave.

Using this prediction, companies can:

- 📞 Contact high-risk customers
- 🎁 Offer personalized discounts
- 💬 Improve customer support
- 📈 Increase customer retention
- 💰 Reduce revenue loss

---

# 📊 Results

✅ Successfully cleaned and preprocessed customer data.

✅ Performed comprehensive Exploratory Data Analysis (EDA).

✅ Trained multiple Machine Learning models.

✅ Compared model performances.

✅ XGBoost achieved the highest accuracy of **80.86%**.

---

# 🔮 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Selection
- Model Deployment using Streamlit
- Flask/FastAPI API
- Docker Deployment
- Cloud Deployment (AWS)

---

# 📦 Requirements

```
Python 3.10+

numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
jupyter
```

Install them using

```bash
pip install -r requirements.txt
```

---

# 👨‍💻 Author

### **Sangem Venkatesh**

🎓 B.Tech Computer Science & Engineering

💼 Aspiring Data Analyst | Machine Learning Enthusiast

---

## 🌐 Connect with Me

<p align="left">
<a href="https://github.com/Venkatesh868817">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github">
</a>

<a href="https://www.linkedin.com/in/sangem-venkatesh-7ba284301/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin">
</a>

<a href="mailto:sangemvenkatesh203@gmail.com">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
</a>
</p>

---

# ⭐ Show your support

If you found this project useful,

⭐ Star this repository

🍴 Fork this repository

📢 Share it with others

---

## 📄 License

This project is licensed under the **MIT License**.
