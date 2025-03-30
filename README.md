# 🚀 **Smart Home Energy Management System using ESP32**

![ESP32](https://img.shields.io/badge/ESP32-IoT-blue) ![Blynk](https://img.shields.io/badge/Blynk-Integration-green) ![DHT22](https://img.shields.io/badge/Sensors-DHT22-orange)

## 🌟 **Project Overview**
The **Smart Home Energy Management System** is an IoT-based project using **ESP32**, **Blynk**, and **DHT22** to remotely monitor and control home appliances. It features:
- Remote appliance control via the **Blynk** app.
- Real-time **temperature and humidity** monitoring.
- **PIR motion detection** for security.
- **LCD display** with custom symbols to show system status.
- Energy-efficient home automation.

---

## 📷 **Project Demo**
🚀 **Simulation:** [Smart Home Energy Management](https://wokwi.com/projects/398558632512308225)  
📸 **Screenshots:**
- ![Blynk Dashboard](https://via.placeholder.com/400x200.png?text=Add+Dashboard+Image)
- ![LCD Display](https://via.placeholder.com/400x200.png?text=Add+LCD+Image)

---

## ⚙️ **Features**
- 🛠️ **Remote Appliance Control:** Turn appliances on/off using the Blynk app.  
- 🌡️ **Temperature & Humidity Monitoring:** Displays real-time readings on the LCD and Blynk app.  
- 🔥 **PIR Motion Detection:** Detects motion and activates lights.  
- 📊 **LCD Display:** Shows appliance status, temperature, and humidity with custom symbols.  
- 🌐 **Blynk Integration:** Remote access and control via WiFi.

---

## 🛠️ **Components Used**
| Component            | Description                 |
|----------------------|-----------------------------|
| ⚡ ESP32              | Microcontroller             |
| 🌡️ DHT22              | Temperature & Humidity Sensor |
| 🔌 Relay Module       | Controls appliances         |
| 🟢 PIR Sensor         | Motion Detection            |
| 🖥️ LCD (20x4 I2C)     | Display system status       |
| 🌐 Blynk App          | Remote control and monitoring |

---

## 🔧 **Circuit Diagram**
📐 *Include a schematic diagram image here.*  
![Circuit Diagram](https://via.placeholder.com/600x300.png?text=Add+Circuit+Diagram)

---

## 🔥 **How It Works**
1. **ESP32 Initialization:**
   - Connects to WiFi and Blynk cloud.
   - Initializes the **LCD** and **DHT22 sensor**.

2. **Blynk Controls:**
   - Switches (SW_1 to SW_5) control appliances.
   - PIR motion detection activates the LED.

3. **Temperature & Humidity Monitoring:**
   - Reads from the **DHT22** sensor.
   - Displays the values on the **LCD** and Blynk app.

---

## 🚀 **Getting Started**

### ✅ **Hardware Requirements**
- ESP32 board  
- DHT22 temperature & humidity sensor  
- PIR motion sensor  
- 5V relay module  
- 20x4 I2C LCD display  
- Jumper wires & breadboard  

### 🔧 **Software Requirements**
- **Arduino IDE** (or PlatformIO in VS Code)  
- **Blynk App**  
- **Wokwi Simulation** *(for virtual testing)*  

---

## ⚙️ **Installation and Usage**

1. **Clone the Repository:**
```bash
git clone https://github.com/Real-Time-IoT-project.git
cd Real-Time-IoT-project
```

2. **Install Dependencies:**
   - Install the following libraries in the **Arduino IDE**:
     - `Blynk`
     - `DHTesp`
     - `LiquidCrystal_I2C`

3. **Blynk Configuration:**
   - Create a new project in the **Blynk app**.
   - Add **5 buttons** for appliance control.
   - Add **2 labels** for temperature and humidity display.
   - Copy your **Blynk Auth Token** and update it in the code.

4. **Upload the Code:**
   - Connect the ESP32 board.
   - Upload the code to the board using the **Arduino IDE**.

5. **Run the Project:**
   - Open the Blynk app to control appliances.
   - View real-time temperature and humidity data.

---

## 🔥 **Blynk App Configuration**
- **Button Pins:**
  - SW_1 → V0  
  - SW_2 → V1  
  - SW_3 → V2  
  - SW_4 → V3  
  - SW_5 → V4  
- **Temperature Display:** V5  
- **Humidity Display:** V6  
- **PIR Sensor Indicator:** V7  

---

## 🔥 **Troubleshooting**
- **No LCD display?**
  - Check the I2C address and connections.
- **No WiFi connection?**
  - Verify your WiFi SSID and password.
- **Incorrect temperature/humidity readings?**
  - Ensure the DHT22 sensor is properly connected and powered.

---

## 📚 **References**
- [ESP32 Documentation](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/)  
- [Blynk Documentation](https://docs.blynk.io)  
- [Wokwi Simulator](https://wokwi.com)  

---

## 📜 **License**
This project is licensed under the **MIT License**.  
Feel free to modify and distribute the code with attribution.

---

## 👨‍💻 **Author**
👤 **Thillai Nirmal K**  
📧shanmugakannan7549@gmail.com
🌐 [GitHub Profile](https://github.com/thillainirmal-tech)

---

✅ This `README.md` is **detailed, professional, and clear**. It covers the project overview, features, installation steps, and circuit details effectively. Let me know if you need modifications or additional sections! 🚀
