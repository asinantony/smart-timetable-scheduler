# Smart Timetable Scheduler

A **Flutter-based Smart Timetable Application** designed to automate academic scheduling for institutions.  
The system allows **administrators and lecturers** to manage and generate class timetables efficiently using a **Genetic Algorithm** for optimized scheduling.

The application integrates **Firebase Authentication** and **Cloud Firestore** for secure login and real-time data management.

---

# Project Overview

Managing academic timetables manually can lead to scheduling conflicts, inefficient classroom allocation, and time-consuming administrative work.

This project provides a **smart scheduling solution** that automatically generates optimized timetables while avoiding conflicts between:

- lecturers
- classrooms
- subjects
- time slots

The system is built using **Flutter for cross-platform support**, allowing deployment on **Android, iOS, Web, and Desktop**.

---

# Key Features

### Role-Based Login System
- Separate access for **Admin** and **Lecturer**
- Secure authentication using Firebase

### Automated Timetable Generation
- Uses a **Genetic Algorithm** to generate conflict-free timetables
- Optimizes scheduling across multiple constraints

### Cloud-Based Data Management
- All timetable data stored in **Firebase Cloud Firestore**
- Enables real-time updates

### Cross Platform Application
The application runs on:

- Android
- iOS
- Web
- Windows
- macOS
- Linux

### Modern User Interface
- Built using **Flutter and Dart**
- Responsive UI for multiple devices

---

# Tech Stack

| Technology | Usage |
|-------------|------|
| Flutter | Cross-platform UI framework |
| Dart | Application logic |
| Firebase Authentication | User login & role management |
| Cloud Firestore | Cloud database |
| Genetic Algorithm | Automated timetable generation |
| GitHub Actions | CI/CD workflow for deployment |

---

# System Architecture

The application consists of three main layers:

### Frontend
Flutter-based UI handling user interactions and displaying timetable data.

### Backend Services
Firebase Authentication for user login and Firestore database for storing timetable information.

### Scheduling Engine
Genetic Algorithm used to generate optimized timetables based on constraints.

---

Screenshots

<img width="963" height="624" alt="image" src="https://github.com/user-attachments/assets/32f59ba2-3e2e-4a6c-9d87-5afeea447df8" />
<img width="934" height="651" alt="image" src="https://github.com/user-attachments/assets/6ba16455-df02-475a-9f28-f81b47fb9ced" />
<img width="955" height="670" alt="image" src="https://github.com/user-attachments/assets/ab9713eb-9b30-452b-922f-7eb8a6dfe96e" />
<img width="955" height="549" alt="image" src="https://github.com/user-attachments/assets/56b39f91-b87d-449c-b974-178f411290ee" />
<img width="959" height="560" alt="image" src="https://github.com/user-attachments/assets/5e42f1b0-127b-414f-9323-c81a1051daf1" />
<img width="571" height="773" alt="image" src="https://github.com/user-attachments/assets/093afb68-dbbc-495e-b1bd-78779fdf1d5f" />
<img width="542" height="324" alt="image" src="https://github.com/user-attachments/assets/c794f061-e1eb-4641-8449-d89cf072091b" />
<img width="544" height="249" alt="image" src="https://github.com/user-attachments/assets/42fcb313-861a-429d-a80b-c5071e029fe7" />


# Project Structure

```
smart-timetable-scheduler
│
├── android/                 # Android platform code
├── ios/                     # iOS platform code
├── web/                     # Web platform code
├── windows/                 # Windows platform code
├── macos/                   # macOS platform code
├── linux/                   # Linux platform code
│
├── lib/                     # Main Flutter application code
├── functions/               # Firebase cloud functions
│
├── images/                  # Screenshots for README
│
├── firebase.json            # Firebase configuration
├── firestore.rules          # Firestore security rules
├── pubspec.yaml             # Flutter dependencies
└── README.md
```

---

# Installation Guide

### 1 Clone the Repository

```
git clone https://github.com/asinantony/smart_timetable.git
cd smart_timetable
```

### 2 Install Dependencies

```
flutter pub get
```

### 3 Add Firebase Configuration Files

Add your Firebase configuration files:

```
android/app/google-services.json
ios/Runner/GoogleService-Info.plist
```

### 4 Run the Application

```
flutter run
```

---

# Future Improvements

Potential improvements for this project include:

- AI-based timetable optimization
- Classroom availability prediction
- Lecturer workload balancing
- Interactive timetable dashboard
- Notification system for schedule updates

---

# Author

**Asin Fraisiya**

BCA – Data Analytics  
Aspiring Data Analyst | Data Visualization | Python | Power BI

LinkedIn  
https://www.linkedin.com/in/asin-fraisiya-v-a-36694427a

GitHub  
https://github.com/asinantony
