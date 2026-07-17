Smart Device Management System
Introduction
This project is a Python-based Smart Device Management System built for the EL 162/234 Object Oriented Programming Mini Project. It simulates how a smart home application might manage different types of smart devices — a security camera, a smart light, and a temperature sensor — through a single unified interface.
Project Summary
The system is built around a parent class, SmartDevice, which defines shared attributes (device ID, power status, name) and behavior (turning on/off, displaying information) common to all smart devices. Three child classes inherit from SmartDevice and add their own specialized features:
SecurityCamera – can start and stop recording.
SmartLight – has adjustable brightness (0–100%).
TemperatureSensor – reports the current temperature.
Object-Oriented Concepts Demonstrated
Classes and Objects – each device type is a class; individual devices are objects.
Constructors (__init__) – used to initialize each device's attributes.
Inheritance – all three child classes inherit from SmartDevice using super().
Encapsulation – device_id and power_status are private attributes (__device_id, __power_status) and cannot be modified directly from outside the class.
Getters/Setters (@property) – used to safely access and validate private data (e.g., brightness must stay between 0 and 100).
Loops and Conditionals – used to drive the interactive menu system.
Functions and Methods – modular, reusable code for each device action.
How to Run the Program
Make sure Python 3 is installed on your computer.
Download or clone this repository.
Open a terminal in the project folder.
Run the program with:
Code
Follow the on-screen menu to interact with the devices:
Code
File Structure
Code
Author
Acheampomaa – University of Mines and Technology (UMaT)
