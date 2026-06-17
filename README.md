# Customer Churn Prediction using Artificial Neural Networks (ANN)

## Overview

Customer churn is one of the biggest challenges faced by businesses, especially in industries such as banking, telecommunications, and subscription-based services. This project leverages Deep Learning techniques to predict whether a customer is likely to leave a company based on their demographic and behavioral information.

The model is built using an Artificial Neural Network (ANN) with TensorFlow and Keras and is deployed as an interactive web application using Streamlit, allowing users to make real-time churn predictions.

---

## Features

* Customer churn prediction using Deep Learning
* Data preprocessing and feature engineering
* Artificial Neural Network (ANN) implementation
* Interactive Streamlit web application
* Real-time prediction capability
* User-friendly interface
* Model performance evaluation using multiple metrics

---

## Tech Stack

### Programming Language

* Python

### Machine Learning & Deep Learning

* TensorFlow
* Keras
* Scikit-learn

### Data Processing

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Deployment

* Streamlit

---

## Dataset

The project uses a customer churn dataset containing features such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

Target Variable:

* Exited (0 = Customer Retained, 1 = Customer Churned)

---

## Project Workflow

### 1. Data Collection

* Load customer churn dataset.
* Analyze customer attributes and target distribution.

### 2. Data Preprocessing

* Handle categorical variables using encoding.
* Perform feature scaling and normalization.
* Split dataset into training and testing sets.

### 3. Model Building

Constructed an Artificial Neural Network consisting of:

* Input Layer
* Hidden Layers with ReLU activation
* Output Layer with Sigmoid activation

### 4. Model Training

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Evaluation Metrics: Accuracy

### 5. Model Evaluation

Performance measured using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

### 6. Deployment

* Saved trained model.
* Developed Streamlit interface.
* Enabled real-time customer churn prediction.

---

## Model Architecture

Input Layer
↓
Dense Layer (ReLU)
↓
Dense Layer (ReLU)
↓
Output Layer (Sigmoid)

The Sigmoid activation function outputs the probability of customer churn.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/customer-churn-ann.git
cd customer-churn-ann
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── data/
│   └── churn.csv
│
├── notebooks/
│   └── ANN_Training.ipynb
│
├── models/
│   └── churn_model.h5
│
├── app.py
├── requirements.txt
├── scaler.pkl
├── encoder.pkl
└── README.md
```

---

## Sample Prediction

Input:

* Credit Score: 650
* Age: 42
* Balance: 120000
* Active Member: Yes

Output:

```text
Probability of Churn: 78%
Prediction: Customer Likely to Churn
```

---

## Results

The ANN model successfully learns customer behavior patterns and predicts churn with high accuracy. The deployed Streamlit application provides a practical and interactive way for businesses to assess customer retention risks in real time.

---

## Future Improvements

* Hyperparameter tuning
* Explainable AI using SHAP
* Integration with cloud services
* Support for batch predictions
* Advanced deep learning architectures

---

## Author

**Priyansh**

GitHub: [https://github.com/yourusername](https://github.com/priyansh1409/ANN_Classification-Churn)

---

## License

This project is licensed under the MIT License.
