# Fırtına UAV - Hybrid Transformable Aerospace & Ground Vehicle

This repository contains the official final technical report and design documentation for **Fırtına UAV**, an innovative hybrid Unmanned Aerial Vehicle (UAV) and Unmanned Ground Vehicle (UGV) prototype developed for the **TUBITAK-TEKNOFEST International Unmanned Aerial Vehicle Competition**. 

The vehicle stood out as a **Finalist (Ranked 27th out of 144 teams)** for its transformable structure and covert tactical capabilities[cite: 1].

The complete engineering final report is available as: `Fırtına_UAV_Project.pdf`.

---

## 🎬 Project Demonstration

Click below to watch the hybrid UAV system in action, demonstrating its flight routines, ground vehicle conversion, and embedded data streaming operations:

[![Watch the Video](https://img.shields.io/badge/YouTube-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/watch?v=33fLI3wTVqc))

---

## 📌 Project Architecture & Capabilities

Fırtına UAV was engineered to fulfill demanding tactical intelligence operations by operating seamlessly across both aerial and terrestrial domains[cite: 1].

*   **Hybrid Transformation:** Utilizes a custom-engineered reductor motor system and servo-controlled mechanics to dynamically switch between flight and ground locomotion modes[cite: 1].
*   **Autonomous Avionics:** Programmed autonomous flight tracks, waypoint navigation, and emergency fail-safe landing routines using **Pixhawk** flight controllers configured via **Mission Planner**[cite: 1].
*   **Terrestrial Operations:** Driven via an **Arduino Nano** microcontroller handling chassis operations when transitioned into ground vehicle mode[cite: 1].
*   **Covert Intelligence & Surveillance:** Integrated an **ESP32-CAM** module concealed inside a functional prop (flower pot) to capture real-time audio and video feeds without detection[cite: 1].
*   **High-Performance Streaming Infrastructure:** Implemented a **Docker-based network system** to stream the live audiovisual payload feed back to the ground station interface under low latency[cite: 1].

---

## 📐 Mechanical & Hardware Engineering

*   **CAD Modeling:** Complete 3D assembly, aerodynamic structural balance, and mechanism stress evaluations were modeled using **SolidWorks 2023** and **AutoCAD Fusion 360**[cite: 1].
*   **System Integration:** Complex integration combining PWM signaling for multi-rotors, servo actuators for mechanical shifting, and custom power distribution boards.

<img width="776" height="690" alt="Ground Vehicle Mode" src="https://github.com/user-attachments/assets/55231b67-99b7-4624-abcd-08669660f3fb" />

<img width="828" height="691" alt="Air Mode" src="https://github.com/user-attachments/assets/ba16d7cb-3208-41b0-abeb-2acdd436b1a3" />



---

## 💻 Ground Station Interface (HMI)

The telemetry from the Pixhawk controller and the live covert camera feed from the ESP32-CAM are aggregated onto a specialized Ground Station Graphical User Interface (GUI)[cite: 1]. This interface tracks flight orientation parameters, GPS coordinates, and payload status simultaneously.

<img width="1223" height="691" alt="UAV Ground Station GUI" src="https://github.com/user-attachments/assets/d36df0be-e40b-4a17-b694-cfe39b3eb39b" />

---

📊 *This project highlights complex multi-disciplinary milestones across aerospace structures, embedded systems deployment, Docker networking, and mission-critical systems validation.*
