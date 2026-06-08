# Bank Customer Churn Prediction using ANN

A deep learning web application that predicts whether a bank customer is likely to churn using an **Artificial Neural Network (ANN)** built with **TensorFlow/Keras** and deployed using **Streamlit**.

## Project Overview

Customer churn is an important problem for banks because retaining existing customers is often more cost-effective than acquiring new ones. This project uses customer banking data to predict whether a customer will leave the bank based on features such as credit score, geography, gender, age, balance, salary, and activity status.

## Features

* Predicts bank customer churn probability
* Uses an Artificial Neural Network for classification
* Streamlit web app for real-time prediction
* Data preprocessing with Label Encoding, One-Hot Encoding, and Standard Scaling
* Saved trained model and preprocessing objects for easy deployment

## Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Streamlit
* Jupyter Notebook

## Project Structure

```text
Bank-Customer-Churn-Prediction-ANN/
│
├── app.py
├── Churn_Modelling.csv
├── experiments.ipynb
├── hyperparametertuningann.ipynb
├── prediction.ipynb
├── model.h5
├── scaler.pkl
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
└── README.md
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Hritik827/Bank-Customer-Churn-Prediction-ANN.git
```

### 2. Go to the project folder

```bash
cd Bank-Customer-Churn-Prediction-ANN
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit app

```bash
streamlit run app.py
```

## Model Workflow

1. Load the customer churn dataset
2. Preprocess categorical and numerical features
3. Encode gender and geography columns
4. Scale numerical features using StandardScaler
5. Train an ANN model using TensorFlow/Keras
6. Save the trained model and preprocessing objects
7. Deploy the model using Streamlit

## Output

The application predicts whether a customer is likely to churn and displays the churn probability.

## Author

**Hritik Patil**
