# 🚀 Arduino Wokwi Simulation Project - Potentiometer using Arduino

This repository contains an automated simulation project designed for an Arduino platform using Wokwi to read and display analog sensor data[span_0](start_span)[span_0](end_span).

## ⚡ Live Simulation
You can run and test this project directly in your browser without any hardware[span_1](start_span)[span_1](end_span)!

👉 [Launch Live Simulation on Wokwi](https://wokwi.com/projects/new/arduino-uno)

## 🛠️ Project Components
* **`sketch.ino`**: The main code controlling the logic, reading the analog input, and transmitting the data via serial communication[span_3](start_span)[span_3](end_span).
* **`diagram.json`**: The virtual circuit layout configuration, including connections between the Arduino Uno and the potentiometer[span_4](start_span)[span_4](end_span).
* **`wokwi-project.txt`**: Project metadata for Wokwi integration[span_5](start_span)[span_5](end_span).

## 📖 How to Run Locally
If you want to upload this code to a physical Arduino board[span_6](start_span)[span_6](end_span):

1. Download and install the **Arduino IDE**[span_7](start_span)[span_7](end_span).
2. Clone or download this repository[span_8](start_span)[span_8](end_span).
3. Open `sketch.ino` in the Arduino IDE[span_9](start_span)[span_9](end_span).
4. Connect your hardware components according to the layout described or viewed in the simulation (Potentiometer Outer Pins to `5V` and `GND`, Middle Pin to `A0`)[span_10](start_span)[span_10](end_span).
5. Select your board and port, then click **Upload**[span_11](start_span)[span_11](end_span).
6. Open the **Serial Monitor** (`Ctrl + Shift + M`) and set the baud rate to **9600** to see your live knob readings[span_12](start_span)[span_12](end_span).
