# Smart Public Transportation System - User Mobile App

A React Native mobile application for passengers to track buses in real-time, get optimized route suggestions, and use one-tap payments for fare. Part of the Smart Public Transportation System (SPTS) project integrating IoT, ML, and web dashboards.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Setup and Installation](#setup-and-installation)  
- [Running the App](#running-the-app)  
- [Folder Structure](#folder-structure)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## Project Overview

This mobile app allows passengers to:  
- View live bus locations on a map  
- Get route suggestions optimized by ML models for cost, time, and walking distance  
- Scan QR codes to check in/out of buses  
- Pay fares quickly with one-tap payment integration  
- View trip history and receive notifications about bus arrivals or delays

The app connects with backend services and IoT modules installed in buses.

---

## Features

- Real-time GPS tracking with interactive maps  
- Multiple route options with fare and ETA estimates  
- QR/NFC based boarding and exit system  
- One-tap payment integration with popular wallets and cards  
- Push notifications for route updates and alerts  
- Trip history with fare receipts  
- User profile management  

---

## Tech Stack

- **React Native CLI** for mobile development  
- **React Native Maps** for map visualization  
- **React Native QR Code Scanner** for boarding check-in/out  
- **Payment Gateway APIs** (e.g., eSewa, Khalti, Google Pay)  
- **Backend APIs** (Flask + Node.js) for ML-powered routing and fare calculation  
- **IoT Modules** (ESP8266/ESP32 + GPS + QR/NFC readers) for bus tracking and passenger check-in  

---

## Setup and Installation

### Prerequisites

- Node.js (v16 or above recommended)  
- Java JDK 11+  
- Android Studio (for Android SDK and emulator)  
- React Native CLI installed globally  
- Android device or emulator

### Clone the Repository

```bash
git clone https://github.com/yourusername/spts-user-app.git
cd smtp
