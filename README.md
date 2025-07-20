# Simon Says Game: Interactive Memory Challenge

## 💡 Overview
This project implements the classic **" Simon Says" memory game**, a fun and challenging game designed to test and improve short-term memory and pattern recognition. It's built for **ESP32** and can be easily simulated using **Wokwi**. Players must remember and replicate a sequence of blinking LEDs and corresponding musical tones.

## ✨ Features
* **Dynamic Sequence Generation:** Generates random sequences of up to **100 steps**, ensuring a fresh and challenging experience with every game.
* **Engaging Visual & Audio Feedback:** Utilizes **4 colored LEDs** (Red, Green, Blue, Yellow) for visual cues and a **buzzer** for distinct musical tones corresponding to each LED.
* **Responsive Player Input:** Features **4 responsive push buttons** for players to input their sequence.
* **Score Tracking & Display:** Displays the current score (number of successful rounds) on a **two-digit 7-segment display**, controlled efficiently using **two 74HC595 shift registers**.
* **Level Progression Sounds:** Distinct musical tones indicate successful completion of a round and game over.
* **Efficient Pin Management:** Leverages the 74HC595 shift registers to minimize the number of microcontroller pins required for the display.

## ⚙️ Components Used
* **Microcontroller:** ESP32-C3-DevKitM-1
* **LEDs:** 4 x 5mm LEDs (Red, Green, Blue, Yellow)
* **Input:** 4 x Tactile Push Buttons
* **Audio:** 1 x Buzzer
* **Display:** 2 x Common Cathode 7-Segment Displays
* **Logic ICs:** 2 x 74HC595 Shift Registers
* **Other:** Resistors (220 Ohm), Breadboard, Jumper Wires

## ⚡️ Circuit Diagram & Simulation
You can view and simulate this project directly on **Wokwi**.

* **Wokwi Project Link:** https://wokwi.com/projects/431723042519787521

  **Screenshot of Circuit:**
  
  <img width="794" height="487" alt="image" src="https://github.com/user-attachments/assets/0fdb7358-dfe2-4991-a3d5-a5b432082ef0" />
