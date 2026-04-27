# 🛡️ Cloud Log Monitoring System

A **real-time cloud-based log monitoring system** that simulates enterprise-level logging, detects anomalies, and visualizes system activity through an interactive dashboard.

---

## 🚀 Features

* ⚡ **Real-time log streaming**
* 📄 **Manual + Auto log generation**
* 🔍 **Search & filtering (level + service)**
* 🧠 **Smart alert detection (error spike in last 60 seconds)**
* 📊 **Analytics dashboard (charts & metrics)**
* 🧩 **Service-wise log breakdown**
* ☁️ **Cloud backend using Firebase (Firestore + Auth)**
* 🌐 **Live deployment via GitHub Pages**

---

## 🧱 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend (Cloud):** Firebase Firestore, Firebase Authentication
* **Visualization:** Chart.js
* **Hosting:** GitHub Pages

---

## 🧠 System Architecture

```
Browser (Frontend UI)
        ↓
Firebase SDK (JS)
        ↓
Firebase Authentication
        ↓
Firestore Database (Logs Storage)
        ↓
Dashboard Visualization (Charts + Alerts)
```

---

## 📊 How It Works

1. Logs are generated manually or automatically
2. Logs are stored in **Firestore (cloud database)**
3. Dashboard fetches logs in real-time
4. Logs are filtered, analyzed, and visualized
5. Alerts trigger when multiple errors occur in a short time

---

## 📁 Log Structure

```json
{
  "logId": "LOG-4821",
  "message": "SQL injection attempt blocked",
  "level": "ERROR",
  "service": "Firewall",
  "ip": "185.234.72.21",
  "timestamp": "..."
}
```

## 🌐 Live Demo

```
https://jatinjayasimha.github.io/cloud-log-monitoring-system/
```

---

## 🛠️ Setup & Run Locally

1. Clone the repository

```
git clone https://github.com/JATINJAYASIMHA/cloud-log-monitoring-system.git
```

2. Open project folder

3. Run using Live Server (VS Code recommended)

---

## 🔐 Firebase Setup

* Create a Firebase project
* Enable:

  * Firestore Database
  * Authentication (Anonymous)
* Add your Firebase config in both files:

  * `index.html`
  * `dashboard.html`

---

## 💡 Key Highlights

* Implements **real-time data flow without a traditional backend server**
* Demonstrates **cloud-native architecture**
* Simulates **security monitoring systems (SIEM-like behavior)**
* Includes **basic anomaly detection logic**

---

## 🎯 Use Cases

* System monitoring
* Cybersecurity log analysis
* DevOps observability
* Learning cloud-based architectures

---

## 🚀 Future Improvements

* 📧 Email alerts
* 🌍 IP geolocation tracking
* 📈 Time-series analytics
* 🔐 Role-based access control


Give it a ⭐ on GitHub!
