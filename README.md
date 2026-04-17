# 🧠 Diabetes Prediction System

A web-based machine learning application that predicts whether a person is diabetic or non-diabetic based on medical input data. This project combines **Machine Learning** with a **Flask web application** to provide real-time predictions through a simple and user-friendly interface.

---

## 📌 Overview

The Diabetes Prediction System uses a trained **Logistic Regression model** to analyze medical features such as glucose level, BMI, age, and more. Users can input their data through a web form and instantly receive a prediction.

This project demonstrates how ML models can be deployed into real-world applications using web technologies.

---

## 🎯 Features

* 🔍 Predicts diabetes risk in real-time
* 🌐 Web-based interface using Flask
* 📊 Uses trained machine learning model
* 💡 Simple and responsive UI (Bootstrap)
* ⚡ Lightweight and fast performance

---

## 🛠️ Tech Stack

* **Programming Language:** Python 3.8
* **Framework:** Flask
* **Machine Learning:** Scikit-learn
* **Libraries:** Pandas, Joblib
* **Frontend:** HTML, CSS, Bootstrap
* **IDE:** PyCharm / Jupyter Notebook

---

## 📂 Dataset

* **Dataset:** PIMA Indian Diabetes Dataset

* **Features:**

  * Pregnancies
  * Glucose
  * Blood Pressure
  * Skin Thickness
  * Insulin
  * BMI
  * Diabetes Pedigree Function
  * Age

* **Target:**

  * `1` → Diabetic
  * `0` → Non-Diabetic

---

## 🤖 Model Details

* **Algorithm Used:** Logistic Regression
* **Accuracy:** ~78%

### Training Steps:

1. Data cleaning and preprocessing
2. Handling missing values
3. Feature scaling
4. Train-test split (80/20)
5. Model training and evaluation

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/diabetes-prediction-system.git
cd diabetes-prediction-system
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python app.py
```

### 4. Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🚀 How It Works

1. User enters medical data in the form
2. Data is sent to the Flask backend
3. Model processes the input
4. Prediction result is displayed

---

## 📸 Screenshots

### 🏠 Home Page

<img width="964" height="556" alt="image" src="https://github.com/user-attachments/assets/127f699e-e7cc-4430-a841-6562a34fdee7" />
<img width="959" height="196" alt="image" src="https://github.com/user-attachments/assets/ca3eb60e-6587-4e6a-886b-40946c3a7346" />


### 📊 Result Page

<img width="950" height="539" alt="image" src="https://github.com/user-attachments/assets/42162bd1-f500-4f39-adec-5c353d6be476" />


---

## ⚠️ Challenges Faced

* Flask not running properly in Jupyter Notebook
* Model integration issues
* Input validation problems

### ✅ Solutions

* Used PyCharm for Flask development
* Ensured correct preprocessing and feature alignment
* Implemented proper input handling in backend

---

## 📈 Future Improvements

* Improve model accuracy using advanced algorithms
* Add user authentication system
* Deploy on cloud (Heroku / AWS)
* Enhance UI/UX design

---

## 📌 Conclusion

This project highlights how machine learning can be integrated into web applications to solve real-world problems. It provides a simple yet effective tool for preliminary diabetes risk assessment.

---

## 👩‍💻 Author

**Sadia Eman Abdul Ghafoor**
BS Data Science

---

## 📜 License

This project is for educational purposes.
