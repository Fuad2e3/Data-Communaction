<div align="center">

# 🛡️ BitGuard: Error Detection & Correction Toolkit
### **Interactive Data Communication & Network Framing Suite**

[![Platform](https://img.shields.io/badge/Platform-Desktop_JavaFX-blue?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjfx.io/)
[![Language](https://img.shields.io/badge/Language-Java_17-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![Build](https://img.shields.io/badge/Build-Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)](https://maven.apache.org/)
[![Course](https://img.shields.io/badge/Course-Data_Communication-8E75FF?style=for-the-badge)](https://green.edu.bd)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**A visual computing laboratory for calculating and simulating Layer 2 Data Link error detection and correction algorithms.**

---

[Explore Features](#-key-features) • [Project Structure](#-project-structure) • [Tech Stack](#-tech-stack)

</div>

---

## 📖 Overview
**BitGuard** is an interactive desktop application engineered using **JavaFX** and **Java 17**. Developed for the Data Communication course curriculum at **Green University of Bangladesh**, it provides an intuitive visual simulation of how digital signals, frames, and bit streams are validated against channel noise using classical encoding algorithms.

---

## ✨ Key Features

- 🔄 **Cyclic Redundancy Check (CRC):** Polynomial division calculating CRC-8, CRC-16, and custom generator polynomials with step-by-step XOR remainder traces.
- 🧮 **Hamming Code Generator & Corrector:** Matrix-based parity generation enabling single-bit error detection and automatic bit syndrome correction.
- 📦 **Internet Checksum Engine:** 16-bit one's complement addition simulating IPv4 and TCP segment header validation.
- ✂️ **Bit Stuffing & De-stuffing:** Framing layer simulator visualizing zero-bit insertion for continuous flag delimitation sequences (`01111110`).
- 🎨 **Modern JavaFX UI:** Fluid animations, responsive FXML layout components, and clean styling.

---

## 📁 Project Structure

```text
Data-Communaction/
├── src/main/java/com/bitguard/
│   ├── controllers/            # JavaFX Controller logic & event dispatchers
│   ├── models/                 # Algorithm implementations (CRC, Hamming, Checksum)
│   ├── helper/                 # Bitwise utilities & byte array formatters
│   └── bitguard/               # Main Application launcher
├── src/main/resources/com/bitguard/bitguard/
│   ├── fxml/                   # Declarative XML interface views
│   ├── styles/                 # Modern CSS themes
│   └── images/                 # Assets, university logos & UI badges
├── pom.xml                     # Maven dependency & plugin configuration
└── README.md                   # System documentation
```

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Language** | Java 17 (LTS) | Core application logic and bitwise manipulation |
| **GUI Framework** | JavaFX (OpenJFX 17) | Modern responsive desktop GUI with FXML |
| **Build Automation** | Apache Maven | Lifecycle management and dependency resolution |
| **Design Pattern** | MVC (Model-View-Controller) | Separation of mathematical algorithms from presentation |

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed ❤️ by Softece**

</div>
