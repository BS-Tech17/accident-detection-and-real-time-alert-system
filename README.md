<h1 align="center">🚨 AI-Based Accident Detection & Real-Time Notification System</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Raspberry%20Pi-5-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Deep%20Learning-MobileNetV2-%230072C6?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IoT-MQTT-%2300C853?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/GSM-Alerts-%231E88E5?style=for-the-badge"/>
</p>

<hr/>

<h2>📌 Problem Motivation</h2>
<p>
Road accidents are one of the leading causes of fatalities worldwide. A major reason for these fatalities is the delay in emergency medical response due to the absence of automated, real-time accident detection and reporting systems.
</p>
<p>
This project aims to minimize the response time by automatically detecting road accidents using AI and instantly notifying nearby hospitals and the victim’s emergency contacts using IoT and GSM-based communication.
</p>

---

<h2>🧠 System Overview</h2>
<p>
This project presents an AI-based accident detection and real-time notification system that integrates deep learning, embedded systems, and IoT communication technologies.
</p>

<ul>
  <li>Accident detection using a CNN model based on MobileNetV2</li>
  <li>Real-time hospital alert using MQTT protocol</li>
  <li>Emergency contact notification using GSM (SMS + Call)</li>
  <li>Bystander-assisted vehicle identification using license plate reporting</li>
</ul>

---

<h2>🏗 System Architecture</h2>

<pre>
Pi Camera
    │
    ▼
Raspberry Pi 5
 (CNN Accident Detection)
    │
    ├──► LED + Buzzer (Local Alert)
    ├──► NodeMCU ── MQTT ──► Hospital NodeMCU
    ├──► GSM Module ──► SMS / Call (Emergency Contacts)
    └──► Email ──► Hospital (Image + Google Maps Location)
</pre>

<p><i>(Replace with an actual architecture diagram image if available)</i></p>

---

<h2>🛠 Hardware Requirements</h2>

<ul>
  <li>Raspberry Pi 5</li>
  <li>Pi Camera Module</li>
  <li>NodeMCU (ESP8266) – 2 Units</li>
  <li>GSM Module (SIM800 / SIM900)</li>
  <li>Active SIM Card</li>
  <li>LED Indicator</li>
  <li>Buzzer</li>
  <li>Push Button (Hospital Side)</li>
  <li>Power Supply & Connecting Wires</li>
</ul>

---

<h2>📦 Software & Technologies</h2>

<ul>
  <li>Python</li>
  <li>TensorFlow / Keras</li>
  <li>MobileNetV2 (Transfer Learning)</li>
  <li>OpenCV</li>
  <li>MQTT Protocol</li>
  <li>Arduino IDE</li>
  <li>GSM AT Commands</li>
  <li>Google Maps API</li>
</ul>

---

<h2>📊 Dataset Used</h2>

<p>
<b>Car Crash Dataset (CCD)</b><br/>
By Asef Jamil Ajwad (Kaggle)
</p>

<p>
The dataset consists of labeled accident and non-accident images and was used to train and validate the CNN-based accident detection model.
</p>

---

<h2>⚙️ Methodology</h2>

<h3>1️⃣ Data Collection & Model Training</h3>
<ul>
  <li>Accident images collected from Kaggle dataset</li>
  <li>Transfer Learning applied using pretrained MobileNetV2</li>
  <li>Model optimized for real-time inference on Raspberry Pi</li>
  <li>Achieved detection accuracy of <b>92%</b></li>
</ul>

<h3>2️⃣ Real-Time Accident Detection</h3>
<ul>
  <li>Pi Camera continuously monitors traffic</li>
  <li>Captured frames are analyzed by the CNN model</li>
  <li>Upon accident detection, LED and buzzer are activated</li>
</ul>

<h3>3️⃣ Emergency Notification System</h3>
<ul>
  <li>Accident alert sent to nearby hospital via MQTT</li>
  <li>Hospital staff acknowledge the alert using a push button</li>
  <li>Email with accident image and Google Maps location is sent</li>
</ul>

<h3>4️⃣ Victim Identification & Contact Alert</h3>
<ul>
  <li>Instructions displayed on a security pole near the accident site</li>
  <li>Bystanders send the vehicle license plate number via SMS</li>
  <li>Registered emergency contact is notified via SMS and call</li>
</ul>

---

<h2>🧪 Testing & Evaluation</h2>

<ul>
  <li>Model tested using unseen accident and non-accident images</li>
  <li>Evaluation metrics include accuracy, false positives, and false negatives</li>
  <li>MQTT latency and reliability analyzed</li>
  <li>System showed minimal end-to-end alert delay</li>
</ul>

---

<h2>📈 Results & Discussion</h2>

<p>
The system achieved an accident detection accuracy of <b>92%</b>, outperforming conventional threshold-based accident detection methods.
</p>

<ul>
  <li>Fast and reliable accident detection</li>
  <li>Instant hospital notification</li>
  <li>Reduced emergency response time</li>
</ul>

<p>
The results demonstrate the effectiveness of combining AI and IoT technologies for real-time emergency response systems.
</p>

---

<h2>🚀 Future Scope</h2>

<ul>
  <li>Integration of vibration and sensor-based detection</li>
  <li>Improved low-light and fog detection</li>
  <li>YOLO-based vehicle identification</li>
  <li>Federated learning for privacy-preserving training</li>
  <li>Smart city and traffic management integration</li>
</ul>

---

<h2>🏅 Key Contributions</h2>

<ul>
  <li>AI-powered real-time accident detection</li>
  <li>Edge deployment on Raspberry Pi 5</li>
  <li>MQTT-based hospital alert mechanism</li>
  <li>GSM-based emergency notification system</li>
  <li>Bystander-assisted victim identification</li>
</ul>

---

<h2>👩‍💻 Made By</h2>

<p>
<b>Bhoomika Saxena & Adityan Balakumar</b><br/>
B.Tech — Computer Science (IoT & Intelligent Systems)<br/>
AI | Embedded Systems | IoT | Research & Innovation
</p>

---

