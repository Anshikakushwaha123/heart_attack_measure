# 🫀 Heart Failure Prediction App

A simple web application built using **Flask** and **Python** that predicts the likelihood of heart failure in patients based on clinical parameters using a trained machine learning model.

## 📌 Features

- Input patient medical data through a web form
- Predict heart failure risk using a trained ML model
- Clean and responsive user interface (can be enhanced with Bootstrap/Tailwind)
- Easily extendable and customizable

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **ML Model:** Trained using scikit-learn (RandomForestClassifier/LogisticRegression etc.)
- **Frontend:** HTML, CSS (optionally with Bootstrap or Tailwind)

---


----


<img width="1920" height="1078" alt="Heart Failure Prediction - Google Chrome 22-07-2025 10_14_59" src="https://github.com/user-attachments/assets/d9002449-794a-478c-a009-e9cf8ddae0f7" />
<img width="1920" height="1078" alt="Heart Failure Prediction - Google Chrome 22-07-2025 10_15_06" src="https://github.com/user-attachments/assets/0b6649a6-162c-4c9e-8945-dd4d507cfa6e" />



----

## 📂 Project Structure

heart_failure_app/
│
├── static/ # Static files (CSS, images, JS)
├── templates/ # HTML templates
│ └── index.html
│
├── model/ # Trained ML model
│ └── heart_model.pkl
│
├── app.py # Flask application
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml
Copy
Edit

---

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/heart_failure_app.git
cd heart_failure_app
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Visit the app in your browser:

cpp
Copy
Edit
http://127.0.0.1:5000/
🧪 Input Parameters
The form accepts the following patient data:

Age

Anaemia (0/1)

Diabetes (0/1)

Ejection Fraction (%)

High Blood Pressure (0/1)

Platelets (k/mL)

Serum Creatinine (mg/dL)

Serum Sodium (mEq/L)

Sex (0 = Female, 1 = Male)

Smoking (0/1)

Time (follow-up period)

📊 Machine Learning Model
Trained on the publicly available Heart Failure Clinical Records Dataset

Preprocessing includes scaling and encoding

Saved as heart_model.pkl using joblib or pickle

📝 Example

📌 TODO
Add input validation

Improve UI with Tailwind or Bootstrap

Add more models and compare performance

Deploy on Render/Heroku/Netlify

📃 License
This project is open-source and available under the MIT License.

💬 Contact
For queries or collaborations, feel free to reach out at: your.email@example.com

yaml
Copy
Edit

---

Let me know if you want it tailored to your exact folder names, model type (e.g., Random Forest), or deployment method!
