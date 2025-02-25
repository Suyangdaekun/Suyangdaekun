# Sodamyeon - Senior Dating App with Face Reading & Astrology-Based Matching
<img src="SuyangApp/app/src/main/res/drawable/logo_sodamyeon.png" alt="Project Logo" style="width:200px; height:auto;"/>

## 📖 Overview
Sodamyeon is a senior dating app that combines traditional wisdom with modern technology.</br>
The app leverages face reading (physiognomy) and astrology-based matching algorithms to help users find meaningful connections.</br>
Built using Mediapipe for facial analysis, Flask for backend services, Socket for real-time communication, and Firebase for data management, sodamyeon provides a seamless and engaging user experience tailored for seniors.

## ✨ Key Features
Face Reading Analysis :
- Analyzes facial features using Mediapipe to provide personality insights.
Astrology-Based Matching :
- Matches users based on their zodiac signs and astrological compatibility.
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
| Frontend | Android (Java/Kotlin) |
| Facial Analysis | Mediapipe |
| Real-Time Communication | Socket.IO |
| Database & Authentication | Firebase Firestore, Firebase Authentication |
| Notifications | Firebase Cloud Messaging (FCM) |

## 🚀 Getting Started
Prerequisites
- Python 3.9+ (for Flask backend)
- Android Studio (for frontend development)
- Firebase account for database and authentication setup
  
## Installation
Clone the repository:
```bash
git clone https://github.com/Suyangdaekun/sodamyeon.git
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
The use of Mediapipe and astrology algorithms may have additional licensing terms.

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
