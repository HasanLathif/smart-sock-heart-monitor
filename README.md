# Electrical System Design for a Remote Infant Heart Health Monitor

**Tags:** `Hardware`, `IoT`, `C++`, `ESP32`, `Sensor Integration`, `Project Report`

> The complete electrical system design for a "Smart Sock" to remotely monitor infant heart health, serving as a Biomedical Engineering Research Project.

---
<img width="618" height="474" alt="Image" src="https://github.com/user-attachments/assets/60d80645-a26f-49e1-9bf2-5db4c5e2527b" />

## 1. The Problem

Monitoring the vital signs of infants (especially heart rate and SpO2) is crucial for detecting conditions like sleep apnea or congenital heart defects. However, existing monitors are often unreliable, non-wearable, or not connected, causing significant anxiety for parents and caregivers.

## 2. My Solution

As my solo "Proyek Penelitian" (Research Project), I designed the complete **electrical and IoT system** for a remote infant heart health monitor, intended to be embedded in a wearable "Smart Sock."

The system is designed around an **ESP32** microcontroller for its Wi-Fi capabilities. It integrates a **MAX30102** sensor to read Photoplethysmography (PPG) signals, from which heart rate and SpO2 are calculated. The ESP32 processes this data and transmits it to a remote server or application, allowing for real-time alerts. This report covers the in-depth sensor selection, component justification, system architecture, and circuit design.

## 3. My Role & Key Contributions

I was the **Sole Researcher and Designer** for this project.

* Conducted in-depth research and comparison of various PPG sensors (e.g., MAX30102 vs. ADPD107).
* Selected the ESP32 as the optimal microcontroller for its processing power and IoT capabilities.
* Designed the complete system architecture, including the power management and sensor-to-MCU interface.
* Wrote the final, comprehensive 29-page research report detailing the entire electrical design process.

## 4. Technology Stack

* **Hardware (Proposed):** `ESP32`, `MAX30102` (PPG Sensor), `LiPo Battery`
* **Software:** `C++` (Arduino IDE), `PlatformIO`
* **Concepts:** `Wearable Technology`, `IoT`, `Biomedical Sensors`, `PPG Signal Processing`

## 5. Proof & Key Results

* **[Research Report]:** The complete 29-page final report detailing the sensor selection, system design, circuit diagrams, and analysis is located in this repository.
    * **[Laporan Proyek Penelitian Teknik Biomedik 2025_Hasan Abdul Lathif]**

## 6. Project Status

**Status: [Complete]**
*This research and design project was successfully completed for the Proyek Penelitian Teknik Biomedik course.*
