# arduino-digital-door-lock
Arduino UNO digital door lock using servo, button, LEDs and buzzer.
# Arduino UNO Digital Door Lock

A simple Arduino UNO-based digital door lock system that demonstrates basic access-control functionality using a push button, servo motor, LEDs, and buzzer.

## Components

- Arduino UNO
- Servo Motor
- Push Button
- Green LED
- Red LED
- Buzzer
- 220Ω Resistors
- Breadboard
- Jumper Wires

## Pin Configuration

| Component | Arduino Pin |
|---|---|
| Push Button | D2 |
| Green LED | D6 |
| Red LED | D7 |
| Buzzer | D8 |
| Servo Signal | D9 |

## Working

- The red LED indicates that the door is locked.
- The push button is used to enter the predefined password through button presses.
- When the correct number of presses is detected, access is granted.
- The servo motor rotates to 90° to simulate unlocking the door.
- The green LED indicates successful access.
- After a predefined delay, the servo returns to 0°, locking the door again.
- An incorrect input triggers the buzzer and indicates access denial.

## Concepts Used

- Arduino UNO
- Digital Input and Output
- INPUT_PULLUP
- Servo Motor Control
- Conditional Statements
- LED Indication
- Buzzer Control
- Basic Access-Control Logic

## Future Improvements

- 4×4 Keypad password entry
- LCD/OLED display
- RFID authentication
- Multiple password support
- EEPROM-based password storage
- ESP32-based remote access control

##Demo-Video: ⏯️ "https://drive.google.com/file/d/1-MHfTirxpC9bUog--OsgLzJSjaokME2G/view?usp=drivesdk"

## Project Status

**Completed ✅**

**Platform:** Arduino UNO  
**Category:** Embedded Systems / Access Control
