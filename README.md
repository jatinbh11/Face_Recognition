# 🎯 Face Recognition Attendance System

This is a real-time **Face Recognition Attendance System** built using OpenCV, scikit-learn, and Streamlit. It allows you to:
- Capture and register new faces
- Detect and recognize faces live via webcam
- Record attendance in CSV format
- View attendance logs in a web interface

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
