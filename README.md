# FarmFix
# 🌿 Plant Disease Detection Web App

A Flask-based web application that uses a pre-trained TensorFlow model to detect plant diseases from uploaded leaf images.

## 🚀 Features

- Upload leaf images to detect diseases
- Deep learning model powered by TensorFlow
- User-friendly and responsive UI
- Background image support for a better visual experience

---

## 🧰 Tech Stack

- Python 3.10
- Flask
- TensorFlow
- NumPy
- HTML/CSS

---

## 📁 Project Structure

├── static/
│ └── images/
│ └── bg.jpg # Background image for UI
├── templates/
│ └── index.html # HTML front-end
├── plant_disease_model.h5 # Pre-trained model
├── app.py # Flask backend
├── README.md # You're here!


---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/plant-disease-detection.git
cd plant-disease-detection

py -3.10 -m venv tf-env         # Create virtual environment
source tf-env/Scripts/activate # Activate on Git Bash (Windows)

source tf-env/bin/activate #for mac or Linux

pip install flask numpy tensorflow

python app.py

* Running on http://127.0.0.1:5000/

