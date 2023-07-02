# Arduino-Safe-Lock

This repository contains the Arduino code for a protected door system using a keypad, LCD display, and a servo motor. The code allows users to enter a password to open and close the door securely.

## Features

- Enter a password using a keypad to open the door.
- Display messages and status on an LCD screen.
- Use a servo motor to physically open and close the door.
- Sound a buzzer in case of incorrect password entry.

## Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- Keypad
- LCD display (compatible with the LiquidCrystal library)
- Servo motor
- Buzzer (optional)

## Installation and Usage

1. Connect the keypad, LCD display, servo motor, and buzzer to the Arduino board according to the hardware setup instructions.
2. Open the Arduino IDE and create a new sketch.
3. Copy and paste the code from this repository into the sketch.
4. Upload the code to the Arduino board.
5. Open the Serial Monitor to view the system output (optional).
6. Follow the instructions on the LCD display to interact with the protected door system.

## Configuration

- `Password_Length`: Set the length of the password (default: 5).
- `Master`: Set the master password that allows access to the door (change the default password "A20B" to your desired password).
- `ROWS` and `COLS`: Set the number of rows and columns on the keypad (modify if using a different keypad).

## Contributing

Contributions to this project are welcome. Feel free to open issues or submit pull requests to suggest improvements or report bugs.
