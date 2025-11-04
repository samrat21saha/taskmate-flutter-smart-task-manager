# 📱 TaskMate – Smart Task Manager App

A modern productivity app built with **Flutter** and **Firebase**, designed to help users manage tasks, deadlines, and daily goals efficiently.  
TaskMate focuses on **simplicity, speed, and cross-device synchronization**, delivering a seamless task management experience.

---

## 🚀 Features
- 🗓️ **Task Creation & Categorization** – Add, edit, and group tasks with tags or priority levels.  
- ⏰ **Smart Reminders** – Get notified before deadlines using Firebase Cloud Messaging.  
- 🌙 **Dark Mode Support** – Adaptive theming for better UX in all lighting conditions.  
- 🔄 **Real-Time Sync** – Tasks sync across devices via Firebase Realtime Database.  
- 📊 **Progress Analytics** – Visual dashboards to track productivity trends.  
- 🧠 **Offline Capability** – View and update tasks even without an internet connection.

---

## 🏗️ Tech Stack

| Category | Technologies Used |
|-----------|------------------|
| Frontend | Flutter (Dart) |
| Backend | Firebase Authentication, Firestore Database |
| State Management | Provider |
| Notifications | Firebase Cloud Messaging |
| Storage | Firebase Storage |
| UI Design | Material 3 Widgets, Custom Animations |

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/samrat21saha/taskmate-flutter-smart-task-manager.git

# Navigate to the project
cd taskmate-flutter-smart-task-manager

# Get dependencies
flutter pub get

# Run the app
flutter run
```
## 📸 Screenshots


	
	
	
## 🧩 Architecture Overview

- MVVM Pattern – Promotes scalability and maintainability.
- Provider for State Management – Ensures reactive, event-driven UI updates.
- Firebase Service Layer – Abstracts authentication, CRUD, and storage operations.

- Folder Structure Example:

lib/
 ┣ models/
 ┣ providers/
 ┣ services/
 ┣ screens/
 ┣ widgets/
 ┗ main.dart

## 🧠 Future Enhancements
- AI-powered task prioritization
- Calendar integration
- Team collaboration and shared task lists
