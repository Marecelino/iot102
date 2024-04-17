# Smart Lock System with RFID and Keypad
![Smart Lock System]("C:\Users\Vagabond\Downloads\tinker.jpg")

## Overview

This project implements a smart lock system using an Arduino board, RFID technology, and a keypad. It allows users to unlock a door using either RFID cards or a keypad password.

## Contributors

- Nguyễn Viết Phong
- Nguyễn Trọng Thứ
- Nguyễn Thị Yến Vy

## Features

- Two default passwords are provided:
  - Password 1: 0000 (Stored in EEPROM address 10)
  - Password 2: 9999 (Stored in EEPROM address 100)
- Default RFID UID:
  - Master RFID UID: 0228581a
  - Second RFID UID: Stored from EEPROM address 500 onwards
- Menu Options:
  - Press D to enter password mode.
  - Press C to change the password.
  - Press B to add a second RFID card.
- Functionality in Main Menu:
  - Press D to return or exit.
  - Press * to clear all entered numbers in the password input mode.

## Dependencies

- EEPROMex
- EEPROMVar
- MFRC522
- Servo
- Keypad
- LiquidCrystal_I2C

## Hardware Requirements

●	Arduino Uno R3
●	Breathboard
●	RFID-RC522
●	Keypad
●	Button
●	Buzzer
●	Liquid Crystal LCD I2C
●	Servo
●	Pin 9v
●	Biến trở 0.25W 5% 330R


## Installation

1. Connect the hardware components as per the wiring instructions in the code.
2. Upload the provided Arduino sketch to your Arduino board.

## Usage

1. Power on the Arduino board.
2. Follow the menu options displayed on the LCD:
   - Press D to enter the password mode and enter the default password or a new password.
   - Press C to change the default passwords.
   - Press B to add a second RFID card.
3. Use the keypad to enter the password or hold an RFID card near the RFID reader to unlock the door.

## Contributing

Contributions to this project are welcome. Feel free to submit bug fixes, improvements, or new features through pull requests.

## License

This project is licensed under the [GROUP 9]
