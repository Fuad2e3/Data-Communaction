# 🛡️ BitGuard: Error Detection & Correction Toolkit

<p align="center">
  <b>A comprehensive toolkit for visualizing and calculating Error Detection and Correction algorithms in Data Communication.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%20%7C%20Desktop-green?style=for-the-badge&logo=android" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Java-orange?style=for-the-badge&logo=java" alt="Language">
  <img src="https://img.shields.io/badge/UI-JavaFX-blue?style=for-the-badge" alt="UI">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
</p>

---

## 🚀 Overview

**BitGuard** is a powerful, user-friendly desktop application designed to help students and professionals understand the core concepts of data communication. It provides interactive modules for various error detection and correction techniques, ensuring data integrity across networks.

## ✨ Key Features

-   **Cyclic Redundancy Check (CRC):** Calculate and verify CRC codes with custom polynomials.
-   **Hamming Code:** Generate and correct Hamming codes for single-bit error detection and recovery.
-   **Checksum:** Implement traditional checksum algorithms to validate data packets.
-   **Bit Stuffing:** Visualize the bit stuffing process used in data link layer framing.
-   **Interactive UI:** A clean, modern interface built with JavaFX for an intuitive experience.

## 🛠️ Tech Stack

-   **Core:** Java 17
-   **UI Framework:** JavaFX
-   **Build Tool:** Maven
-   **Project Architecture:** MVC (Model-View-Controller)

## 📥 Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/fuadk/Data-Communaction.git
    cd Data-Communaction
    ```

2.  **Build the project:**
    ```bash
    mvn clean install
    ```

3.  **Run the application:**
    ```bash
    mvn javafx:run
    ```

## 📂 Project Structure

```text
Data-Communaction/
├── src/main/java/com/bitguard/
│   ├── controllers/  # UI Logic & Event Handling
│   ├── models/       # Data Structures & Algorithms
│   ├── helper/       # Utility Classes
│   └── bitguard/     # Main Application Entry
├── src/main/resources/com/bitguard/bitguard/
│   ├── fxml/         # UI Layouts
│   ├── styles/       # CSS Themes
│   └── images/       # Assets & Logos
├── pom.xml           # Maven Configuration
└── LICENSE           # MIT License
```

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

See `CONTRIBUTING.md` for more details.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>Data Communication | Green University of Bangladesh</i>
</p>
