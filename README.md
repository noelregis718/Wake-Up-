# Wake Up Alarm

**Wake Up Alarm** is a robust and feature-rich React Native application designed to help you start your day right. Built with modern technologies and a focus on reliability, it integrates seamless authentication, cloud synchronization, and advanced notification capabilities.

## 🚀 Features

-   **Smart Alarms**: Reliable alarm scheduling using `@notifee/react-native`.
-   **Cloud Sync**: precise data synchronization with **Firebase Firestore**.
-   **Secure Authentication**:
    -   Google Sign-In integration.
    -   Firebase Authentication for secure user management.
-   **Fast Local Storage**: Utilizes `react-native-mmkv` for lightning-fast local data persistence.
-   **Modern Interaction**: Smooth navigation with React Navigation and intuitive UI components.
-   **Push Notifications**: Integrated with Firebase Cloud Messaging (FCM).

## 🛠️ Tech Stack

-   **Core**: React Native (v0.72.6), React (v18.2.0)
-   **Navigation**: React Navigation (Native Stack)
-   **Backend / Services**: Firebase (Auth, Firestore, Messaging)
-   **Storage**: MMKV (Local), Firestore (Cloud)
-   **Notifications**: Notifee
-   **UI/UX**: React Native SVG, React Native Date Picker, Safe Area Context

## ⚙️ Prerequisites

Before you begin, ensure you have met the following requirements:
-   Node.js (>= 16)
-   Java Development Kit (JDK)
-   Android Studio (for Android development)
-   Xcode (for iOS development, macOS only)

## 📦 Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/noelregis718/Wake-Up-.git
    cd Wake-Up-
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Firebase Configuration**:
    -   Place your `google-services.json` file in `android/app/`.
    -   Place your `GoogleService-Info.plist` file in `ios/`.

## 📱 Running the App

### Android
1.  Start the Metro server:
    ```bash
    npm start
    ```
2.  Run the application:
    ```bash
    npm run android
    ```

### iOS
1.  Install CocoaPods dependencies:
    ```bash
    cd ios && pod install && cd ..
    ```
2.  Run the application:
    ```bash
    npm run ios
    ```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/noelregis718/Wake-Up-/issues).

## 👤 Author

**Noel Regis**

-   **Email**: [noelregis718@gmail.com](mailto:noelregis718@gmail.com)
-   **GitHub**: [@noelregis718](https://github.com/noelregis718)

---
*Built with ❤️ by Noel Regis*
