# Traffic-light-Control-Embedded
This project is a Traffic Light Control System designed for a four-way intersection using an Embedded System. 

It is developed in CCS C and simulated using Proteus. The system efficiently manages traffic signals using positive logic for two directions and negative logic for the other two directions.

Project Overview:
This project implements a traffic light control system for a 4-way intersection using an embedded system. The traffic lights are controlled using CCS C programming and simulated in Proteus.

Logic Design:
Two directions operate in positive logic (LED ON = High Logic).
Two directions operate in negative logic (LED ON = Low Logic).

Project Features:
✅ Embedded C (CCS Compiler) - Code written in C for microcontroller-based traffic light control.
✅ 4-Way Traffic Control - Manages lights in four directions with proper timing and synchronization.
✅ Positive & Negative Logic Implementation - Two directions work with HIGH = ON, while the other two work with LOW = ON.
✅ Proteus Simulation - Fully tested and simulated using Proteus for hardware accuracy.
✅ Timing Mechanism - Configurable delay system for red, yellow, and green signals.

Tools & Technologies:
Programming Language: Embedded C - For writing and compiling the embedded C program.
Development IDE: Code Composer Studio (CCS)
Microcontroller: MSP430 - Used to control traffic lights.
Simulation Software: Proteus Design Suite - For circuit simulation and validation.

Working Principle:
The microcontroller toggles the Red, Yellow, and Green LEDs in a cyclic manner.
Timers and delays are used to set appropriate durations for each signal.
The system is tested in Proteus with a virtual microcontroller and LEDs.

How to Run:
Open Code Composer Studio (CCS) and compile main.c.
Generate the .hex file and upload it to the Proteus microcontroller.
Load the Proteus simulation file and run the simulation.
Observe the traffic light sequence in the simulation.

Future Enhancements:
Sensor-based Traffic Control
Smart Traffic Management with IoT Integration
Adaptive Timings Based on Traffic Density

