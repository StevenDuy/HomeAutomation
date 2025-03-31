# 🏠 IoT Home Automation Project

## 🌟 Overview
This project is an **IoT-based home automation system** that integrates multiple sensors and an **RGB LED** to automate lighting based on sound, motion, and ambient light conditions. Developed using **Arduino**, this smart system enhances **energy efficiency, convenience, and security** in modern homes. This project is an **open-source** academic work designed to explore IoT concepts and applications.

## 🔥 Key Features
✅ **Sound-based LED Control** – Turn lights ON/OFF with a simple clap.  
✅ **Motion Detection** – Detects movement and triggers LED blinking.  
✅ **Light Sensor Adjustment** – Automatically adjusts LED brightness.  

## 🔧 Hardware Components
- **🖥️ Arduino Uno** – Microcontroller for processing sensor data.
- **🎤 KY-037 Sound Sensor** – Detects sound signals for LED toggling.
- **👁️ PIR HC-SR501 Motion Sensor** – Detects movement for security and automation.
- **🌞 LM393 Light Sensor** – Adjusts LED brightness based on ambient light.
- **🌈 RGB LED** – Provides visual feedback based on sensor inputs.

## 🛠️ Circuit Wiring
- **🎤 Sound Sensor:** DO → D2, A0 → A1
- **👁️ Motion Sensor:** OUT → D3
- **🌞 Light Sensor:** A0 → A0, DO → A2
- **💡 RGB LED:** Red → D4, Green → D5, Blue → D6

## 💻 Software Requirements
- **Arduino IDE** – Required for writing and uploading the code.

## 🚀 Setup and Installation Guide
1. **Download and Install Arduino IDE**  
   - Visit: [🔗 Arduino Official Website](https://www.arduino.cc/en/software)
   - Download and install the latest version of **Arduino IDE**.

2. **Connect the Arduino Board**  
   - Use a **USB cable** to connect the **Arduino Uno** to your computer.

3. **Select the Board and Port**  
   - Open **Arduino IDE**.
   - Navigate to **Tools → Board → Arduino Uno**.
   - Go to **Tools → Port** and select the correct COM port.

4. **Upload the Code**  
   - Copy the project code into the **Arduino IDE**.
   - Click **Verify** to check for errors.
   - Click **Upload** to transfer the code to the **Arduino board**.

5. **Testing the System**  
   - **Clap** near the sound sensor to toggle the LED.
   - **Move** in front of the motion sensor to make the LED blink.
   - **Change lighting conditions** to see the LED brightness adjust automatically.

## 🎯 Expected Results
🔹 The LED turns **ON/OFF** when sound is detected.  
🔹 The LED **blinks** when motion is detected.  
🔹 The LED **brightness** changes dynamically based on ambient light.  

## 🛠️ Troubleshooting Guide
🔹 **LED does not respond to sound?**  
   - Ensure the **sound sensor** is properly connected and adjusted.
🔹 **Motion sensor not detecting movement?**  
   - Check the **sensor placement** and **sensitivity settings**.
🔹 **Light sensor not affecting LED brightness?**  
   - Ensure there are **significant lighting changes** and the wiring is correct.

## 🎓 Conclusion
This **IoT-based home automation system** offers a **smart, energy-efficient, and hands-free** lighting solution. By integrating **sound, motion, and light sensors**, it enhances **user convenience, home security, and power efficiency**. This project is part of an **academic study** exploring IoT technology in **real-world applications**.

## 🏅 Author
- **👨‍🎓 Hồ Hoàng Duy**  
- **🆔 Student ID:** BC00413  
- **📚 Course Code:** 7481  
- **🏫 Class Code:** SE07201  
- **🎓 Institution:** BTEC FPT Cần Thơ  

## 📜 License
This project is **open-source** and can be **modified and redistributed** under the **MIT License**.

Developed for **educational and automation purposes**. 🚀

