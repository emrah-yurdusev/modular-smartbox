# 📦 Modular SmartBox

![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Desktop](https://img.shields.io/badge/Desktop-Qt-green)
![Language](https://img.shields.io/badge/Language-C%2B%2B-purple)
![Type](https://img.shields.io/badge/Project-IoT-success)

An IoT-based customizable smart desk assistant that helps users stay focused by displaying important information on a dedicated physical screen instead of requiring frequent smartphone usage.

Developed as a Software Engineering graduation project at the European University of Lefke.

---

## 🚀 Overview

Many people check their phones for simple information such as time, weather, or notifications while studying or working. This often leads to distractions caused by social media and other applications.

Modular SmartBox aims to solve this problem by providing a customizable desktop information display that remains visible on the user's desk at all times.

Users can design their own layouts through a desktop application without writing any code.

---

## ✨ Key Features

* Drag & Drop desktop interface
* Real-time synchronization
* ESP32-powered embedded system
* OLED display support
* JSON-based layout configuration
* Wi-Fi (TCP/IP) communication
* Serial (UART) communication
* Third-party API integration
* Fully customizable information widgets

---

## 🖥️ Desktop Control Center

The desktop application is developed using C++ and Qt Framework.

Users can:

* Add widgets using drag & drop
* Customize screen layouts
* Position modules freely
* Save layouts automatically
* Deploy layouts to SmartBox instantly

Supported modules:

* Clock
* Weather
* Temperature
* Custom API Data
* Future widget extensions

---

## 🔌 Hardware Architecture

The hardware system is built around:

* ESP32 Microcontroller
* I2C OLED Display

The ESP32 receives layout data from the desktop application and renders the information on the OLED display in real time.

---

## 🏗️ System Architecture

```text
Third Party APIs
        ↓
Qt Desktop Application
        ↓
JSON Layout Data
        ↓
Wi-Fi (TCP/IP) / Serial (UART)
        ↓
ESP32 Microcontroller
        ↓
OLED Display
```

---

## 🛠️ Technologies Used

### Software

* C++
* Qt Framework
* JSON
* Arduino IDE

### Hardware

* ESP32
* OLED Display (I2C)

### Communication

* Wi-Fi (TCP/IP)
* Serial Communication (UART)

---

## 🎯 Project Goals

* Reduce phone-based distractions
* Improve productivity while studying or working
* Provide a customizable information display
* Support real-time internet data
* Combine desktop software and embedded systems into a single platform

---

## 🚧 Project Status

Currently under development as a graduation project.

Planned future improvements:

* Pomodoro Timer Module
* Mobile Companion Application
* Battery Support
* Audio Notifications
* Additional Widget Types

---

## 👨‍💻 Authors

**Emrah Yurdusev**
Software Engineering Student

**Muhsin Güreşçioğlu**
Software Engineering Student

European University of Lefke

Supervisor: **Cem Kalyoncu**
