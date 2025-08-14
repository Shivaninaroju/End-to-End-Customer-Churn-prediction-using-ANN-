# 🧠 Customer Churn Prediction using ANN

## 📌 Problem Statement
Customer churn refers to the loss of customers in a business. This project aims to predict whether a customer will leave the bank based on various features like credit score, age, tenure, balance, etc. Accurately predicting churn can help businesses retain customers and improve service quality.

## 📊 Dataset Info
The dataset consists of 10,000 entries with the following features:

Numerical: CreditScore, Age, Tenure, Balance, EstimatedSalary, EstimatedSalary, NumOfProducts, HasCrCard,  etc.

Categorical: Geography (OneHotEncoded), Gender (LabelEncoded)

Target: Exited (1 if customer left the bank, 0 otherwise)


## 🔧 Tech Stack Used
TensorFlow/Keras for building the ANN

Pandas / NumPy / Scikit-learn for data preprocessing

Streamlit for creating an interactive web UI

Matplotlib for data visualization

LabelEncoder & OneHotEncoder with .pkl files saved for real-time input transformation


## 📦 How to Use the Web App
Open the link: https://end-to-end-ann-classification-jwixyyg3xw9ozeadksvoto.streamlit.app/

Enter customer details like Credit Score, Age, Geography, Balance, etc.

Click Predict.

The app will display whether the customer is likely to exit or stay.


## 🛠 For Local Setup (Optional)

git clone https://github.com/Shiva-Prasad-Naroju/End-to-End-Customer-Churn-prediction-using-ANN.git

cd End-to-End-Customer-Churn-prediction-using-ANN

pip install -r requirements.txt

streamlit run app.py


## ✅ Key Features
Real-time prediction of customer churn

Fully interactive Streamlit app

Clean and modular code

Model input transformation using saved encoders


## 📁 Repository Structure

📦End-to-End-Customer-Churn-Prediction-using-ANN

 ┣ 📜app.py                     # Streamlit app
 
 ┣ 📜model.h5                   # Trained ANN model
 
 ┣ 📜label_encoder_gender1.pkl  # Label encoder for gender
 
 ┣ 📜onehot_encoder_geo.pkl     # OHE for geography
 
 ┣ 📜scaler.pkl                 # Feature scaler
 
 ┣ 📜requirements.txt           # Dependencies
 
 ┣ 📜README.md                  # Project documentation
 
 ┗ 📜Churn_Modelling.csv        # Dataset


## 🧪 Model Building (ANN)

🚀 Used TensorFlow Keras Sequential API

### 🧠 Architecture:

📥 Input layer: normalized numerical features

🔁 Hidden layers: 2 Dense layers with ReLU 🔥

📤 Output layer: Sigmoid ➡️ Binary Classification ✅❌

### ⚙️ Compiled with:

🧪 Optimizer: adam

   Loss: binary_crossentropy

📊 Metrics: accuracy 🎯

## 📩 Contact
📧 Shiva Prasad Naroju - shivanaroju26@gmail.com
