# Digital-Lock-System
A secure, Arduino-based smart lock system that uses a keypad for password authentication. The project replaces traditional lock-and-key mechanisms with a more modern, user-friendly, and tamper-resistant solution. Built with components like an Arduino Nano, 16x2 LCD, SG90 servo motor, and keypad input.
## 📌 Features

- Keypad-based access control
- Servo-controlled door locking
- LCD feedback interface
- Buzzer alarm for incorrect password attempts
- Countdown auto relocking
- Multiple lockout stages for multiple failed attempts

## 🛠️ Components Used

- Arduino Nano
- SG90 Servo Motor
- 16x2 LCD Display
- 3x4 Keypad
- 5V Buzzer
- Breadboard and Jumper Wires

## ⚙️ Working Logic

1. User inputs password via keypad.
2. Password is verified by the Arduino.
3. If correct: servo unlocks the door, buzzer signals success.
4. If incorrect: buzzer triggers alert.
5. Lockout timer activates after repeated wrong attempts.

## ✅ Input & Output

| Input Type        | Value |
|-------------------|-------|
| Correct Password  | 1     |
| Incorrect Password| 0     |

| Output Type       | Value |
|-------------------|-------|
| Door Unlocked     | 1     |
| Door Locked       | 0     |
| Buzzer Triggered  | 1     |
| Buzzer Silent     | 0     |

## 🧠 Truth Table

| P (Password) | D (Door) | B (Buzzer) |
|--------------|----------|------------|
| 0            | 0        | 1          |
| 1            | 1        | 1          |

## ➕ Future Enhancements

- Biometric authentication (fingerprint, voice)
- Mobile app integration
- User management system
- Encrypted communication
- Real-time alerts and tamper detection
- Smart home ecosystem integration

