# 🎓 University Admission Prediction

A Machine Learning-based web application that predicts the probability of admission to a university based on student academic profile.

This project is deployed using Streamlit and built with a trained regression model.

🔗 Live App: https://admi-predictor.streamlit.app

# 📌 Features

Predicts admission chances based on:

GRE Score (out of 340)

TOEFL Score (out of 120)

University Rating (out of 5)

SOP Strength (out of 5)

LOR Strength (out of 5)

CGPA (out of 10)

Research Experience (0 or 1)

User-friendly Streamlit interface

Real-time prediction

Deployed on Streamlit Cloud

# 🛠️ Tech Stack

Python

Streamlit

Scikit-learn

NumPy

Pandas

Pickle (for model serialization)

📂 Project Structure
AD-main/
│
├── main.py                 # Streamlit application
├── finalized_model.pickle  # Trained ML model
├── scaler_model.pickle     # Feature scaler
├── requirements.txt        # Dependencies
├── image.webp              # App banner image
└── README.md               # Project documentation
#  How to Run Locally

Clone the repository

git clone https://github.com/your-username/AD-main.git
cd AD-main

Install dependencies

pip install -r requirements.txt

Run the Streamlit app

streamlit run main.py
# 🧠 Model Information

The model was trained using a regression algorithm.

Features were scaled before prediction.

Final prediction outputs the probability of admission.

# 📊 Example Output

The app returns:

Your predicted chance of admission is: 82.45%

🌟 Future Improvements

Add model accuracy metrics display

Add visualization graphs

Improve UI design

Deploy using Docker

Add more advanced ML models
