
# Smart Public Transportation System (SMTP)

A full-stack, IoT-enabled, ML-powered smart public transport management system designed to modernize city transit by enabling real-time tracking, optimized routing, seamless fare payments, and centralized management.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [System Components](#system-components)  
- [Features](#features)  
- [Technology Stack](#technology-stack)  
- [Architecture](#architecture)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [Future Enhancements](#future-enhancements)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## Project Overview

SMTP aims to improve public transportation efficiency and user experience by leveraging IoT devices on buses, machine learning algorithms for route and fare optimization, and web/mobile applications for all stakeholders. Passengers get real-time tracking, route suggestions, and one-tap payment; companies manage fleets effectively; admins oversee city-wide operations.

---

## System Components

### 1. Passenger Mobile App (Android)  
- Real-time bus tracking and live maps  
- ML-powered route suggestions based on fare, time, and walking distance  
- QR/NFC boarding and exit system  
- One-tap fare payment integration (eSewa, Khalti, Google Pay, etc.)  
- Trip history, notifications, and receipts  

### 2. Transportation Company Dashboard (Web)  
- Fleet management (add/remove buses, assign drivers)  
- Route and schedule planning  
- Analytics dashboard (ridership, revenue, occupancy)  
- IoT device health monitoring and alerts  

### 3. Central Admin Dashboard (Web)  
- City-wide monitoring of multiple companies and routes  
- Approval and management of new routes and operators  
- ML model training and deployment for dynamic routing/fare  
- System health and IoT device oversight  

### 4. IoT Hardware Modules  
- GPS tracking via Neo-6M GPS modules  
- ESP8266/ESP32 microcontrollers for communication  
- QR/NFC readers for passenger boarding validation  
- Optional passenger counting sensors (ultrasonic, vibration)  
- Onboard displays for drivers/passengers  

### 5. Optional Driver Mobile App  
- Trip start/end management  
- Live route updates and navigation  
- Issue reporting (breakdowns, delays)  
- Shift and earnings tracking  
- Company communication channel  

---

## Features

- Accurate, real-time bus location tracking  
- Machine learning for personalized, optimized route suggestions  
- Dynamic fare calculation with one-tap payment checkout  
- Offline caching for unreliable network areas  
- Notifications and alerts for users and operators  
- Multi-role access control (Passenger, Driver, Company, Admin)  

---

## Technology Stack

| Component                   | Technology / Framework                |
|----------------------------|-------------------------------------|
| Mobile App                 | React Native CLI          |
| Web Dashboards             | Next.js (React)                      |
| Backend API                | Flask (Python) + Node.js             |
| Database                   | PostgreSQL + Redis (cache)           |
| IoT Devices                | ESP8266/ESP32, Neo-6M GPS, sensors  |
| Communication Protocol     | MQTT / HTTP                         |
| Mapping API                | Google Maps Platform / OpenStreetMap |
| Payment Gateways           | eSewa, Khalti, Google Pay, Apple Pay|
| ML Frameworks              | TensorFlow, scikit-learn, or PyTorch |
| CI/CD (optional)           | GitHub Actions, Docker              |

---

## Architecture

![SMTP Architecture Diagram](docs/architecture.png)  
*Diagram illustrating the flow between Passenger App, IoT devices on buses, backend services, ML modules, payment gateway, and web dashboards.*

---

## Installation & Setup

### Prerequisites

- Node.js (v16+)  
- Java JDK 11+  
- Android Studio (for Android SDK and emulator)  
- Python 3.8+ and pip for backend  
- PostgreSQL and Redis installed  
- MQTT broker setup (e.g., Mosquitto)  
- Payment gateway accounts (eSewa, Khalti, etc.)

### Backend Setup

1. Clone the repo and navigate to backend folder  
2. Create a virtual environment and activate it  
3. Install dependencies: `pip install -r requirements.txt`  
4. Configure `.env` file with database and API keys  
5. Run backend services:  
   ```bash
   flask run
   node server.js
   ```

### Mobile App Setup

1. Navigate to the mobile app folder  
2. Install dependencies: `npm install`  
3. Run on emulator or device:  
   ```bash
   npx react-native run-android
   ```

### Web Dashboards Setup

1. Navigate to web dashboard folders (`company-dashboard`, `admin-dashboard`)  
2. Install dependencies: `npm install`  
3. Run development server:  
   ```bash
   npm run dev
   ```

---

## Usage

- Passengers install the mobile app to track buses and pay fares.  
- Companies use their dashboard to manage routes and fleets.  
- Admins monitor overall city transit operations.  
- IoT devices installed in buses provide real-time data for tracking and fare calculation.

---

## Future Enhancements

- Add multi-modal transport integration (metro, bike sharing)  
- AI-powered chatbot for passenger assistance  
- Driver app full rollout for operational communication  
- Real-time passenger occupancy analytics with advanced sensors  
- Enhanced ML models for predictive maintenance and dynamic pricing

---

## Contributing

Contributions are welcome! Please fork the repo, create feature branches, and submit pull requests. Report issues and suggest features via GitHub Issues.

---

## License



---

## Contact

**Shoumant Khadka**  
Email: np03cs4s240193@heraldcollege.edu.np  
GitHub: [https://github.com/Shoumant201/SMTP.git]

---

*Thank you for checking out the Smart Public Transportation System!*
