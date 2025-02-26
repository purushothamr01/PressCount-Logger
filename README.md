Smart Button Counter

📌 Project Description

The Smart Button Counter is an embedded system that counts and displays the number of times a push button is pressed. The system incorporates debouncing to ensure accurate counting and displays the count on an LCD (16x2 with I2C module) or the Serial Monitor.

🛠️ Components Required

Arduino Uno

Push Button

10kΩ Resistor (Pull-down resistor)

16x2 LCD with I2C Module (Optional)

Jumper Wires

⚡ Circuit Connections

Push Button:

One side → Digital Pin 2

Other side → GND via a 10kΩ pull-down resistor

Also connected to 5V

LCD (16x2 with I2C) (Optional):

VCC → 5V

GND → GND

SDA → A4

SCL → A5
