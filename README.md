# PriceCart 🛒📱

[![Release](https://img.shields.io/github/v/release/Nhlanhla-Muthwa/PriceCartApk?color=blue&label=Latest%20Release)](https://github.com/Nhlanhla-Muthwa/PriceCartApk/releases)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Fire%20OS-brightgreen.svg)](https://github.com/Nhlanhla-Muthwa/PriceCartApk)

**PriceCart** is an intelligent, privacy-first mobile shopping assistant built with modern Android development standards. Powered by **On-Device Machine Learning (Edge AI)**, PriceCart enables users to scan shelf price tags instantly using their phone camera, manage dynamic cart running totals, and avoid checkout surprises—all without requiring an internet connection.

---

## 🌟 Key Features

* **🤖 On-Device AI Scanner:** Real-time optical character recognition (OCR) powered by Google ML Kit to detect price tags instantly without sending data to external servers.
* **🔒 100% Private & Offline:** All camera feeds, price history, and cart lists remain strictly on your physical device. Works seamlessly in stores with low or no cell service.
* **⚡ Real-Time Running Totals:** Dynamic arithmetic engine calculates total costs, taxes, and budget thresholds on the fly.
* **💾 Local History (Room DB):** Built on Android's native Room database engine to save and organize past shopping carts offline.
* **🔐 Secure & Obfuscated:** Built with R8 code shrinking and cryptographically signed with a 25-year RSA-2048 publisher key.

---

## 🛠️ Tech Stack & Architecture

* **Language:** Kotlin
* **UI Framework:** Jetpack Compose (Modern Declarative UI)
* **AI & Computer Vision:** Google ML Kit (Text Recognition API) + CameraX
* **Database:** Room Database (SQLite abstraction)
* **Architecture:** MVVM (Model-View-ViewModel) + Clean Architecture
* **Security & Build Tools:** R8 Code Shrinking / Obfuscation, Gradle (Kotlin DSL), APK Signature Scheme v2

---

## 📥 Direct Download & Installation

You can download the production APK directly from the official releases page or sideload it onto any compatible Android or Amazon Fire OS device:

1. Download the latest release binary: [**`PriceCart.apk`**](https://github.com/Nhlanhla-Muthwa/PriceCartApk/releases/latest/download/PriceCart.apk)
2. Open the file on your mobile device and grant permission to install from unknown sources if prompted.
3. Launch **PriceCart** and start scanning!

---

## 👤 Author & Maintainer

**Nhlanhla Muthwa**  
*Founder & Software Engineer*  
* 🌍 **Website:** [Nhlanhla Muthwa Personal Portfolio](https://nhlanhlamuthwa.netlify.app)
* 🐙 **GitHub:** [@Nhlanhla-Muthwa](https://github.com/Nhlanhla-Muthwa)
  

---

## 📄 License

This project is released under the [MIT License](LICENSE).
