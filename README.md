# Airgap 🛡️

**Secure Your Focus. Hardened Productivity for macOS, iPad, and iPhone.**

![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20iOS%20%7C%20iPadOS-lightgrey)
![Stack](https://img.shields.io/badge/Tech-SwiftUI%20%7C%20SwiftData%20%7C%20CloudKit-orange)
![License](https://img.shields.io/badge/License-AGPLv3-red)
![Status](https://img.shields.io/badge/Status-Active%20Development-success)

## 📡 The Protocol
**Airgap** is a cross-platform cognitive performance suite designed for the "Make and Break" mindset. It doesn't just track time; it enforces a security boundary around your focus.

Built on the scientific **50/10 Ultradian Rhythm**, Airgap ensures you maintain peak cognitive output without burnout.

> **Note:** This is an open-source project that I use personally. It will eventually be released on the App Store with an "Open Core" model (Free core features, Premium cloud/advanced features).

## ✨ Features

### Core (Open Source)
* **⚡ Scientific Splits:** Default 50-minute Deep Work / 10-minute Active Recovery cycles.
* **🖥️ Native Experience:** Optimized UI for macOS (Menu Bar/Window), iPad (Sidebar), and iPhone.
* **📊 Local History:** Track your session data locally on your device.

### Advanced (In Development)
* **🛡️ Multi-Device Lockdown:** Start a session on your Mac, and your iPhone automatically enters "Shields Up" mode (Lockdown).
* **☁️ iCloud Sync:** Seamless state synchronization using SwiftData & CloudKit.
* **🔒 App Shielding:** Integration with the `FamilyControls` API to physically block distracting apps during work sessions.

## 🛠️ Tech Stack

* **Language:** Swift 6
* **UI Framework:** SwiftUI (Multiplatform)
* **Persistence:** SwiftData (SQLite)
* **Sync Engine:** iCloud / CloudKit
* **Architecture:** MVVM (Model-View-ViewModel) with `@Observable`

## 🚀 Getting Started

### Prerequisites
* Xcode 16.0+
* iOS 17.0+ / macOS 14.0+
* Apple Developer Account (Required for "App Shielding" & iCloud capabilities)

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/airgap.git](https://github.com/yourusername/airgap.git)
    ```
2.  **Open the project:**
    Double-click `Airgap.xcodeproj`.
3.  **Configure Signing:**
    * Go to Project Settings > Signing & Capabilities.
    * Select your **Personal Team**.
    * Ensure **iCloud** and **Family Controls** capabilities are enabled.
4.  **Build & Run:**
    Press `Cmd + R` to launch on your Simulator or Device.

## 🗺️ Roadmap

- [x] Core Timer Logic (State Machine)
- [x] SwiftData Persistence
- [x] iCloud Synchronization
- [ ] **Lockdown Mode:** Integration with `FamilyControls` API to block social apps.
- [ ] **Live Activities:** Dynamic Island support for iPhone 15/16.
- [ ] **Statistics:** Visual graphs of "Deep Work" hours vs. "Distracted" hours.
- [ ] **App Store Release:** Launching the compiled binary for public use.

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)**.

* **Free to Use:** You are free to use, modify, and distribute this software.
* **Open Source:** If you modify this code and distribute it (or host it as a service), you **must** open-source your changes under the same license.
* **Commercial Use:** The trademark "Airgap" and the App Store release are reserved by the author.

## 🤝 Contributing

Contributions are welcome! This is a long-term project.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 👤 Author

**Martin-Luther Obahor**
* *Make and Break* Philosophy
* [LinkedIn](https://linkedin.com/in/yourprofile)

---

*"Discipline is freedom."*
