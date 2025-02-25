# Sodamyeon - Senior Dating App with Face Reading & Astrology-Based Matching
<img src="SuyangApp/app/src/main/res/drawable/logo_sodamyeon.png" alt="Project Logo" style="width:200px; height:auto;"/>

## 📖 Overview
Sodamyeon is a senior dating app that combines traditional wisdom with modern technology.</br>
The app leverages face reading (physiognomy) and astrology-based matching algorithms to help users find meaningful connections.</br>
Built using Mediapipe for facial analysis, Flask for backend services, Socket for real-time communication, and Firebase for data management, sodamyeon provides a seamless and engaging user experience tailored for seniors.
<video width="640" height="360" controls>
  <source src="앱 시연영상.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## ✨ Key Features
Face Reading Analysis :
- Analyzes facial features using Mediapipe to provide personality insights.
- Facial landmark analysis (Mediapipe, dlib, FAN)
- Physiognomy analysis algorithm
- Facial ratio measurement
  
Astrology-Based Matching :
- Matches users based on their zodiac signs and astrological compatibility.
- Birthdate-based astrology analysis
- Zodiac matching algorithm
- Compatibility analysis system
  
Real-Time Chat :
- Enables instant messaging between matched users via Socket.

User Profiles :
- Stores and manages user data securely using Firebase.

Senior-Friendly UI :
- Simple and intuitive interface designed for older adults.

## 🛠 Tech Stack
| Category | Technologies |
|----------|--------------|
| Backend | Flask, Socket.IO |
| Frontend | Android (Kotlin) | 
| Facial Analysis | Mediapipe, dlib, FAN |
| Real-Time Communication | Socket.IO, Firebase Realtime Database |
| Database & Authentication | Firebase Firestore, Firebase Authentication |
| Notifications | Firebase Cloud Messaging (FCM) |
| Image Processing | OpenCV, NumPy |

## 🚀 Getting Started
Prerequisites
- Python 3.9+ (for Flask backend)
- Android Studio (for frontend development)
- Firebase account for database and authentication setup
  
## Installation
Clone the repository:
```bash
git clone https://github.com/Suyangdaekun/Sodamyeon.git
```
Backend Server execution:
```bash
cd backend
python app.py
```
Configure Firebase:
- Create a Firebase project and download the google-services.json file.
- Place it in the app/ directory of the Android project.
  
Run the Android app:
- Open the project in Android Studio.
- Build and run on an emulator or physical device.
  
## 🖥 Usage
Sign Up/Login :
- Users can register using their email or Google account via Firebase Authentication.
Profile Creation :
- Upload a profile picture for face reading analysis.
- Enter your birth date for astrology-based matching.
  
Matching :
- The app analyzes facial features and zodiac compatibility to suggest matches.
Chat :
- Once matched, users can communicate in real-time using the chat feature.
  
## 📁 Project Structure
```
.
├── backend
│ ├── app.py # Flask server handling face reading and astrology logic
│ ├── requirements.txt # Python dependencies
│ └── static # Static files for API documentation
├── app
│ ├── src/main/java/com/sodamyeon/app
│ │ ├── MainActivity.kt # Main entry point for Android app
│ │ ├── ChatActivity.kt # Real-time chat implementation
│ │ └── FaceAnalysis.kt # Mediapipe integration for face reading
│ ├── res
│ │ ├── layout # XML layouts
│ │ └── drawable # Image assets
│ └── google-services.json # Firebase configuration file
└── README.md # Project documentation
```

## 📄 License
MIT License

Licenses of used external libraries:
- Mediapipe: Apache 2.0
- Firebase: Google APIs Terms of Service
- OpenCV: BSD 3-Clause

## 🔒 Security Considerations
- Firebase security rules setup
- User data encryption
- API authentication methods

## 🤝 Team
Team Name: Suyang
| Role | Name |
|----------|--------------|
| Project Leader | Yang Dong Hoon |
| Backend Developer | Ryu Yang Hwan |
| Frontend Developer | Moon Ee Hwan |
| UI/UX Designer | Shin Dong Chan |
| Face landmarks modeling | Su Hyok Yun |

## 📬 Contact
For inquiries, please contact:
wintrover@gmail.com
