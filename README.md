# 🎉 Event Attendance Scanner App 🎉

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/travis/Vaishnavi06Desai/FEST1/master.svg)](https://travis-ci.org/github/FEST1)

## 📜 Overview

Welcome to the **Event Attendance Scanner App**! This Android app was developed for a college fest in 2019 to streamline event attendance. After a user pays for an event, the app generates a unique QR code for them. Event coordinators can then scan the QR code to mark attendance. Firebase serves as the database to manage all data, ensuring smooth and secure operation.

## 🚀 Features

- **QR Code Generation**: Generate a unique QR code for users once they’ve paid for an event.
- **QR Code Scanning**: Event coordinators scan the QR codes to register attendance.
- **Firebase Integration**: Firebase handles user authentication and real-time database updates.
- **Instant Updates**: Event attendance is updated in real-time for both users and coordinators.

## 🛠️ Technologies Used

- **Android**: Built with Java/Kotlin.
- **Firebase**: Used for database management, authentication, and real-time updates.
- **QR Code Generator & Scanner**: Integrated to facilitate attendance tracking.
- **Firebase Authentication**: Secure login for users.

## 🔧 Installation

To run the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Vaishnavi06Desai/FEST1.git
    ```

2. **Open the project** in Android Studio.

3. **Set up Firebase**:
    - Go to the [Firebase Console](https://console.firebase.google.com/).
    - Create a new project and configure it with your Android app (download `google-services.json` and place it in your project).

4. **Build and Run**: Launch the app on an Android emulator or a physical device.

## 🧑‍💻 Usage

1. **Login**: Use Firebase authentication to log into the app.
2. **Generate QR Code**: After payment, a unique QR code will be generated.
3. **Attendance Tracking**: Event coordinators can scan the QR code to register the user’s attendance for the event.

## 🤝 Contributing

We welcome contributions to enhance this app! To contribute:

1. **Fork** the repository.
2. **Create a new branch**: `git checkout -b feature/your-feature`
3. **Commit your changes**: `git commit -am 'Add new feature'`
4. **Push your changes**: `git push origin feature/your-feature`
5. **Create a Pull Request**.

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for more details.

---

## ✨ Enjoy using the Event Attendance Scanner! ✨
