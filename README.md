# HomeAutomation
# IoT Home Automation Project

## Overview
This project is designed to automate home lighting using an Arduino-based IoT system. It utilizes sound, motion, and light sensors to control an RGB LED, enhancing convenience, energy efficiency, and security.

## Features
- **Sound Activation:** Turn the LED on/off with a sound sensor.
- **Motion Detection:** LED blinks when motion is detected.
- **Light Sensitivity:** LED brightness adjusts based on ambient light.

## Hardware Requirements
- **Arduino Uno** – The main microcontroller.
- **KY-037 LM393 Sound Sensor** – Detects sound to toggle LED.
- **PIR HC-SR501 Motion Sensor** – Detects motion to trigger LED blinking.
- **LM393 Light Sensor** – Adjusts LED brightness based on light levels.
- **RGB LED** – Displays different lighting effects.
- **Jumper Wires** – For circuit connections.
- **Breadboard** – For prototyping connections.

## Wiring Instructions
- **Sound Sensor:** `DO → D2`, `A0 → A1`
- **Motion Sensor:** `OUT → D3`
- **Light Sensor:** `A0 → A0`, `DO → A2`
- **RGB LED:** `Red → D4`, `Green → D5`, `Blue → D6`

## Software Requirements
- **Arduino IDE** – Required to write and upload code to the Arduino.
- **Required Libraries** (If applicable, install via Arduino Library Manager)

## Installation Guide
1. **Download & Install Arduino IDE**
   - Download from the official website: [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)
   - Follow installation instructions for your OS.
2. **Connect the Arduino Board**
   - Plug the Arduino into your computer via a USB cable.
3. **Select the Board & Port**
   - Open Arduino IDE.
   - Go to `Tools > Board` and select **Arduino Uno**.
   - Go to `Tools > Port` and select the correct port for your Arduino.
4. **Upload the Code**
   - Open the `.ino` file containing the IoT Home Automation code.
   - Click on `Verify` (✔️) to compile the code.
   - Click on `Upload` (➡️) to upload it to the Arduino board.
5. **Test the System**
   - Ensure all sensors and LED connections are secure.
   - Observe responses to sound, motion, and light changes.

## Troubleshooting
- **Arduino not detected?** Try a different USB cable or port.
- **Code upload fails?** Ensure the correct board and port are selected.
- **LED not responding?** Check wiring and sensor functionality.

## Future Enhancements
- Integration with Wi-Fi for remote control.
- Mobile app interface for customization.
- Additional sensors for expanded automation.

## License
This project is open-source and can be modified and redistributed under the MIT License.

---
Developed for educational and automation purposes. 🚀

