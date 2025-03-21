# Automated Attendance System using Facial Recognition (Python)

A smart, real-time attendance system that uses facial recognition to automatically detect and record attendance—eliminating manual efforts and reducing proxy risks. Built with Python, OpenCV, Flask, and machine learning techniques like KNN and Haar Cascade.

## Project Overview
This project is designed to automate the attendance tracking process in educational institutions and workplaces using Face Recognition Technology. By capturing live video frames from a webcam, the system identifies faces in real-time, matches them with pre-trained images, and logs attendance into an Excel file automatically.

The system provides:
- A web-based GUI for taking and viewing attendance
- Real-time face detection & recognition
- Excel report generation
- Ability to add new users (students/employees) to the face database


## Technologies Used
- Python 3.x
- OpenCV – for face detection & image processing
- Haar Cascade Classifier – for efficient face detection
- KNN (k-Nearest Neighbors) – for face recognition
- Flask – for web application and routing
- Pandas – for attendance management
- NumPy – for image data handling
- Sklearn (scikit-learn) – for ML classification
- HTML/CSS – for GUI templating
- Joblib – to save and load the trained ML model

## Features
- Real-time face detection and recognition
- Auto-generated attendance reports (CSV format)
- Add new users with webcam
- Admin-only access for adding/training data
- Lightweight web interface using Flask

