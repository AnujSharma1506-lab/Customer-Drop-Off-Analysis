# Customer Drop-Off Analysis

This project is a **Machine Learning–based Customer Churn Prediction Web App** built using **Python and Streamlit**.  
It predicts whether a customer is likely to **churn (Yes/No)** based on key input features.

---

## 🚀 Features
- Interactive **Streamlit web interface**
- Predicts customer churn in real-time
- Uses a **trained ML model**
- Input validation with sliders and dropdowns
- Scales input data using a pre-trained scaler

---

## 🧠 Machine Learning Model
- Model trained on customer churn dataset
- Uses the following features:
  - Age
  - Gender
  - Tenure
  - Monthly Charges
- Data preprocessing done using **StandardScaler**
- Model and scaler saved using **joblib**

---

## 🛠️ Tech Stack
- Python
- Streamlit
- NumPy
- Scikit-learn
- Pandas
- Joblib

## 📂 Project Structure
├── app.py # Streamlit web app
├── main.ipynb # Model training & experimentation
├── customer_churn_data.csv # Dataset
├── model.pkl # Trained ML model
├── scaler.pkl # Scaler for preprocessing
└── README.md # Project documentation


## ▶️ How to Run the Project

### 1️⃣ Clone the repository
   git clone <repository-url>
   cd customer-churn-prediction


### 2️⃣ Install required libraries
  pip install streamlit numpy scikit-learn pandas joblib


### 3️⃣ Run the Streamlit app
   streamlit run app.py


## 🧪 How It Works
1. User enters customer details:
   - Age
   - Gender
   - Tenure
   - Monthly Charge
2. Inputs are scaled using the saved scaler
3. Model predicts churn:
   - **Yes** → Customer likely to leave
   - **No** → Customer likely to stay

---

## 📊 Output
- Displays **Churn Prediction (Yes / No)**
- Visual feedback using Streamlit animations

---

## 📌 Future Improvements
- Add more features for better accuracy
- Improve UI design
- Deploy on cloud (Streamlit Cloud / AWS)
- Add model performance metrics
