# Insurance Premium Prediction

## 📌 Project Description

The **Insurance Premium Prediction** project is a machine learning–based system designed to estimate the **health insurance premium** of an individual based on their personal, lifestyle, and medical attributes.

The goal of this project is to analyze how factors such as age, income, BMI category, smoking habits, employment status, medical history, and insurance plan influence the final insurance cost.

This project demonstrates a complete **end-to-end ML workflow**, including data preprocessing, feature engineering, model training, and prediction.

---

## 🧠 Problem Statement

Insurance companies need an accurate way to estimate premiums based on customer risk profiles.  
Manual estimation can be inconsistent and biased.

This project solves that problem by:
- Using historical insurance data
- Learning patterns between customer attributes and premium amounts
- Providing consistent and data-driven predictions

---

## 🧩 Key Features Considered

The model uses the following types of input features:

- **Demographic Information**
  - Age
  - Gender
  - Region
  - Marital status
  - Number of dependents

- **Health & Lifestyle Factors**
  - BMI category
  - Smoking status
  - Medical history
  - Genetic risk

- **Financial & Employment Details**
  - Income level
  - Employment status
  - Selected insurance plan

These features are preprocessed and encoded before being passed to the trained model.

---

## ⚙️ Model & Approach

- Categorical variables are handled using **encoding techniques**
- Numerical features are scaled using a **feature scaler**
- A supervised machine learning model is trained on processed data
- The trained model predicts the insurance premium based on input features

Pre-trained model and preprocessing artifacts are stored and reused for prediction.

---

## 🎯 Use Case

This project can be used for:
- Educational purposes (learning ML pipelines)
- Insurance cost estimation prototypes
- Integration into web applications (e.g., Streamlit)
- Demonstrating real-world regression problems

---

## 📁 Project Structure Overview

- **Model artifacts**: Stored separately for reuse
- **Prediction logic**: Isolated from training code
- **Modular design**: Makes the project easy to extend and integrate

---

## 👨‍💻 Author

**Aniruddha Moharir**  
Engineering Student  
Machine Learning & Data Science Enthusiast
