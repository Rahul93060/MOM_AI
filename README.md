🤰 MOM AI – Maternal Health Risk Prediction Platform
📌 Overview

MOM AI is an AI-powered maternal health risk prediction platform designed to help detect high-risk pregnancies at an early stage. The system analyzes important maternal health parameters such as age, blood pressure, blood sugar level, body temperature, and heart rate to predict the risk level of pregnancy using a machine learning model.

The platform helps healthcare professionals quickly assess whether a pregnancy falls under Low Risk, Medium Risk, or High Risk, allowing early medical intervention and better maternal care monitoring.

🚨 Problem Statement

Maternal health complications remain a significant global challenge, particularly in rural or resource-limited areas where early detection of high-risk pregnancies is difficult. Conditions such as preeclampsia, gestational diabetes, and hypertension often go unnoticed until they become severe.

There is a need for intelligent systems that can analyze maternal health data and provide early risk prediction to support healthcare professionals in making better decisions.

💡 Solution

MOM AI uses a Machine Learning model to analyze maternal health parameters and predict pregnancy risk levels. The system provides an easy-to-use web interface where healthcare workers or doctors can enter patient data and instantly receive risk predictions.

The platform also stores patient records, allowing healthcare providers to monitor maternal health data over time.

✨ Key Features

🤖 AI-based maternal health risk prediction

📝 Patient data entry through a web interface

⚠️ Risk classification (Low, Mid, High)

🗂 Patient record storage and management

🧑‍⚕️ Doctor dashboard for viewing patient records

🔗 REST API for prediction access

🎨 Risk level visualization using color indicators

🛠 Technology Stack
🔹 Backend

🐍 Python

🌐 Django Framework

🔹 Machine Learning

📊 Scikit-learn

🐼 Pandas

🔢 NumPy

🔹 Frontend

🌍 HTML

🎨 CSS

🅱️ Bootstrap

🔹 Database

💾 SQLite (via Django ORM)

🔹 APIs

🔌 Django REST API for prediction endpoint

🔹 Future Enhancements

📈 Chart.js for risk trend visualization

📩 SMS alert system for high-risk pregnancies

🧠 Explainable AI insights for prediction reasoning

🏗 Project Architecture

User Input → Django Backend → Machine Learning Model → Risk Prediction → Database Storage → Result Display

1️⃣ User enters maternal health data.
2️⃣ Django backend processes the request.
3️⃣ The trained ML model predicts the risk level.
4️⃣ The prediction is displayed to the user.
5️⃣ Patient data and prediction results are stored in the database.

⚙️ How It Works

1️⃣ User enters maternal health details in the web form.
2️⃣ The data is sent to the backend server.
3️⃣ The trained machine learning model processes the input.
4️⃣ The model predicts the maternal health risk level.
5️⃣ The result is displayed and saved for future monitoring.
