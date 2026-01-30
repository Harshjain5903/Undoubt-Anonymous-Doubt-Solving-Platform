# Undoubt: Anonymous Doubt-Solving Platform 🚀

**Undoubt** is a high-performance, cross-platform mobile application developed with **Flutter** and **Firebase**. It provides a secure, anonymous environment for students to seek academic clarity, eliminating the social barrier of asking questions in traditional classroom settings.

---

## 📌 Project Overview
Many students hesitate to ask questions due to the fear of peer judgment. **Undoubt** bridges this gap by offering an "Anonymous-First" ecosystem. Users can join virtual classrooms, post image-supported doubts, and engage in real-time knowledge sharing without revealing their identity.

### 🎯 Key Features
* **Virtual Classrooms:** Create or join specialized study groups via unique invite codes.
* **Anonymous Engagement:** Post questions and provide solutions anonymously to foster inclusive participation.
* **Multi-modal Doubts:** Full support for text and high-resolution image uploads for complex problem-solving.
* **Real-time Synchronization:** Utilizes Firebase Firestore for instantaneous updates and live collaboration.
* **Secure Authentication:** Seamless and verified user onboarding via Google Sign-In integration.

---

## 🏗️ Repository Structure
├── lib/
│   ├── screens/       # UI Layer (Classroom, Doubt Threads, Auth)
│   ├── services/      # Backend Logic (Firebase Auth & Firestore)
│   ├── helpers/       # Persistence (Shared Preferences)
│   └── main.dart      # App Entry Point
├── assets/            # Branding and UI Assets
├── android/           # Native Android Configuration
└── ios/               # Native iOS Configuration
🛠️ Tech Stack
Frontend: Flutter (Dart) – Delivering a consistent, native experience on Android & iOS.

Authentication: Firebase Auth – Secured via Google OAuth.

Database: Cloud Firestore – Real-time NoSQL database for low-latency data syncing.

Storage: Firebase Storage – Optimized hosting for user-generated image content.

🛠️ Technical Implementation
1. Privacy-Centric Architecture
Designed a custom logic layer that decouples public-facing profiles from user identities. This ensures complete anonymity for the student while maintaining backend security and data integrity.

2. Optimized Data Streams
Leveraged Firestore’s listener-based architecture to build a reactive UI. The app handles concurrent classroom activity efficiently, ensuring that doubt threads update in real-time without manual refreshing.

3. Scalable File Management
Implemented a robust image-handling pipeline using image_picker and Firebase Storage, enabling users to upload and view clear, compressed images of diagrams or handwritten notes.

🚀 Getting Started
Prerequisites
Flutter SDK (Version 3.0+)

Firebase project credentials (google-services.json or GoogleService-Info.plist)

Installation
Clone the repository:

Bash
git clone [https://github.com/Harshjain5903/Undoubt-Anonymous-Doubt-Solving-Platform.git](https://github.com/Harshjain5903/Undoubt-Anonymous-Doubt-Solving-Platform.git)
cd Undoubt-Anonymous-Doubt-Solving-Platform
Install dependencies:

Bash
flutter pub get
Run the application:

Bash
flutter run
👨‍💻 Author
Harsh Jain Computer Science Graduate Student at UIC

Connect with me: LinkedIn • GitHub
