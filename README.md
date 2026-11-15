# AUTOSAR Cruise Control and Emergency Braking System

An academic automotive software project focused on implementing Cruise Control and Emergency Braking functionality using AUTOSAR Classic architecture and C programming.

The project explores software component design, vehicle speed monitoring, target speed management, braking-distance calculation, and communication through the AUTOSAR Runtime Environment (RTE).

## Project Overview

The objective of this project is to develop an AUTOSAR-based automotive software prototype that combines cruise control functionality with an emergency braking concept.

The software is organized into individual Software Components (SWCs), each responsible for a specific function.

The project documentation describes the use of Vector SystemDesk for the design phase and VEOS as the virtual simulation environment.

## Key Features

- Cruise Control functionality
- Target Speed Management
- Vehicle Speed Monitoring
- Accelerator and Brake Pedal Input Handling
- Emergency Braking Distance Calculation
- Accident Detection based on Acceleration Threshold
- Simplified Engine Control Logic
- AUTOSAR Runtime Environment (RTE) communication

## Technologies & Tools

| Technology | Purpose |
|---|---|
| C Programming | Software Component implementation |
| AUTOSAR Classic | Automotive software architecture |
| Vector SystemDesk | System and Software Component design |
| Vector VEOS | Virtual ECU simulation environment |
| AUTOSAR RTE | Communication between Software Components |

## Software Components

| Software Component | Responsibility |
|---|---|
| CruiseControlSWC | Cruise control logic and speed regulation |
| TargetSpeedControl | Target speed adjustment |
| EmergencyBrakeSWC | Braking-distance calculation and emergency braking logic |
| EngineControl | Simplified engine control and injection calculation |
| AccidentRecorder | Acceleration threshold monitoring and accident recording request |

## Project Architecture

The project follows a component-based software design approach.

Individual Software Components handle vehicle inputs, control decisions, and output signals through AUTOSAR RTE interfaces.

## Project Screenshots

Original project screenshots will be added here.

<!-- Add original SystemDesk and VEOS screenshots after uploading them to the images folder. -->

## Project Structure

## Project Structure

```text
AUTOSAR-Classic-Cruise-Control-Emergency-Braking/
│
├── images/
│   └── .gitkeep
│
├── AccidentRecorder.c
├── CruiseControlSWC.c
├── EmergencyBreakSWC.c
├── EngineControl.c
├── TargetSpeed.c
│
├── AUTO-MOBILE.png
├── ECU.png
├── EngineControl_READ ME.txt
│
├── Unit4-Documentation for Implementing Cruise Control and Emergency Brake in AUTOSAR.pdf
└── unit4-task-question.pdf
```

## Project Workflow

1. Define the automotive software requirements.
2. Design Software Components and interfaces in SystemDesk.
3. Configure component ports and internal behaviors.
4. Generate or configure the AUTOSAR Runtime Environment.
5. Implement the component logic using C.
6. Prepare the virtual simulation environment with VEOS.
7. Evaluate the component behavior using simulation inputs and outputs.

## Documentation

- [Project Implementation Documentation](Unit4-Documentation%20for%20Implementing%20Cruise%20Control%20and%20Emergency%20Brake%20in%20AUTOSAR.pdf)
- [Original Project Task](unit4-task-question.pdf)

## Learning Outcomes

Through this academic project, I explored:

- AUTOSAR Classic architecture and Software Components.
- C programming for automotive embedded systems.
- AUTOSAR RTE communication concepts.
- Cruise control and emergency braking logic.
- Virtual ECU simulation concepts.
- Component-based automotive software development.

## Important Note

This repository represents an academic software prototype. It is intended for educational purposes and is not certified for use in real vehicles or safety-critical applications.


Project video: 
https://www.youtube.com/watch?v=j8z6x-xMgdg

https://www.youtube.com/watch?v=zBaiihsHe5w
