Smart Button Counter

📌 Project Description

I made this project by researching various online resources and combining different ideas to create a functional button counter. The Smart Button Counter is an embedded system that counts and displays the number of times a push button is pressed. The system incorporates debouncing to ensure accurate counting and displays the count on an LCD (16x2 with I2C module) or the Serial Monitor.

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

📟 How It Works

Button Debouncing: The interrupt ensures accurate counting by applying a debounce delay.

Counting Mechanism: The count is stored in buttonCount and updated on the Serial Monitor and LCD.

LCD Display (Optional): Displays the count using the LiquidCrystal_I2C library.

🔥 Features

Debounce Mechanism for accurate counting

Interrupt-based Button Handling

LCD & Serial Monitor Output

Arduino-Compatible & Easy to Build



📌 Future Improvements

Add EEPROM storage to retain count after a restart

Implement a reset button to clear the count

Display the count on an OLED display


