# 🚗 Car Price Prediction – Full Stack Machine Learning Application

A production-ready Full Stack Machine Learning application that predicts used car prices using a trained **Random Forest Regressor**, served via **FastAPI** backend and consumed through a **Streamlit frontend UI**.

---

## 🚀 Project Overview

This application predicts the selling price of used cars based on features such as:

- Brand
- Year
- Kilometers Driven
- Fuel Type
- Transmission
- Owner Type
- Engine & Power

The project demonstrates:

✔ End-to-End ML Pipeline  
✔ Model Training & Serialization  
✔ REST API Development  
✔ Frontend + Backend Integration  
✔ Production-Ready Architecture  

---

## 🧠 Architecture
Streamlit Frontend  →  FastAPI Backend  →  Random Forest Model (.pkl)
(User Input)            (REST API)           (Scikit-Learn)
---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| Backend API | FastAPI |
| Frontend UI | Streamlit |
| Machine Learning | Random Forest Regressor |
| ML Library | Scikit-Learn |
| Data Processing | Pandas, NumPy |
| Model Serialization | Joblib |
| Validation | Pydantic |
| Language | Python |

---

## 📂 Project Structure
Car-Price-Prediction-Full-Stack/
│
├── main.py                     # FastAPI application
├── model.py                    # Model loading & prediction logic
├── schema.py                   # Pydantic validation schema
├── streamlit_app.py            # Streamlit frontend
├── train.py                    # Model training pipeline
│
├── random_forest_model.pkl     # Trained ML model
├── feature_columns.pkl         # Feature alignment reference
├── cardekho_data.csv           # Dataset
│
├── requirements.txt
├── runtime.txt
└── README.md

## 🧠 Machine Learning Pipeline

1. Data Cleaning
2. Feature Engineering
3. One-Hot Encoding
4. Train/Test Split
5. Random Forest Model Training
6. Model Serialization using Joblib
7. API Deployment with FastAPI
8. UI Integration using Streamlit

---

## ⚡ How to Run Locally

1️⃣ Clone Repository


git clone https://github.com/prerit-18/Car-Price-Prediction-Full-Stack.git

cd Car-Price-Prediction-Full-Stack

2️⃣ Create Virtual Environment

python3 -m venv .venv

source .venv/bin/activate   # Mac/Linux

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run FastAPI Backend
uvicorn main:app --reload

Backend will run at:
http://127.0.0.1:8000

5️⃣ Run Streamlit Frontend
Open a new terminal and run:
streamlit run streamlit_app.py

Frontend will run at:
http://localhost:8501 bash

## 🎯 Key Highlights

✔ Clean REST API architecture
✔ Structured Pydantic validation
✔ Feature column alignment for safe inference
✔ Serialized ML model for fast predictions
✔ Separate training script
✔ Full-stack integration
✔ Deployment ready

⸻

## 🌍 Deployment Ready

This project can be deployed on:
		•   Render
		•	Railway
		•	Streamlit Cloud
		•	Docker
		•	AWS / GCP / Azure

⸻

## 📈 Future Improvements
	• 	Add model evaluation metrics (R², MAE, RMSE)
	•	Add Docker containerization
	•	Add CI/CD pipeline
	•	Add model versioning
	•	Add logging & monitoring
	•	Deploy live demo

⸻

## 👨‍💻 Author

Prerit
Machine Learning & Backend Developer

Building intelligent, production-ready systems using AI + Backend engineering.
