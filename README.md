# 🚑 ReviveConnect

ReviveConnect is a disaster-resilient communication application designed to enable connectivity when traditional networks fail.

## 🔥 Problem
During natural disasters (earthquakes, floods, cyclones), cellular networks often go down, leaving people unable to communicate or request help.

## 💡 Solution
ReviveConnect uses **Bluetooth + Wi-Fi (Nearby Connections API)** to create a **peer-to-peer offline network**, allowing devices to communicate directly without internet.

## ⚙️ Features
- 📡 Offline device discovery using Bluetooth & Wi-Fi
- 🔗 Peer-to-peer connection (Nearby Connections API)
- 💬 Real-time messaging between nearby devices
- 🚨 SOS communication support
- 🔁 Works without cellular network or internet

## 🛠️ Tech Stack
- Kotlin (Android)
- Google Nearby Connections API
- Bluetooth & Wi-Fi Direct

## 🚀 How it Works
1. Devices advertise and discover nearby peers
2. Connection is established automatically
3. Messages are exchanged directly between devices
4. Communication continues even without internet

## 🎯 Future Improvements
- Mesh networking (multi-hop communication)
- Location sharing (GPS-based rescue)
- Event-driven activation (auto-trigger during disasters)
- Cloud sync when internet is restored

## 📌 Use Cases
- Disaster management & rescue operations
- Remote area communication
- Emergency communication backup system

---

> ⚡ Built as a step toward resilient communication systems for real-world emergencies.
