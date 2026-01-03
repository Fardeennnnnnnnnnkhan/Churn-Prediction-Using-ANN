# 📉 Customer Churn Prediction Using Artificial Neural Network (ANN)
https://churn-prediction-by-fardeen.streamlit.app/
An end-to-end **Machine Learning project** that predicts the **probability of customer churn** using an **Artificial Neural Network (ANN)** and deploys the model as an interactive **Streamlit web application**.

This project focuses on **probability-based prediction**, which is far more useful in real-world business scenarios than simple yes/no classification.

---

## 🚀 Project Overview

Customer churn occurs when customers stop using a company’s service.  
Predicting churn in advance helps businesses take preventive actions such as:

- Personalized offers  
- Customer retention campaigns  
- Improved customer support  

Instead of predicting only *Churn* or *No Churn*, this project predicts a **churn probability**, enabling smarter, data-driven decisions.

---

## 🎯 Objectives

- Predict customer churn probability using historical data  
- Perform proper feature engineering and preprocessing  
- Train an ANN for binary classification  
- Deploy the trained model using Streamlit  
- Provide an easy-to-use web interface for predictions  

---

## 🧠 Machine Learning Details

- **Model Type**: Artificial Neural Network (ANN)  
- **Problem Type**: Binary Classification  
- **Output**: Churn Probability (range: 0 to 1)  
- **Activation Function**: Sigmoid  

---

## 🗂️ Dataset Features

| Feature | Description |
|------|------------|
| CreditScore | Customer credit score |
| Gender | Male / Female |
| Age | Customer age |
| Tenure | Number of years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of products used |
| HasCrCard | Credit card ownership |
| IsActiveMember | Active customer status |
| EstimatedSalary | Estimated salary |
| Geography_France | Customer from France |
| Geography_Germany | Customer from Germany |
| Geography_Spain | Customer from Spain |

⚠️ Identifier columns like `CustomerId` and `RowNumber` were removed to avoid data leakage.

---

## ⚙️ Tech Stack

- **Language**: Python  
- **Libraries**: NumPy, Pandas, Scikit-learn, TensorFlow / Keras, Streamlit  
- **Model Storage**: `.h5`, `.pkl`  
- **Version Control**: Git & GitHub  

---

## 🔧 Data Preprocessing

- Label Encoding for `Gender`  
- One-Hot Encoding for `Geography`  
- Feature Scaling using `StandardScaler`  
- Removal of non-informative ID columns  
- Train-test split  

---

## 🧠 ANN Architecture

- Input Layer (12 features)  
- Hidden Layer 1 (ReLU)  
- Hidden Layer 2 (ReLU)  
- Output Layer (Sigmoid)  

---

## 📊 Model Output Interpretation

Example:
```
Churn Probability: 0.33
```

- **< 0.30** → Low risk  
- **0.30 – 0.60** → Medium risk  
- **> 0.60** → High risk  

---

## 🌐 Streamlit Web Application

Run locally:
```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
ANN_Project_Implementation/
│
├── app.py
├── model.h5
├── scaler.pkl
├── label_encoder_gender.pkl
├── one_hot_encoder_geo.pkl
├── requirements.txt
├── README.md
└── notebooks/
```

---

## 🛠️ Installation

```bash
git clone https://github.com/Fardeennnnnnnnnnkhan/Churn-Prediction-Using-ANN.git
cd Churn-Prediction-Using-ANN
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

---

## 🎤 Interview Explanation

> “I built an end-to-end customer churn prediction system using an ANN that outputs churn probability instead of a binary label. The model is deployed using Streamlit for real-time predictions.”

---

## 👨‍💻 Author

**Fardeen Khan**  
GitHub: https://github.com/Fardeennnnnnnnnnkhan  

⭐ If you find this project useful, consider giving it a star!
