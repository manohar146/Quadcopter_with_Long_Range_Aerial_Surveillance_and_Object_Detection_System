# Quadcopter_with_Long_Range_Aerial_Surveillance_and_Object_Detection_System
 This project,   “Quadcopter with Long Range Aerial Surveillance and Object Detection System,” aims  to design and implement a robust quadcopter equipped with an ESP32-CAM module for  efficient surveillance and detection. 
# 🛸 Quadcopter with Long Range Aerial Surveillance & Object Detection System

## 🚀 Overview  
This project showcases a custom-built quadcopter equipped with an **ESP32-CAM module** for real-time aerial surveillance and object detection. Designed for long-range communication and efficient image processing, it integrates **IoT**, **computer vision**, and **embedded systems** to deliver a scalable solution for modern monitoring needs.

## 🎯 Objectives  
- Develop a drone system with up to **200m range** using dual-band Wi-Fi antennas  
- Enable **real-time object detection** using YOLOv3 and OpenCV  
- Ensure **cost-effective**, modular design for educational and field use  
- Optimize for **energy efficiency** and stable flight control  
- Demonstrate applications in **security, agriculture, and disaster response**

## 🧠 System Architecture  
| Module                  | Role & Highlights                                      |
|------------------------|--------------------------------------------------------|
| **ESP32-CAM**          | Captures and streams video; runs detection algorithms  |
| **Python + OpenCV**    | Processes images on ground station using YOLOv3        |
| **APM 2.8 Controller** | Stabilizes flight and handles navigation                |
| **BLDC Motors + ESCs** | Provides propulsion and speed control                  |
| **Dual-Band Antenna**  | Extends Wi-Fi range up to 200m                         |
| **LiPo Battery (2200mAh)** | Powers the entire system for extended flight time     |

## 📸 Features  
- 📡 Long-range wireless video transmission  
- 🧠 Real-time object detection (YOLOv3)  
- 🔋 Efficient power management  
- 🛠️ Modular hardware for easy upgrades  
- 🌐 IoT-enabled remote monitoring

## 📂 Repository Contents  
- `objectdetection.py` – Python script for object detection  
- `Major_Project_report++.pdf` – Full technical documentation  
- `README.md` – Project overview and setup guide  
- `cam_pic*.png` / `Pic*.jpg` – Sample detection outputs  
- `Picture1.jpg` – Drone build snapshot

## 🛠️ Setup Instructions  
1. Flash ESP32-CAM with firmware and connect to Wi-Fi  
2. Run `objectdetection.py` with OpenCV installed  
3. Mount ESP32-CAM securely on drone  
4. Launch and monitor live feed via IP stream  
5. Tune detection parameters in Python as needed

## 📊 Results  
- Achieved stable video feed up to **150–200 meters**  
- Detected objects like **cars, bikes, and people** with high accuracy  
- Responsive flight control and real-time feedback  
- Identified challenges: vibration interference, frame rate lag, directional control

## 📌 Future Enhancements  
- Add GPS and autonomous navigation  
- Integrate thermal imaging for night surveillance  
- Upgrade to YOLOv8 for improved detection  
- Explore 5G-based communication modules

## 🧾 Credits  
Developed by:  
- Kiran Kumar T S (1MJ21EC058)  
- M Manohar Naik (1MJ21EC065)  
- Manjunatha Y E (1MJ21EC069)  
- Rahul Dixit (1MJ21EC107)  
Guided by: Prof. Anu Joy, MVJ College of Engineering

---

📬 Want help turning this into a GitHub Pages showcase with interactive visuals, chalkboard-style headers, or modal resume embeds? I’ve got ideas. Just say the word.
