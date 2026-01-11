# 🩺 Personalized Medical Assistant  
### Disease Prediction, Drug Recommendation & Appointment Management System

---

## 📌 Project Overview

**Personalized Medical Assistant** is a full-stack **Django + Machine Learning** web application designed to assist patients and doctors through an intelligent medical workflow.

The system allows patients to:
- Predict diseases based on symptoms
- Request medicines from doctors
- Book appointments with doctors

Doctors can:
- Review patient diagnoses
- Approve or manage appointments
- Recommend medicines to patients

This project uses **Machine Learning models (Logistic Regression & Decision Tree)** for disease prediction and drug recommendation.

---

## 🧠 Machine Learning Models Used

- **Logistic Regression (LR)**  
  → Disease Prediction based on symptoms

- **Decision Tree (DT)**  
  → Drug Recommendation based on disease, age, and gender

Both models are trained and integrated into the Django backend.

---

## 🧩 Features

### 👤 Patient Dashboard
- Select symptoms and predict disease
- View diagnosis results
- Request medicine from doctor
- Book appointment with doctor
- View appointment status (Pending / Approved)

### 👨‍⚕️ Doctor Dashboard
- View patient disease predictions
- Recommend medicines to patients
- Approve or schedule appointments
- View appointment details (date & time)

---

## 🛠️ Technologies Used

### Backend
- Python
- Django 4.0
- SQLite (Database)

### Machine Learning
- scikit-learn
- NumPy
- SciPy
- joblib

### Frontend
- HTML
- CSS
- Bootstrap

---

## 📦 Python Dependencies
- asgiref==3.8.1
- Django==4.0
- joblib==1.3.2
- numpy==1.26.4
- pillow==10.2.0
- scikit-learn==1.2.2
- scipy==1.12.0
- sqlparse==0.4.4
- threadpoolctl==3.4.0
- typing_extensions==4.10.0
- tzdata==2024.1

---

## 🚀 Quick Start – Run the Project

### 1️⃣ Clone the Repository

    https://github.com/Zinb-NMK/Personalized-Medical-Assistant

---

### 2️⃣ Create Virtual Environment

    python -m venv venv

---

### 3️⃣ Navigate to Project Folder

    cd system

---

### 4️⃣ Activate Virtual Environment

**Windows**

    ./venv/scripts/activate

---

### 5️⃣ Install Dependencies

    pip install -r requirements.txt

---

### 6️⃣ Run Migrations

    python manage.py makemigrations  
    python manage.py migrate

---

### 7️⃣ Start Django Server

    python manage.py runserver

---

## 🔐 Default Login Credentials

### 👤 Patient Login

    Username: patient  
    Password: patient

---

### 👨‍⚕️ Doctor Login

    Username: doctor  
    Password: doctor
---

---

## 🧠 Machine Learning Models Used

This project integrates Machine Learning models with a Django web application to provide intelligent medical assistance.

### 🔹 Logistic Regression (LR)
- Used for **Disease Prediction**
- Takes patient symptoms as input
- Predicts the most likely disease

### 🔹 Decision Tree (DT)
- Used for **Drug Recommendation**
- Uses:
  - Diagnosed disease
  - Patient age
  - Patient gender
- Predicts the recommended medicine for supported diseases

Models are trained offline and loaded into the Django backend using `joblib`.

---

## 🧑‍⚕️ Application Workflow

### 👤 Patient Flow
1. Patient logs in to the dashboard
2. Selects symptoms for disease prediction
3. Disease is predicted using Logistic Regression
4. Patient can:
   - Request medicine from doctor
   - Book an appointment
5. Patient views medicine and appointment status

### 👨‍⚕️ Doctor Flow
1. Doctor logs in to the dashboard
2. Reviews patient disease predictions
3. Approves or schedules appointments
4. Recommends medicines using Decision Tree model
5. Updates patient records

---

## ⚠️ Important Notes

- Ensure **scikit-learn version is exactly 1.2.2**
- Anaconda is recommended for environment consistency
- This project is intended **only for educational purposes**
- Not suitable for real-world medical diagnosis

---

## 📌 Disclaimer

⚠️ This system is developed strictly for **academic and learning purposes**.  
Predictions and drug recommendations should **not be considered as medical advice**.

Always consult a certified medical professional.

---

## 🙌 Acknowledgements

- Udemy Course: *Machine Learning Disease Prediction and Drug Recommendation*
- Django & Scikit-learn Open Source Community

---

## ⭐ Support

If you find this project helpful:
- ⭐ Star the repository
- 🍴 Fork the project
- 🧑‍💻 Contribute improvements

---
---

## 👨‍💻 Author

**Nagaram ManojKumar**  
Aspiring AI/ML Engineer & Full-Stack Developer  

🎓 B.Tech in Computer Science (AI & ML)  
💡 Passionate about Machine Learning, Django, and Real-World AI Applications  
🚀 Focused on building intelligent healthcare solutions  

---

## 📬 Contact

- GitHub: https://github.com/Zinb-NMK
- LinkedIn: *(linkedin.com/in/manojkumar-nagaram)*

---

© 2026 Nagaram ManojKumar. All rights reserved.
