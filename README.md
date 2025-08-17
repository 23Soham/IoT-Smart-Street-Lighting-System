# IoT-Smart-Street-Lighting-System

🌆 IoT Smart Street Lighting System
An IoT-powered Smart Street Lighting Solution designed to optimize energy consumption, improve urban safety, and enable real-time monitoring of streetlights using sensors, microcontrollers, and cloud-based data analytics.
📌 Project Overview
Traditional street lighting systems consume excessive energy and require manual monitoring. This project proposes an IoT-enabled Smart Street Lighting System that:
💡 Automatically controls streetlights based on ambient light and motion detection
⚡ Reduces energy wastage through adaptive dimming and intelligent control
🌐 Provides real-time monitoring and control via IoT cloud integration
🔒 Enhances safety by ensuring lights stay on when pedestrians/vehicles are detected
🏗️ System Architecture
<p align="center"> <img src="system-architecture.png" alt="System Architecture" width="700"/> </p>
(Replace system-architecture.png with the uploaded architecture diagram filename in your repo.)
⚙️ Components Used
Hardware: Arduino/ESP8266, LDR (Light Dependent Resistor), PIR Motion Sensors, LED Lamps, Relay Modules
IoT Platform: Blynk / ThingSpeak (for cloud monitoring)
Communication: Wi-Fi (ESP8266 NodeMCU)
Power Management: Relays and energy-efficient LED drivers
🚀 Features
🌙 Automatic Dimming: Lights dim when no movement is detected
🚶 Motion-Based Control: Streetlights brighten when vehicles/pedestrians pass
📡 IoT Monitoring: Real-time status and data logging via cloud dashboard
⚡ Energy Efficiency: Reduces unnecessary power consumption by up to 60%
🔧 Remote Control: Ability to override or schedule lighting manually
🔍 Methodology
Sensor Integration: LDR detects day/night, PIR detects motion
Microcontroller Processing: Arduino/ESP8266 processes sensor inputs
Smart Control Logic:
Lights ON when dark + motion detected
Lights DIM when dark + no motion
Lights OFF during daylight
IoT Connectivity: Sends sensor data & streetlight status to cloud dashboard
Visualization: Graphs & analytics for usage and performance monitoring
📊 Results
✅ Reduced Energy Consumption – achieved up to 60% energy savings compared to traditional systems
✅ Improved Safety – ensured well-lit streets only when needed
✅ Scalable Design – can be deployed city-wide with modular IoT nodes
🛣️ Future Enhancements
🔌 Integration with renewable energy sources (solar panels)
🤖 AI-based predictive maintenance for faulty streetlights
📍 GPS-enabled mapping for city-wide monitoring
🛰️ Integration with smart city platforms for holistic urban management


<img width="596" height="317" alt="Screenshot 2025-08-05 at 10 18 12 PM" src="https://github.com/user-attachments/assets/e0f7e8f5-74ae-479c-9486-fac7337e67a1" />

<img width="636" height="359" alt="Screenshot 2025-08-05 at 10 18 51 PM" src="https://github.com/user-attachments/assets/1a88c9ac-79c4-482c-9d2c-67ca1de6994a" />
