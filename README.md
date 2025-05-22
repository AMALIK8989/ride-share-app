# Ridely

Ridely is a Flutter-based ride-hailing app, inspired by Uber, allowing users to book rides and drivers to accept requests — all in a single app. It features real-time location tracking, scheduled rides, driver selection, and multi-language support. Built for both Android and iOS, using Firebase and Google APIs.

---

## 🚗 Features

- User & Driver roles (auto-detected, all-in-one app)
- Real-time ride requests and live tracking
- Scheduled rides (pick date & time)
- Manual driver selection by users
- Multi-language support
- Clean, modern UI (purple & gold theme)
- Firebase Auth & Firestore Database
- Google Maps integration

---

## 📱 Screenshots

_**(Add your app screenshots here)**_

---

## 🛠️ Tech Stack

| Tech                       | Description                           |
|----------------------------|---------------------------------------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="32" width="32"/> | Flutter (Dart)      |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="32" width="32"/> | Firebase Auth/Firestore |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" height="32" width="32"/> | Google Maps & Places API |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg" height="32" width="32"/> | Android             |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" height="32" width="32"/> | iOS                 |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="32" width="32"/> | GitHub Actions (CI/CD)  |

---

## 🎨 UI Color Theme

| Name            | Color Code | Usage         |
|-----------------|------------|--------------|
| Primary         | `#6A0DAD`  | Royal Purple |
| Accent          | `#FFD700`  | Gold         |
| Background      | `#F5F5F5`  | Light Gray   |
| Text Primary    | `#1A1A1A`  | Black        |
| Secondary       | `#FFFFFF`  | White        |
| Error           | `#E53935`  | Error/Alert  |

---

## 🚀 Getting Started

1. **Clone the repo**
   ```sh
   git clone https://github.com/yourusername/ridely.git
   cd ridely
   ```

2. **Install dependencies**
   ```sh
   flutter pub get
   ```

3. **Setup Firebase**
   - Create Firebase project.
   - Add Android/iOS apps.
   - Download `google-services.json` & `GoogleService-Info.plist` into `/android/app` and `/ios/Runner`.
   - Enable Authentication (email/phone), Firestore, and Maps APIs.

4. **Configure Google Maps**
   - Add your API keys in platform-specific files.

5. **Run the app**
   ```sh
   flutter run
   ```

---

## 🎯 Roadmap

- [ ] Complete user & driver flows
- [ ] Scheduled ride logic
- [ ] Manual driver selection
- [ ] Multi-language support (add more languages)
- [ ] Admin dashboard (optional)

---

## 🤝 Contributing

Pull requests are welcome! Please open issues to discuss features or bugs.

---

## 📝 License

MIT License. See [LICENSE](LICENSE) for details.

---
