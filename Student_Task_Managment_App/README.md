# 📚 TaskMaster - Complete Task Management System

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter" alt="Flutter">
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-brightgreen" alt="Platform">
  <img src="https://img.shields.io/badge/State%20Management-Provider-9B59B6" alt="Provider">
  <img src="https://img.shields.io/badge/Database-Firebase-FFA000" alt="Firebase">
</p>

<p align="center">
  <b>A comprehensive dual-application system for educational institutions to manage tasks, track student performance, and streamline communication between admins and students.</b>
</p>

---

## 📖 Introduction

**TaskMaster** is a complete task management ecosystem designed specifically for educational environments. It consists of two seamlessly integrated applications:

- **👨‍💼 Task_Admin App** - Empowers administrators and teachers to create, assign, and monitor tasks while gaining valuable insights into student performance.
- **👨‍🎓 Task_Student App** - Provides students with an intuitive dashboard to view assignments, track deadlines, and monitor their academic progress.

Built with Flutter and powered by Firebase, TaskMaster delivers a smooth, real-time experience across both platforms, making task management effortless and efficient.

---

## ✨ Key Features

### For Admins & Teachers
| Feature | Description |
|---------|-------------|
| 📊 **Admin Dashboard** | Comprehensive overview of all tasks, students, and system metrics |
| 👥 **Student Management** | Add, edit, and manage student profiles with ease |
| 📝 **Task Creation** | Create and assign tasks with deadlines, descriptions, and attachments |
| 📈 **Performance Analytics** | Track student progress with visual performance metrics |
| 🔔 **Real-time Updates** | Instant synchronization across all devices |

### For Students
| Feature | Description |
|---------|-------------|
| 🎯 **Personal Dashboard** | Personalized view of assigned tasks and deadlines |
| 📅 **Smart Calendar** | Visual calendar for tracking submission dates |
| ✅ **Task Tracking** | Mark tasks as complete with submission status |
| 📊 **Performance View** | Visual representation of academic progress |
| 🔐 **Secure Login** | Role-based authentication system |

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=flutter,dart,firebase" />
</p>

| **Category** | **Technologies** |
|--------------|-----------------|
| **Framework** | Flutter & Dart 🦋 |
| **State Management** | Provider |
| **Backend & Database** | Firebase (Auth, Firestore, Storage) ☁️ |
| **Local Storage** | Hive / Shared Preferences 📦 |
| **UI Components** | Material Design 3, Custom Animations ✨ |

---

## 📸 Screenshots

### 👨‍💼 Admin Interface

<div align="center">
  
| Loading Screen | Admin Dashboard | Student Management |
|:--------------:|:---------------:|:------------------:|
| <img src="https://github.com/user-attachments/assets/80ce30ac-1ab5-44f1-a74a-f7a848987024" width="200"/> | <img src="https://github.com/user-attachments/assets/c717fcd8-4dd4-42ee-9724-e843ed924a76" width="200"/> | <img src="https://github.com/user-attachments/assets/34e60509-9995-4a6b-86c8-654e5c6472ca" width="200"/> |

| Task Management | Performance Analytics |
|:---------------:|:---------------------:|
| <img src="https://github.com/user-attachments/assets/61d600b2-71a1-4ef3-8e98-9026c1a3b052" width="200"/> | <img src="https://github.com/user-attachments/assets/c781da0a-276b-4ed2-a0cb-fe29cdb3808f" width="200"/> |

</div>

---

### 👨‍🎓 Student Interface

<div align="center">
  
| Loading Screen | Login Screen | Task List | Calendar View |
|:--------------:|:------------:|:---------:|:-------------:|
| <img src="https://github.com/user-attachments/assets/57610013-dd5b-48d5-a7fd-1039c572ed02" width="200"/> | <img src="https://github.com/user-attachments/assets/ed2844ea-3af9-4b40-aade-0d7e047bb1da" width="200"/> | <img src="https://github.com/user-attachments/assets/946656df-1cbc-4e30-a323-efdc090cdac7" width="200"/> | <img src="https://github.com/user-attachments/assets/132947b8-b94a-4b33-b5bc-1f86de8f2160" width="200"/> |

| Performance Dashboard |
|:---------------------:|
| <img src="https://github.com/user-attachments/assets/0693ae2f-ec1b-4144-a8e6-d0c2bdc561ce" width="200"/> |

</div>

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (3.x or higher)
- Dart SDK
- Android Studio / VS Code
- Firebase Account (for backend services)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/taskmaster.git
   cd taskmaster
---

2. **Install dependencies for both apps**
   ```bash
   # For Admin App
   cd task_admin
   flutter pub get
   
   # For Student App
   cd ../task_student
   flutter pub get
   ```

3. **Firebase Setup**
   - Create a new Firebase project
   - Register Android/iOS apps
   - Download and add `google-services.json` (Android) or `GoogleService-Info.plist` (iOS)
   - Enable Authentication, Firestore, and Storage

4. **Run the apps**
   ```bash
   # Admin App
   flutter run -t lib/main_admin.dart
   
   # Student App
   flutter run -t lib/main_student.dart
   ```

---

## 📱 Download APKs

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/👨‍💼-Download%20Admin%20APK-FF6B6B?style=for-the-badge&logo=android&logoColor=white" alt="Admin APK">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/👨‍🎓-Download%20Student%20APK-4ECDC4?style=for-the-badge&logo=android&logoColor=white" alt="Student APK">
  </a>
</p>

---

## 🎥 Demo Video

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/▶️-Watch%20Demo%20Video-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch Demo">
  </a>
</p>

---

## 📁 Project Structure

```
taskmaster/
├── task_admin/              # Admin Application
│   ├── lib/
│   │   ├── screens/         # UI Screens
│   │   ├── models/          # Data Models
│   │   ├── providers/       # State Management
│   │   └── services/        # Firebase Services
│   └── pubspec.yaml
│
└── task_student/            # Student Application
    ├── lib/
    │   ├── screens/         # UI Screens
    │   ├── models/          # Data Models
    │   ├── providers/       # State Management
    │   └── services/        # Firebase Services
    └── pubspec.yaml
```

---

## 🔄 Future Enhancements

- [ ] Push Notifications for task reminders
- [ ] File attachments for assignments
- [ ] In-app messaging between admins and students
- [ ] Export performance reports as PDF
- [ ] Biometric authentication
- [ ] Dark mode support
- [ ] Multi-language support

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🐛 Report bugs and issues
2. 💡 Suggest new features
3. 📝 Improve documentation
4. 🔧 Submit pull requests

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Flutter Team](https://flutter.dev/) for the amazing framework
- [Firebase](https://firebase.google.com/) for robust backend services
- All contributors and testers who helped shape this project

---

<p align="center">
  Made with ❤️ for educators and students
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/yourusername/taskmaster?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/yourusername/taskmaster?style=social" alt="GitHub forks">
</p>
```

