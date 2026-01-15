# 💳 Online Transaction Fraud Detection

## 📌 Overview
This project focuses on **detecting fraudulent online transactions** using **Machine Learning classification techniques**.  
It analyzes transaction patterns such as amount, balance changes, and transaction types to identify **fraudulent behavior**.

This project reflects **real-world banking and digital payment fraud detection systems**.

---

## 📊 Dataset Information
- 📁 **Dataset:** Online Transaction Dataset  
- 🏷 **Problem Type:** Binary Classification  
- 🎯 **Target Variable:** `isFraud`
  - `0` → Legitimate Transaction  
  - `1` → Fraudulent Transaction  

### 🔢 Features Used
- `type` – Transaction type (TRANSFER, CASH_IN, PAYMENT, etc.)
- `amount` – Transaction amount
- `oldbalanceOrg` – Sender balance before transaction
- `newbalanceOrig` – Sender balance after transaction
- `oldbalanceDest` – Receiver balance before transaction
- `newbalanceDest` – Receiver balance after transaction

---

## 🧠 Machine Learning Approach
### 🔹 Classification Model
- Supervised Learning
- Binary Classification
- Fraud detection based on abnormal transaction behavior

### 🔍 Key Concepts
- Feature Engineering
- Data Cleaning
- Class Imbalance Handling
- Model Evaluation

---

## 🛠 Tech Stack
- 🐍 Python  
- 📊 NumPy  
- 🗂 Pandas  
- 📈 Matplotlib  
- 🎨 Seaborn  
- 🤖 Scikit-learn  

---

## ⚙️ Project Workflow
1. 📥 Import required libraries  
2. 📂 Load transaction dataset  
3. 🧹 Clean and preprocess data  
4. 🔍 Perform Exploratory Data Analysis (EDA)  
5. ✂️ Split data into training and testing sets  
6. 🧠 Train classification model  
7. 📏 Evaluate model performance  
8. 📊 Visualize fraud patterns  

---

## 📈 Results & Insights
- ✅ Successfully detects fraudulent transactions  
- 📉 Fraud cases are rare but high-impact  
- 📊 Visualization highlights abnormal patterns  
- 🔍 Feature analysis improves detection accuracy  

---

## ▶️ How to Run the Project
1. 🔽 Clone the repository  
2. 📓 Open `Online_transaction_fraud_detection.ipynb`  
3. ▶️ Run all cells sequentially  
4. 📊 Review predictions and evaluation metrics  

---

## 🚀 Future Enhancements
- ⚡ Apply Random Forest & XGBoost  
- 🔁 Handle class imbalance using SMOTE  
- 🌐 Deploy using Streamlit  
- 📡 Real-time fraud detection simulation  

---

## 👤 Author

<img src="https://avatars.githubusercontent.com/Nandan0402" width="120" style="border-radius:50%;" />

**Nandan**  
📌 AI & Machine Learning Enthusiast  

🔗 **GitHub:** https://github.com/Nandan0402  
🔗 **LinkedIn:** https://www.linkedin.com/in/nandan0402  

---

⭐ *If you find this project useful, consider giving it a star!*
