# Lakshmilavanyasaladi-Opticrop-Smart-Agriculture-Production-Optimization-Engine
# opti-crop
# 🌱 Smart Agricultural Production Optimization Engine (OptiCrop)

## 📖 Project Overview

The **Smart Agricultural Production Optimization Engine (OptiCrop)** is a Machine Learning-based web application developed to help farmers identify the most suitable crop based on soil nutrients and environmental conditions. The system analyzes important agricultural parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, soil pH, and rainfall to recommend the best crop for maximum productivity.

The project aims to improve agricultural decision-making by providing intelligent, data-driven crop recommendations that enhance crop yield, optimize resource utilization, and support sustainable farming practices.

---

## 🎯 Objectives

- Recommend the most suitable crop based on soil and climate conditions.
- Improve agricultural productivity using Machine Learning.
- Assist farmers in making informed cultivation decisions.
- Promote sustainable and efficient farming practices.

---

## ✨ Features

- 🌾 Crop recommendation based on soil nutrients and environmental parameters.
- 📊 Machine Learning-based prediction using Scikit-learn.
- 🌐 User-friendly web interface developed with Flask.
- ✅ Input validation for all agricultural parameters.
- ⚡ Real-time crop prediction.
- 📱 Responsive and easy-to-use interface.

---

## 📋 Input Parameters

The application accepts the following inputs:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- Soil pH
- Rainfall (mm)

---

## 📤 Output

The application predicts and displays the **most suitable crop** for the given soil and climatic conditions.

**Example Output:**

```
Recommended Crop: Rice
```

---

## 🛠 Technologies Used

### Programming Language

- Python 3

### Machine Learning

- Scikit-learn
- NumPy
- Pandas
- SciPy

### Data Visualization

- Matplotlib
- Seaborn

### Web Framework

- Flask

### Frontend

- HTML5
- CSS3
- JavaScript

### Model Serialization

- Joblib

---

## 📂MY Project Structure

```
OptiCrop/
│
├── app.py
├── requirements.txt
├── README.md
│
├── data/
│   └── Crop_Recommendation.csv
│
├── models/
│   ├── crop_model.joblib
│   ├── scaler.joblib
│   └── train.py
│
├── templates/
│   └── index.html
│
├── static/
│   ├── style.css
│   └── script.js
│
└── notebook.ipynb
```

---

## ⚙ Installation

### Clone the Repository
https://github.com/LakshmiLavanyasaladi
### Navigate to the Project Folder

```bash
cd OptiCrop
```

### Installing Required Libraries

```bash
pip install -r requirements.txt
## ▶ Running the Application

Start the Flask server:

```bash
python app.py
```
## 🧪 How It Works

1. The user enters soil and environmental parameters.
2. The application validates the input values.
3. The data is standardized using the trained scaler.
4. The Machine Learning model predicts the most suitable crop.
5. The predicted crop is displayed on the screen.

---


### Prediction Result

"C:\Users\admin\OneDrive\Pictures\crop-recommendation-system.jpeg"

## 🚀 Future Enhancements

- Fertilizer recommendation system
- Weather API integration
- Farmer login and registration
- Prediction history using a database
- Interactive dashboard with charts
- Crop information and cultivation guidelines
- Deployment to cloud platforms

---

## 👩‍💻 Author

**Lavanya Saladi**

B.Tech Student

---

## 📄 License

This project is developed for educational and academic purposes.
