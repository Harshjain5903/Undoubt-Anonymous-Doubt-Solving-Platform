# Undoubt: Anonymous Doubt Solving Platform 🚀

Undoubt is a cross-platform mobile application built with **Flutter** and **Firebase** that provides a safe, anonymous space for students to ask questions and share knowledge. It bridges the gap between classroom hesitation and academic clarity through a structured, real-time "Classroom" ecosystem.

---

## 📌 Project Overview
Many students feel intimidated asking questions in person or on public forums. **Undoubt** solves this by offering an anonymous-first approach where users can join virtual classrooms, post doubts with image support, and receive solutions from peers or instructors without the fear of judgment.

### 🎯 Key Features
* **Virtual Classrooms:** Create or enroll in classrooms using unique generated codes.
* **Anonymous Engagement:** Post doubts and answers anonymously to encourage participation.
* **Multi-modal Doubts:** Support for text and image-based questions for complex subjects (math, diagrams, etc.).
* **Real-time Synchronization:** Powered by Firebase Firestore for instant updates across all users.
* **Secure Authentication:** Integrated Google Sign-In for a seamless and verified user experience.

---

## 🏗️ Technical Architecture
├── lib/
│   ├── screens/       # UI Layers (Home, Classroom, Doubt, Settings)
│   ├── services/      # Backend logic (Firebase Auth & Firestore)
│   ├── helpers/       # Local storage & Shared Preferences
│   └── main.dart      # Application entry point
├── assets/            # UI components and branding imagery
├── android/           # Android-specific configurations
└── ios/               # iOS-specific configurations
🛠️ Tech Stack
Frontend: Flutter (Dart) for high-performance, cross-platform UI.

Backend: Firebase Authentication (Google Sign-In).

Database: Cloud Firestore (NoSQL real-time database).

Storage: Firebase Storage for hosting doubt-related images.

Local Storage: Shared Preferences for persistent user session management.

🛠️ Technical Implementation Highlights
1. Anonymous Ecosystem
Implemented a logic layer that decouples user identity from public posts while maintaining backend traceability for security. This ensures users feel safe while administrators can still manage content.

2. Scalable Database Design
The Firestore schema is optimized for "Classroom" sub-collections, allowing the app to handle thousands of concurrent queries within specific doubt threads without performance degradation.

3. Image Processing
Integrated image_picker and Firebase Storage to allow users to upload high-resolution photos of their physical notes or textbooks directly into the doubt stream.

🚀 Getting Started
Prerequisites
Flutter SDK

Dart 3.0+

Firebase Project Credentials (google-services.json for Android / GoogleService-Info.plist for iOS)

Installation
Clone the repository:

Bash
git clone [https://github.com/Harshjain5903/Undoubt-Anonymous-Doubt-Solving-Platform.git](https://github.com/Harshjain5903/Undoubt-Anonymous-Doubt-Solving-Platform.git)
cd Undoubt-Anonymous-Doubt-Solving-Platform
Install dependencies:

Bash
flutter pub get
Configure Firebase: Place your google-services.json in android/app/.

Run the application:

Bash
flutter run
📈 Future Roadmap
Push Notifications: Alerting users when their doubts are answered.

AI Integration: Automated doubt categorization and basic AI-generated hints.

Web Support: Expanding the Flutter codebase to support a desktop/web browser version.

👨‍💻 Author
Harsh Jain Computer Science Graduate Student at UIC

Connect with me: LinkedIn • GitHub
