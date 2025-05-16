# 🎯 Face Recognition Attendance System

This is a real-time **Face Recognition Attendance System** built using OpenCV, scikit-learn, and Streamlit. It allows you to:
- Capture and register new faces
- Detect and recognize faces live via webcam
- Record attendance in CSV format
- View attendance logs in a web interface

---

## 📁 Project Structure

FACE_RECOGNITION_PROJECT/
│
├── Attendance/ # Stores daily attendance CSVs
├── data/ # Pickled face data and cascade file
│ ├── haarcascade_frontalface_default.xml
│ ├── faces_data.pkl # Saved face encodings
│ └── names.pkl # Corresponding names
│
├── add_faces.py # Script to add new face data
├── test.py # Face recognition & attendance logger
├── app.py # Streamlit web app for attendance viewing
├── bg.jpg # Background image for GUI overlay
└── README.md # This documentation file

markdown
Copy
Edit

---

## 🚀 Features

- 📸 **Face Data Collection** using webcam (`add_faces.py`)
- 🧠 **Real-Time Recognition** with KNN classifier (`test.py`)
- 📝 **Attendance Logging** in per-day CSV files
- 💬 **Text-to-Speech Announcements** on recognition
- 🌐 **Live Web Interface** using Streamlit to view attendance (`app.py`)
- 📦 **Data Persistence** with `pickle`

---


🧠 Tech Stack
OpenCV – Face detection and video capture

scikit-learn – KNN classifier for face recognition

Streamlit – Frontend interface to display attendance

pickle – Data serialization

pywin32 (SAPI) – Voice output for feedback
