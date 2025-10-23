# 🌸 Iris Flower Classification App

A **Machine Learning web app** built with **Python**, **scikit-learn**, and **Streamlit** to predict the species of an Iris flower — *Setosa*, *Versicolor*, or *Virginica* — using its sepal and petal dimensions.

This project demonstrates the **complete ML lifecycle** — from model training and saving, to interactive deployment using Streamlit.



## 🧭 Overview

The **Iris Flower Classification App** is a complete end-to-end **machine learning project** that predicts the species of an Iris flower — *Setosa*, *Versicolor*, or *Virginica* — based on its **sepal** and **petal** measurements.


## 🎯 Goal of the Project

The main goals of this project are to:

- ✅ Understand and implement a **basic machine learning workflow** — from model training to deployment.  
- ✅ Build an **interactive web application** using **Streamlit** to make real-time predictions.  
- ✅ Learn how to **save, load, and use trained ML models** in a production-like environment.  

This project helped me understand the real-world flow of deploying ML models into web applications.


## ✨ Features

- 🧠 **ML-Powered Predictions:** Classifies Iris flowers into one of three species.  
- 💻 **Interactive Interface:** Built with Streamlit for clean and simple user input.  
- ⚡ **Real-Time Output:** Instant prediction once measurements are entered.  
- 💾 **Reusable Model:** The model is saved as `iris_model.pkl` for easy reuse.  
- 🔍 **Lightweight Deployment:** Runs locally with minimal dependencies.  

---

## 🧰 Tech Stack

| Category | Tools / Libraries |
|-----------|-------------------|
| Programming | Python 3.9+ |
| ML Framework | scikit-learn |
| Data Handling | pandas, numpy |
| Model Serialization | pickle |
| Web Framework | Streamlit |

---

## 🔄 Project Workflow

1. **Data Loading** → Imported the Iris dataset from `sklearn.datasets`.  
2. **Preprocessing** → Split data into training and testing sets.  
3. **Model Training** → Used a `RandomForestClassifier` for prediction.  
4. **Model Saving** → Stored the trained model using the `pickle` library.  
5. **Web App Development** → Built a user interface using Streamlit.  
6. **Prediction** → The app predicts flower species based on user input.

---

## 💻 How to Run Locally

## 1.Clone the Repository
```bash
git clone https://github.com/pavani mudireddy/iris-flower-classification.git
cd iris-flower-classification
```
## 2.Install Dependencies
- pip install -r requirements.txt
- If you don’t have requirements.txt, create one with:
- streamlit
- pandas
- numpy
- scikit-learn
- 
## 3.Run the Streamlit App
streamlit run iris_app.py

## 📊 Output

When you enter the sepal and petal dimensions, the app will display a prediction such as:
The predicted flower species is Setosa

## 📸 Preview
![App Screenshot](screenshot.png)

## 🧩 Project Structure
.
├── train_model.py         # Script to train and save the ML model
├── ML_API.py              # Trained model file (Pickle)
├── App.py                 # Streamlit web application
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

## 🎓 Key Learnings

- How to use scikit-learn to train classification models

- How to serialize ML models with pickle

- How to build interactive web apps using Streamlit

- Basics of end-to-end ML deployment on a local machine

- Understanding Random Forest Classifier and feature importance
- 
## 🔗 Useful Links

- Project Link:
  https://github.com/pavanimudireddy/iris_prediction
- LinkedIn:
  www.linkedin.com/in/pavani-mudireddy

## 🚀 Future Improvements

✅ Add flower image display for each predicted species

✅ Show model accuracy, confusion matrix, and metrics

🔲 Include feature importance visualization

🔲 Deploy the app on Streamlit Cloud or Hugging Face Spaces

🔲 Add an option to upload CSV files for batch predictions

  
