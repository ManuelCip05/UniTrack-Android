# 🎓 UniTrack — University Career & Study Manager

**UniTrack** is a native Android application designed to help university students manage their academic path, calculate averages and graduation projections, organize class schedules, and store notes and study materials.

---

## 📲 Download & Try the App
* **Direct Download (APK):** Download the latest installable version directly from the [**GitHub Releases**](../../releases) section.
* **Google Play Store:** *Currently in Closed Testing on Google Play (Public release coming soon).*

---

## ✨ Key Features
* **Multi-Career & International Systems Support:** Full support for the Italian system (`/30` & `/110` with CFU) and international grading systems (GPA 4.0, France `/20`, Spain `/10` with ECTS).
* **Record Book & Advanced Simulator:** Real-time calculation of arithmetic average, weighted average, and graduation base, featuring a dedicated simulation section for upcoming exams, pass/fail courses, thesis points, and career bonuses.
* **Class Schedule & Exam Countdown:** Weekly class calendar filtered by ongoing courses, along with a countdown tracker for upcoming exam dates.
* **Study Materials:** Integrated management of text notes and file attachments (PDFs, slides, images) for every single course.
* **100% Offline & Privacy-First:** Completely local data storage with a JSON-based Backup Export/Import feature.
* **Customizable UI:** Light/Dark theme, pure AMOLED Black mode, customizable accent color palettes, and multi-language support (EN, IT, FR, ES).

---

## 🛠️ Tech Stack & Architecture 
* **Language:** 100% Kotlin
* **UI Framework:** Jetpack Compose (Material Design 3)
* **Architecture:** MVVM (Model-View-ViewModel) with reactive state management via Kotlin `StateFlow` and `Coroutines`
* **Data Persistence:** Custom local JSON database + `SharedPreferences`
* **Monetization:** Google AdMob SDK

---
*Developed by **MicroCip** — Full source code is kept in a private repository for commercial distribution purposes on the Google Play Store.*
