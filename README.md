# 🏠 Home Price Prediction Project

## 📌 Overview

This project is a **Machine Learning + Web Application** that predicts house prices based on user inputs like location, BHK, bathrooms, and area.

It combines:

* Data preprocessing
* Model building
* API development
* Frontend UI

---

## ⚙️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* Flask (API)
* HTML, CSS, JavaScript (Frontend)

---

## 🔍 Features

* Data cleaning (handled null values)
* Outlier detection and removal
* Data visualization using scatter plots
* Multiple ML models:

  * Linear Regression
  * Decision Tree
* Model optimization using:

  * Cross Validation
  * Grid Search
* Final model saved using:

  * Pickle file (`.pkl`)
  * JSON file (for locations)

---

## 🧠 Model Building Steps

1. Loaded dataset using Pandas
2. Cleaned data (handled missing/null values)
3. Removed outliers for better accuracy
4. Performed data visualization (scatter plots)
5. Trained models:

   * Linear Regression
   * Decision Tree
6. Applied:

   * Cross Validation
   * Grid Search for best parameters
7. Saved final model using Pickle

---

## 🔌 API Endpoints (Flask)

### 1. Get Locations

**GET** `/get_location_names`

Returns list of available locations.

---

### 2. Predict Home Price

**POST** `/predict_home_price`

#### Input:

* location
* sqft
* bhk
* bath

#### Output:

* Predicted price

---

## 💻 Frontend

* Built using HTML, CSS, JavaScript
* User enters details in form
* Sends request to Flask API
* Displays predicted price

---

## 📁 Project Structure

```
Flask_projects/
│
├── Client/        # Frontend (HTML, CSS, JS)
├── Model/         # ML model and datasets
├── Server/        # Flask API
├── columns.json   # Location data
├── model.pkl      # Trained model
```

---

## ▶️ How to Run

### 1. Install dependencies

```
pip install -r requirements.txt
```

### 2. Run Flask server

```
python server.py
```

### 3. Open frontend

Open `app.html` in browser

---

## 📊 Future Improvements

* Add more ML models
* Improve UI/UX
* Deploy project online
* Add authentication


