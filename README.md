# Servo Base Unit Mechatronics Project

📘 Project Overview

This project focuses on the design, modeling, and control of a Servo Base Unit as part of the Mechatronics and Robotics course (SPC 428).
The project incorporates component selection, hardware/software integration, system coding, 
and parameter estimation to build a robust servo system. The system utilizes Arduino, C programming, 
and Simulink to achieve precise position and velocity control of a linear cart system.

🚀 Key Features

Component Selection: Careful selection of key components such as DC motors, encoders, and motor drivers to meet system design requirements.

Hardware/Software Interface: Seamless integration of hardware components with software logic for real-time control.

System Coding: Development of control algorithms in C for Arduino to achieve cascaded PID control.

Performance Analysis: Analysis of system performance data to estimate and tune system parameters.


🛠️ Tools & Technologies

C Programming: For system control and logic development on Arduino.

Arduino: Acts as the microcontroller to execute system logic.

Simulink: Used for system modeling and parameter estimation.


🧪 Technical Approach

⚙️ Component Selection

DC Motor: Selected for precise control of linear cart movement.

Motor Driver (L298): Chosen to control DC motor speed and direction.

Encoder: Used for feedback on motor position and speed.

Limit Switch: Provides a home position reference for the system.

⚡ Hardware/Software Interface

Wiring Setup:

Motor Driver (L298): Interfaces with the DC motor and Arduino.

Arduino: Controls motor driver, encoder, and limit switch using I/O pins.

Encoder: Provides feedback on motor position and speed via interrupts.

Limit Switch: Signals the home position for position control.



