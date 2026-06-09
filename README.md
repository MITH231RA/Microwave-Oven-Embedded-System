# Microwave Oven Embedded System

## 📌 Project Overview

This project simulates the working of a Microwave Oven using a PIC Microcontroller and Embedded C. The system provides a user-friendly interface through a Matrix Keypad and CLCD display, allowing users to select cooking modes, set cooking time, and monitor the cooking process.

---

## 🎯 Objectives

- Simulate the basic functionality of a microwave oven.
- Implement menu-driven navigation using a matrix keypad.
- Display system status and cooking information on a CLCD.
- Use timers and interrupts for accurate time management.
- Apply Embedded C concepts in a real-time application.

---

## 🛠 Hardware Requirements

- PIC Microcontroller
- CLCD (Character LCD)
- Matrix Keypad
- Power Supply

---

## 💻 Software Requirements

- MPLAB X IDE
- XC8 Compiler
- Embedded C

---

## ✨ Features

- Multiple microwave operating modes
- Time setting through keypad
- CLCD-based user interface
- Countdown timer functionality
- Interrupt-driven operation
- Menu-based navigation
- Real-time display updates

---

## 📂 Project Structure

```text
microwave_owen.X
│
├── main.c
├── micro_oven.c
├── micro_oven.h
├── clcd.c
├── clcd.h
├── matrix_keypad.c
├── matrix_keypad.h
├── timers.c
├── timers.h
├── isr.c
├── Makefile
└── nbproject/
```

## 🔄 Working Flow

1. System initializes peripherals.
2. User selects a cooking mode.
3. User enters cooking time through keypad.
4. Timer starts counting down.
5. Remaining time is displayed on CLCD.
6. On completion, the system indicates cooking completion.

---

## 📚 Concepts Used

- Embedded C Programming
- Interrupt Service Routines (ISR)
- Timer Programming
- Matrix Keypad Interfacing
- CLCD Interfacing
- State Machine Design
- Real-Time Embedded Systems

---

## 🚀 Future Enhancements

- Temperature control simulation
- EEPROM-based cooking presets
- Buzzer notification system
- IoT-based remote monitoring
- Touchscreen interface

---

## 👩‍💻 Author

**Mithra**

Engineering Student | Embedded Systems Enthusiast

GitHub: https://github.com/MITH231RA
