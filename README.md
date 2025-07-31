
# ⚡ Advanced IDE-Based Fault Detection and Management for 2-Phase Transmission Lines

A real-time embedded system for detecting and managing faults in 3-phase transmission lines using Arduino and ESP32. The project aims to improve power system reliability through automated monitoring, fault isolation, and wireless data communication.

---

## 🚀 Features

- 🔍 **Real-time Fault Detection** with current/voltage sensors
- ⚙️ **Automated Fault Isolation** using relays and microcontroller logic
- 📡 **Wireless Communication** via ESP32 to send alerts or log data
- 🛠️ **Arduino IDE Development** for easy customization
- 📊 Optional IoT dashboard integration (Blynk, ThingSpeak, etc.)

---

## 🔧 Technologies Used

- Arduino UNO / Mega
- ESP32 Wi-Fi Module
- Voltage & Current Sensors (e.g., ACS712)
- Relay Modules
- Arduino IDE & Libraries

---


---

## 🧪 How It Works

1. **Sensors** detect abnormalities (overcurrent, voltage drop).
2. **Microcontroller** processes input and determines fault type.
3. **Relays** act to isolate faulty phase(s).
4. **ESP32** sends real-time status to remote dashboard or mobile app.

---

## 📦 Setup Instructions

1. Connect the sensors and relays as per the circuit diagram.
2. Upload `main_fault_detection.ino` to Arduino.
3. Upload `esp32_alert_module.ino` to ESP32 via Arduino IDE.
4. Monitor serial output or connect IoT dashboard for live data.

---

## 📈 Future Enhancements

- AI-based predictive fault analytics
- GPS tracking for distributed lines
- Mobile App for real-time notifications

---

## 📄 License

This project is open-source and available under the (SIMATS)(LICENSE).



