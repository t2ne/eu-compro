# EuCompro 🛒📱

A fully functional mobile application for managing supermarket shopping, developed using **Angular**, **Ionic**, and **Firebase**. The project leverages Capacitor for native functionality and integrates barcode scanning, camera access, offline storage, and real-time data syncing.

Originally designed in **Figma**, this app targets Android and iOS platforms and uses **Firebase** for authentication, database, and storage services.

---

## 🌟 Features

- 📦 **Product Scanning**: Barcode scanning for quick product entry.
- 🧾 **Shopping Lists**: Create and manage multiple shopping lists.
- 🔄 **Real-Time Sync**: Data is synced with Firebase for instant updates.
- ☁️ **Cloud Storage**: Store user data persistently via Firebase.
- 📷 **Camera Integration**: Capture product images through device camera.
- 💾 **Offline Support**: Local storage enabled via SQLite for offline usability.
- 📱 **Cross-Platform**: Runs on Android and iOS using Capacitor.

---

## 🛠️ Installation

### ✅ Prerequisites

Ensure the following are installed:

- [Node.js](https://nodejs.org/)
- npm
- (Opcional) Android Studio or Xcode

---

### 📥 Clone the Repository

```bash
git clone https://github.com/t2ne/eu-compro
cd eu-compro
```

---

### ⚙️ Install Ionic & Angular CLI

```bash
npm install -g @ionic/cli @angular/cli cordova-res
```

---

### 📦 Install Dependencies

```bash
npm install
```

---

## 🚀 Running the App

### Development Server

To run the app in a web browser:

```bash
ionic serve
```

---

### Android / iOS Deployment

#### Add Android Platform:
```bash
ionic capacitor add android
ionic capacitor open android
```

#### Add iOS Platform:
```bash
ionic capacitor add ios
ionic capacitor open ios
```

Use Android Studio or Xcode to build and run on an emulator or physical device.

---

## 🧪 Testing

Run unit tests:

```bash
npm run test
```

---

## 🙋‍♂️ Author

[@t2ne](https://github.com/t2ne) - [@eduardoc0uto](https://github.com/eduardoc0uto)

---

## 🎓 Academic Project

This application was developed as part of an academic project focused on cross-platform mobile development, demonstrating proficiency in:

- Angular + Ionic framework
- Firebase integration (Authentication, Firestore, Storage)
- Native APIs with Capacitor
- UX/UI design following a Figma prototype
