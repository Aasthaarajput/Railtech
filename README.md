# 🚆 RailTech – IoT-enabled Railway Wagon Load Monitoring System  

## 📌 Overview  
RailTech is an **IoT-based railway wagon load monitoring system** designed to improve **safety, efficiency, and logistics** in railway freight operations.  
It uses a **5kg load cell + HX711 amplifier** to measure load, processes the data with an **Arduino UNO & ESP32**, and displays it on an **LCD screen**.  
The system can also transmit data to IoT platforms for **real-time monitoring and predictive analytics**.  

---

## 🎯 Objectives  
- Prevent **overloading accidents** by real-time monitoring of wagon loads.  
- Enable **efficient freight management** with accurate load data.  
- Provide **IoT/cloud integration** for centralized monitoring.  
- Reduce **manual inspection** and improve operational safety.  

---

## ⚙️ Working Principle  
1. A **load cell (5kg)** senses the applied load from the wagon.  
2. The signal is amplified using an **HX711 module**.  
3. **Arduino UNO** processes the load cell output.  
4. **ESP32** enables wireless IoT data transfer.  
5. Weight is shown on a **16x2 LCD** and can be uploaded to cloud dashboards.  

---

## 🛠️ Hardware Components  
- Arduino UNO  
- ESP32 Wi-Fi Module  
- HX711 Load Cell Amplifier  
- 5kg Load Cell  
- 16x2 LCD Display  
- LED Indicator  
- Cardboard Railway Wagon Model (with coal demo load)  

---

## 🖥️ Software & Libraries  
- **Arduino IDE**  
- HX711 Arduino Library  
- LiquidCrystal Library  
- Wi-Fi / MQTT / ThingSpeak (for IoT integration)  

---

## 📊 Applications  
- Freight wagon **overload prevention**  
- **Supply chain monitoring** for railway cargo  
- **Real-time tracking** of wagon loads  
- Preventive safety against **derailments and theft**  

---

## ✅ Advantages  
- Real-time wagon load monitoring  
- Reduces accidents due to overloading  
- IoT-enabled for smart railway infrastructure  
- Cost-effective and scalable  

---

## ⚠️ Limitations  
- Prototype load cell capacity limited to **5kg**  
- Requires industrial-grade sensors for deployment  
- Internet/GSM coverage required for IoT mode  

---

## 🚀 Future Scope  
- Cloud dashboard + Mobile App integration  
- **AI/ML-based predictive analytics**  
- High-capacity industrial-grade load cells  
- Integration with **Railway ERP systems**  

---

## 📷 Project Demo  
- Cardboard wagon filled with coal acting as load.  
- **Load cell mounted below** the wagon.  
- Arduino + ESP32 + LCD setup displaying weight.  

---

## 👤 Contributors  
- **Your Name** – Design, Hardware Implementation, IoT Integration  
