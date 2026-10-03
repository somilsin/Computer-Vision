[← Computer Vision](../README.md)

# 🇮🇳 Indian-ANPR (Automatic Number Plate Recognition)  

**Maintained by [Somil Singh](https://github.com/somilsin) — Software Engineer & AI Enthusiast**

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/) [![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)](https://opencv.org/) [![MySQL](https://img.shields.io/badge/Database-MySQL-orange?logo=mysql)](https://www.mysql.com/) [![Twilio](https://img.shields.io/badge/Notifications-Twilio-red?logo=twilio)](https://www.twilio.com/) [![AI](https://img.shields.io/badge/AI-Computer%20Vision-purple?logo=ai)]() [![Research](https://img.shields.io/badge/Focus-Research--Driven-yellow)]()  

---

## 📖 Repository Description

The Indian-ANPR (Automatic Number Plate Recognition) system is a research-driven project that combines Computer Vision, Database Systems, and Real-Time Notifications to automate vehicle compliance verification in the Indian context. Using  OCR (Optical Character Recognition) - pytesseract for license plate detection and recognition, the system extracts vehicle numbers from images and validates them against a MySQL registration database.

To enhance usability, the project integrates with Twilio, allowing authorities to track which users are registered and which are not through automated SMS notifications. This work demonstrates a practical application of AI and software engineering by bridging image processing, backend database design, and cloud-based communication APIs.

The project not only strengthened my expertise in AI frameworks and Python development, but also highlighted the role of integrated intelligent systems in real-world societal applications such as traffic enforcement and smart city solutions.

## 📂 Project Overview  

- 🚘 Developed a **vehicle details verification system** powered by **Computer Vision + Database Integration**.  
- 📸 Implemented a pipeline for **license plate detection & number extraction** from vehicle images.  
- 🔎 Connected extracted data with a **registration database** to validate:  
  - ✅ Owner details  
  - ✅ Vehicle model  
  - ✅ Registration/document validity  
- ⚠️ Built automated **alerts for expired or invalid registrations**.  
- 📲 Integrated **Twilio SMS notifications** to track which users are registered and which are not — enabling real-time compliance monitoring.  

---

## ⚙️ Tech Stack  

- **Python** → Core logic, ANPR pipeline  
- **OpenCV** → License plate detection & recognition  
- **MySQL** → Vehicle & user registration database  
- **Flask (optional for API)** → Backend integration  
- **HTML / CSS / JavaScript** → User interface  
- **Twilio** → SMS-based notification system  

---

## 🎯 Purpose  

- **Practical Application** → Apply **Computer Vision + Database Systems** to solve a real-world problem (vehicle compliance).  
- **Industry Relevance** → Demonstrates ability to integrate **AI-driven detection, database validation, and real-time communication systems**.  
- **Societal Impact** → Supports **traffic enforcement, safety, and monitoring of registered vehicles**.  

---

## 🧠 Next Steps  

- 🔬 Enhance ANPR accuracy using **deep learning (YOLO, CRNN)**.  
- 🌐 Deploy as a **cloud-based API** for smart city applications.  
- 📊 Build a **dashboard for authorities** to view compliance reports in real time.  
- 🚦 Expand to **traffic violation detection** (overspeeding, red-light jumping, etc.).  

---

## My local configuration

I run the Python and Node.js code from this project folder. My database password and Twilio settings come from environment variables. I set `MYSQL_PASSWORD`, `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN`, `TWILIO_FROM_NUMBER` and `TWILIO_TO_NUMBER` locally before starting the relevant program. I keep the actual values out of the repository.

The Python program can send text messages when executed. I configure the recipient and database for the environment I intend to use before running it.
