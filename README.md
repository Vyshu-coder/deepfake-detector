# 🔍 Deepfake Detection System

A full-stack web application that detects deepfakes in images and videos
using an EfficientNetB0-based CNN model.

## ✨ Features
- 🧠 ML-powered deepfake detection (EfficientNetB0)
- 🎞️ Supports both image and video uploads
- 🔐 User authentication (login, signup, forgot password)
- 🛠️ Admin dashboard for user/detection management
- 📊 Forensic analysis panel
- 📁 Detection history per user
- 📧 Email verification/reset support
- 🚦 Rate limiting & file cleanup scheduler

## 🛠️ Tech Stack
| Layer     | Technology                        |
|-----------|-----------------------------------|
| Backend   | Python, Flask, SQLAlchemy         |
| ML Model  | TensorFlow, Keras, EfficientNetB0 |
| Frontend  | HTML, CSS, Vanilla JavaScript     |
| Database  | SQL (via SQLAlchemy)              |

## 🚀 Getting Started

### 1. Install dependencies
pip install -r backend/requirements.txt

### 2. Set up environment variables
Copy `.env.example` to `.env` and fill in values.

### 3. Run the app
python backend/app.py

### 4. Open in browser
http://localhost:5000

## 📸 Screenshots
(Add screenshots here)

## 📜 License
MIT
