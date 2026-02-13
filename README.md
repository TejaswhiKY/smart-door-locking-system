🔐 Arduino Smart Door Lock System

A password-based smart door locking system built using Arduino Uno.
This project allows users to register a secure PIN and unlock the door using a keypad. The system provides real-time feedback through an LCD display and controls a servo motor to simulate door locking and unlocking.


🚀 Features

🔑 First-time PIN registration

💾 PIN stored securely using EEPROM

🔒 Password-protected unlocking system

❌ Maximum 5 incorrect attempts limit

📟 16x2 LCD display for system status

🔁 Servo motor controlled locking mechanism

🔐 Automatic lock after unlocking



🛠️ Components Used

🔹 Arduino Uno

🔹 4x4 Matrix Keypad

🔹 I2C 16x2 LCD Display

🔹 Servo Motor (SG90)

🔹 Buzzer

🔹 Jumper Wires

🔹 Breadboard

🔹 USB Cable


📟 I2C LCD Connections

| LCD Pin | Arduino Uno Pin |
| ------- | --------------- |
| GND     | GND             |
| VCC     | 5V              |
| SDA     | A4              |
| SCL     | A5              |


⌨️ 4x4 Keypad Connections


| Keypad Pin | Arduino Uno Pin |
| ---------- | --------------- |
| Pin 1      | 9               |
| Pin 2      | 8               |
| Pin 3      | 7               |
| Pin 4      | 6               |
| Pin 5      | 5               |
| Pin 6      | 4               |
| Pin 7      | 3               |
| Pin 8      | 2               |


🔐 Servo Motor Connections


| Servo Wire             | Arduino Uno Pin |
| ---------------------- | --------------- |
| Red (VCC)              | 5V              |
| Brown/Black (GND)      | GND             |
| Orange/Yellow (Signal) | 10              |

🔊 Buzzer Connections


| Buzzer Pin   | Arduino Uno Pin |
| ------------ | --------------- |
| Positive (+) | A0              |
| Negative (–) | GND             |


⚙️ Working Principle

🔹 The system initializes and displays a welcome message on the LCD.

🔹 The user enters a 4-digit PIN using the keypad.

🔹 The Arduino compares the entered PIN with the stored password.

🔹If correct:

  Servo rotates to unlock the door

  LCD displays "Access Granted"

🔹 If incorrect:

   Buzzer activates

  LCD displays "Wrong Password"
  
 🔹 After multiple incorrect attempts, the system temporarily blocks access.

 

🔮 Future Improvements

🔹 Add fingerprint sensor for biometric security

🔹 Add RFID card authentication

🔹 Mobile app control using Bluetooth/Wi-Fi

🔹 Add real-time clock (RTC) for time-based access logs

🔹 Cloud-based monitoring system


🎯 Applications

🔹 Home security systems

🔹 Office door access control

🔹 Locker security

🔹 Safe box protection

🔹 Educational embedded system projects

🧪 Simulation Platform

🔹Tinkercad Circuits


📌 Click on below link for simulation or copy link and paste in browser to think this 👇

     https://www.tinkercad.com/things/eEUOK7cjzgo-smart-door-locking-system
