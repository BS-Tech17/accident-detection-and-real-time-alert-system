
---

## 🛠 Hardware
- Raspberry Pi 5 & Pi Camera  
- NodeMCU (ESP8266) ×2  
- GSM Module (SIM800/SIM900)  
- SIM Card, LED, Buzzer, Security Pole, Jumper Wires & Breadboard  

---

## ⚙️ Software
- Python 3.x, TensorFlow/Keras, OpenCV  
- MQTT Broker (Mosquitto)  
- Raspberry Pi OS, pySerial for GSM communication  

---

## 🔌 Pin Example
| Component | Raspberry Pi Pin |
|-----------|----------------|
| Pi Camera | CSI Port       |
| LED       | GPIO 17        |
| Buzzer    | GPIO 27        |
| NodeMCU   | GPIO 14/15     |
| GSM TX/RX | GPIO 10/9      |

---

## 🎯 Methodology
1. **Detection:** Pi-Camera captures frames; MobileNetV2 detects accidents.  
2. **Local Alert:** Red LED & buzzer activated.  
3. **Hospital Alert:** NodeMCU publishes MQTT alert; hospital acknowledges.  
4. **Emergency Contact:** Bystanders send license plate; GSM module notifies family.  
5. **Verification:** Accident image & Google Maps link emailed to hospital.

---

## 📊 Results
- **Detection Accuracy:** 92% on Kaggle *Car Crash Dataset (CCD)*  
- **MQTT Latency:** Near real-time  
- **False Positives:** Minimized via image verification & security pole system  

---

## 🚀 Future Scope
- YOLO-based vehicle recognition  
- Driver drowsiness detection  
- Federated learning for multi-sensor data  
- Hazard detection (floods, obstacles)  
- Mobile app for live notifications  

---

## 👩‍💻 Authors
- **Adityan Balakumar** — CSE(Hons.), IoT & Intelligent Systems, Manipal University Jaipur  
- **Bhoomika Saxena** — CSE(Hons.), IoT & Intelligent Systems, Manipal University Jaipur  
- **Dr. Usha Choudhary** — CSE(Hons.), IoT & Intelligent Systems, Manipal University Jaipur  

---

## 📂 Folder Structure
