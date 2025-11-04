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
- Signup/Login page
- <img width="500" height="500" alt="Signup_login" src="https://github.com/user-attachments/assets/d43363db-444e-4589-bc2d-0b5f6abdae16" />

- Profile Settings Page
- <img width="500" height="500" alt="Profile setting" src="https://github.com/user-attachments/assets/c08af76d-4273-4e75-8d77-eeec7b7977a6" />

- Home Page
- <img width="500" height="500" alt="Home" src="https://github.com/user-attachments/assets/8c83c891-a8cd-4090-ab75-4a6c1f660a1b" />

- Dark-mode Home Page
- <img width="500" height="500" alt="Dark Mode" src="https://github.com/user-attachments/assets/ff96a82a-7747-4a8d-b9a0-feac49c4cdc5" />

- Add Task Page
- <img width="500" height="500" alt="Add Task" src="https://github.com/user-attachments/assets/ce5762f9-de8c-459a-b768-b45785c7277d" />

- Calendar Page
- <img width="500" height="500" alt="Calendar" src="https://github.com/user-attachments/assets/f19fffdb-50aa-45b2-8228-5aa0d88b6855" />

- Analytics Page
- <img width="500" height="500" alt="Analytics" src="https://github.com/user-attachments/assets/09d1a274-2ba7-410d-8f4f-754c5c39a304" />




	
	
	
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
