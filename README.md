# 🤖Arduino Wokwi Simulation Project - Potentiometer using Arduino🎚️

This repository contains an automated simulation project designed for an Arduino platform using Wokwi to read and display analog sensor data.

## ⚡ Live Simulation
You can run and test this project directly in your browser without any hardware.

👉 [Launch Live Simulation on Wokwi](https://wokwi.com/projects/467145759797836801)

## 🛠️ Project Components
* **`sketch.ino`**: The main code controlling the logic, reading the analog input, and transmitting the data via serial communication.
* **`diagram.json`**: The virtual circuit layout configuration, including connections between the Arduino Uno and the potentiometer.
* **`wokwi-project.txt`**: Project metadata for Wokwi integration.

## 📖 How to Run Locally
If you want to upload this code to a physical Arduino board

1. Download and install the **Arduino IDE**
2. Clone or download this repository
3. Open `sketch.ino` in the Arduino IDE
4. Connect your hardware components according to the layout described or viewed in the simulation (Potentiometer Outer Pins to `5V` and `GND`, Middle Pin to `A0`)
5. Select your board and port, then click **Upload**
6. Open the **Serial Monitor** (`Ctrl + Shift + M`) and set the baud rate to **9600** to see your live knob readings
