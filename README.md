# ❤️ Heart Disease Prediction System

A Machine Learning-based web application that predicts the likelihood of heart disease using patient health parameters. The system uses a Random Forest Classifier trained on healthcare data and provides real-time predictions through a simple web interface.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help patients seek timely medical attention. This project leverages Machine Learning to analyze patient health information and predict the risk of heart disease.

The application is built using Python, Flask, Scikit-Learn, Pandas, and NumPy.

---

## 🚀 Features

✅ Predicts heart disease risk based on medical attributes

✅ User-friendly web interface

✅ Machine Learning model using Random Forest Algorithm

✅ Fast and accurate predictions

✅ Data preprocessing using StandardScaler

✅ Flask-based deployment

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap

### Backend
- Python
- Flask

### Machine Learning
- Scikit-Learn
- Random Forest Classifier

### Libraries
- Pandas
- NumPy
- Joblib

---

## 📊 Input Parameters

The prediction is based on the following parameters:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- Oldpeak
- Slope
- Number of Major Vessels (CA)
- Thalassemia (Thal)

---

## 📂 Project Structure

```text
Heart-Disease-Prediction/
│
├── app.py
├── train_model.py
├── heart.csv
├── requirements.txt
├── model.pkl
├── scaler.pkl
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   └── images/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd Heart-Disease-Prediction
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Train the Model

```bash
python train_model.py
```

### 5️⃣ Run the Application

```bash
python app.py
```

### 6️⃣ Open in Browser

```text
http://127.0.0.1:5000
```

---

## 🔄 Working Flow

1. User enters health details.
2. Data is preprocessed using StandardScaler.
3. Trained Random Forest model receives input.
4. Model predicts heart disease risk.
5. Result is displayed on the webpage.

---

## 🎯 Future Enhancements

- Add user authentication
- Store prediction history
- Improve model accuracy
- Generate downloadable health reports
- Deploy on cloud platforms
- Add AI-powered recommendations

---

## 📚 Learning Outcomes

- Machine Learning Fundamentals
- Data Preprocessing
- Classification Algorithms
- Flask Web Development
- Model Deployment
- Healthcare Data Analytics

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit and push
5. Create a Pull Request
## 👩‍💻 Author

**Priyanka Deshnur**

Aspiring Full Stack Java Developer | Machine Learning Enthusiast

## ⭐ Support

If you found this project useful, please give it a ⭐ on GitHub and share your feedback.
