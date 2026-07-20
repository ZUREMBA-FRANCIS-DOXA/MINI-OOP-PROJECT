# Smart Device Management System

## Overview
This project is an OOP mini-project (Object Oriented Programming)**. It models a smart home management system where a technology company controls various smart devices — security cameras, smart lights, and temperature sensors — through a common interface.

## Task Summary
The program demonstrates the following OOP concepts:
- Classes and objects: a parent `SmartDevice` class and three child classes (`SecurityCamera`, `SmartLight`, `TemperatureSensor`)
- Inheritance: each child class inherits from `SmartDevice` and calls `super().__init__()`
- Encapsulation: `__device_id` and `__power_status` are private attributes, only modifiable through controlled methods (`turn_on()`, `turn_off()`) or validated `@property` setters
- Validation: device ID cannot be empty; light brightness is constrained to 0–100
- Menu-driven interface: a loop-based console menu lets the user display device info, power devices on/off, read temperature, adjust brightness, and start/stop recording

## Files
- `smart_device_management_system.py` — full source code

## How to Run
1. Make sure Python 3 is installed.
2. Clone this repository:
3. Run the program:
4. Follow the on-screen menu (options 1–7) to interact with the devices.

## Class Structure
```
SmartDevice (parent)
 ├── SecurityCamera  → recording_status, start_recording(), stop_recording()
 ├── SmartLight      → brightness, increase_brightness(), decrease_brightness()
 └── TemperatureSensor → temperature, read_temperature()
```

## Author
Submitted By — ZUREMBA FRANCIS AGORTINZOR, UMaT
