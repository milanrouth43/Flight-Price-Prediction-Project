# ✈️ Flight Price Prediction System

A full-stack Machine Learning web application that predicts flight ticket prices based on user travel details. The application uses a trained Scikit-learn regression model served through a Flask REST API with a modern React (Vite) frontend for an interactive user experience.

> 🚀 **Live Demo:** https://flight-price-prediction-project-xi.vercel.app/

---

## 📌 Project Overview

Flight ticket prices vary based on multiple factors such as airline, source, destination, departure time, arrival time, travel class, number of stops, and booking date.

This project leverages Machine Learning to estimate flight prices using historical flight data. Users can enter travel details through a responsive web interface and instantly receive a predicted ticket price.

---

## ✨ Features

- Predict flight ticket prices instantly
- Responsive React user interface
- Flask REST API backend
- Machine Learning prediction model
- Real-time prediction based on user inputs
- Clean and user-friendly design
- Live deployment using Vercel

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Vite
- HTML5
- CSS3
- JavaScript

## Backend

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy

## Machine Learning

- Data Preprocessing
- Feature Engineering
- Regression Model
- Model Serialization (Pickle)

## Deployment

- Vercel
- GitHub

---

# 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Model Serialization (`model.pkl`)
7. Flask API Integration
8. React Frontend Integration
9. Live Deployment

---

# 🏗️ Project Architecture

```
                     User

                       │

                       ▼

             React Frontend (Vite)

                       │

                REST API Request

                       │

                       ▼

               Flask Backend (Python)

                       │

                       ▼

          Trained Machine Learning Model

                       │

                       ▼

            Predicted Flight Price

                       │

                       ▼

              Displayed to the User
```

---

# 📂 Project Structure

```
Flight-Price-Prediction-Project
│
├── client
│   ├── public
│   ├── src
│   ├── package.json
│   └── vite.config.js
│
├── server
│   ├── app.py
│   ├── model.pkl
│   ├── flight.csv
│   ├── Flight Price Prediction Using Python.ipynb
│   └── requirements.txt
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/milanrouth43/Flight-Price-Prediction-Project.git
```

## Frontend

```bash
cd client

npm install

npm run dev
```

## Backend

```bash
cd server

pip install -r requirements.txt

python app.py
```

---

# 🚀 API Endpoint

### POST `/predict`

The backend accepts the following inputs:

- Airline
- Source City
- Destination City
- Departure Time
- Arrival Time
- Number of Stops
- Travel Class
- Days Left Before Departure

The API returns the predicted flight ticket price.

---

# 📈 Model Inputs

The prediction model considers the following parameters:

- Airline
- Source City
- Destination City
- Departure Time
- Arrival Time
- Stops
- Travel Class
- Days Left

---

# 📷 Screenshots

## Home Page

> Add a screenshot here

---

## Prediction Result

> Add a screenshot here

---

# 🔮 Future Improvements

- User Authentication
- Flight Price Trend Analysis
- Interactive Charts
- Docker Containerization
- CI/CD Pipeline using GitHub Actions/Jenkins
- AWS Cloud Deployment
- Model Performance Dashboard

---

# 👨‍💻 Author

**Milan Routh**

📧 Email: milanrouth43@gmail.com

🔗 LinkedIn: https://linkedin.com/in/milanrouth43

💻 GitHub: https://github.com/milanrouth43

🌐 Live Demo: https://flight-price-prediction-project-xi.vercel.app/

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Thank you for visiting!
