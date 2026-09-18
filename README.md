<div align="center">
  <h1>KNP Management System</h1>
  <p><em>A Digital Classroom Platform for Kabete National Polytechnique</em></p>
  <br>
  <p>
    <a href="https://github.com/shelad3/Kabete-Poly/releases/latest">
      <img src="https://img.shields.io/github/v/release/shelad3/Kabete-Poly?color=818cf8&label=latest%20release" alt="Latest release">
    </a>
    <img src="https://img.shields.io/badge/platform-Android-brightgreen" alt="Platform">
    <img src="https://img.shields.io/badge/framework-Flutter-02569B" alt="Flutter">
    <img src="https://img.shields.io/badge/backend-Firebase-orange" alt="Firebase">
    <img src="https://img.shields.io/badge/admin-Python%2FPyQt6-3776AB" alt="Admin stack">
  </p>
  <br>
  <p>
    <a href="#features">Features</a> &middot;
    <a href="#ecosystem">Ecosystem</a> &middot;
    <a href="#download">Download</a> &middot;
    <a href="#installation">Installation</a> &middot;
    <a href="#tech-stack">Tech Stack</a> &middot;
    <a href="#development">Development</a>
  </p>
</div>

---

## About

KNP Management System replaces the old paper-based way of sharing lecture notes, lab reports and class schedules with a platform that works in real time.

- **Students** access lessons, timetables and grades from their phones, and get notified the moment something new goes up.
- **Staff** publish materials and release results from a lightweight desktop admin tool.
- **Everyone** communicates through class forums, direct messaging and push notifications.

Built by a student, for students — learning everything from Flutter to Firebase to deployment along the way.

---

## Features

| Feature | Description |
|---------|-------------|
| **Lesson Archive** | Browse and download lecture notes, lab reports, and past papers organized by class |
| **Timetable** | Real-time class schedules with per-day weekly views, a **week grid**, **today-first** ordering, automatic **scroll-to-today**, and reminders fired **20 minutes before** each class |
| **Grades Portal** | View CAT1, CAT2, and exam results as soon as they're published |
| **Class Forums** | Discussion boards for each class — ask questions, share resources |
| **Messaging** | Direct messaging with classmates and teachers |
| **Push Notifications** | Instant alerts for new materials, timetable changes, grade updates and class reminders |
| **Campus Map** | Google Maps integration to find rooms, labs, and faculty offices |
| **Faculty Directory** | Contact info for all lecturers and staff |
| **In-app updates** | The app checks the project repository for a newer APK on launch |

---

## Ecosystem

| Surface | Stack | Description |
|---------|-------|-------------|
| **Student App** | Flutter / Android | The main app students use daily |
| **Admin Tool** | Python + PyQt6 + Firebase Admin SDK | Manage classes, publish lessons, timetables and grades |
| **Mark Scanner** | Android | Optical mark scanning that feeds scores into the grades portal |
| **Landing Page** | HTML / CSS / JS | This site — downloads the latest APK straight from the project repo |

All surfaces share a single Firebase (Firestore + Auth + Cloud Messaging) backend.

---

## Download

<div align="center">
  <a href="https://github.com/shelad3/Kabete-Poly/releases/latest">
    <img src="https://img.shields.io/badge/Download-APK-brightgreen?style=for-the-badge&logo=android&logoColor=white" alt="Download latest APK">
  </a>
</div>

The button (and the landing page) always resolve to the **latest release of the app project** at
[`shelad3/Kabete-Poly`](https://github.com/shelad3/Kabete-Poly/releases/latest) — no stale links, no manual version bumps.

Scan the QR code below with your phone to download the latest APK:

<div align="center">
  <img src="https://api.qrserver.com/v1/create-qr-code/?size=250x250&data=https://github.com/shelad3/Kabete-Poly/releases/latest" alt="Scan to download the latest APK">
  <br>
  <sup>Points straight at the newest release asset on GitHub</sup>
</div>

---

## Installation

1. Download the latest APK from the link above or scan the QR code.
2. Open the downloaded file on your Android device.
3. If prompted, allow installation from unknown sources (`Settings > Security > Install unknown apps` / `Play Protect > Install anyway`).
4. Launch the app and register using your student email.
5. Select your class and start exploring.

> **Note:** The app requires an internet connection for registration and real-time features. Timetable data is cached for offline use after the first load.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Flutter / Dart |
| Backend | Firebase (Firestore, Auth, Cloud Messaging) |
| File Storage | Cloudinary |
| Maps | Google Maps SDK |
| State Management | Provider + ChangeNotifier |
| Admin Tool | Python + PyQt6 + Firebase Admin SDK |

---

## Development

```bash
# Clone the app repository
git clone https://github.com/shelad3/Kabete-Poly.git
cd Kabete-Poly

# Fetch dependencies
flutter pub get

# Run on a device / emulator
flutter run
```

> **Note:** The app relies on a private Firebase project and configuration (`google-services.json`). Reach out via a GitHub issue if you'd like to contribute or experiment.

This repo (`KNP-Management-System`) hosts the public landing page — pure HTML/CSS/JS with no build step. Open `index.html` directly or serve it with any static server.

---

## Author

**Sheldon Ramu** — Electrical Engineering student at Kabete National Polytechnique (Level 5).

Everything — Flutter, Firebase, UI design, deployment — was learned hands-on during the development of this project starting February 2026.

- GitHub: [@shelad3](https://github.com/shelad3)

---

## License

Distributed for educational / institutional use. See the individual project repositories for licensing details.