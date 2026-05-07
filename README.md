# Ecosmart-2k25-Sustainable-Home

An intelligent renewable-energy-powered smart home prototype focused on energy conservation, automation, and sustainable infrastructure.This project integrates solar awareness, motion-based automation, and smart lighting control using embedded systems and sensor-driven logic.

Overview
Traditional lighting systems waste massive amounts of electricity because lights remain active even when no one is present. EcoSmart solves this problem through:

Ambient light sensing
Human presence detection
Hybrid power awareness
Automated lighting control

The system dynamically responds to environmental conditions and user activity to minimize unnecessary energy consumption while promoting renewable energy usage.

Objective
Reduce energy wastage in residential and smart infrastructure environments
Integrate renewable energy awareness into automation systems
Build a low-cost smart lighting solution using embedded systems
Demonstrate hybrid solar + backup power operation
Develop a scalable foundation for future IoT-based smart home

Key Features
🌞 Solar-aware smart lighting system
🌙 Automatic day/night detection using LDR
🚶 Motion detection using ultrasonic sensor
⚡ Hybrid power indication (Solar + Backup)
💡 Adaptive lighting control
🔔 Audio indication during solar operation
🔋 Energy-efficient embedded automation
🧠 Real-time sensor-driven decision making
🏠 Smart mini-home prototype architecture

Working Principle
The system continuously monitors:

Ambient Light Intensity
Using an LDR sensor
Determines whether conditions are bright or dark
Human Presence
Using an ultrasonic sensor
Detects nearby movement or object presence

Based on sensor inputs:

Lights turn ON only when needed
Lighting condition changes dynamically
Solar mode is indicated through LEDs and buzzer feedback
Backup mode activates when solar availability is absent

This creates an intelligent energy-efficient environment.

Hardware Components
Component	Purpose
Arduino Uno	Central controller
LDR Sensor	Detects ambient light
Ultrasonic Sensor	Detects human/object presence
LEDs	System state indicators
Piezo Buzzer	Solar mode indication
Resistors	Current limiting & voltage division
9V Supply	Simulated solar input
5V Supply	Backup power source

Software Used
Software	Role
Arduino IDE	Embedded programming
Embedded C	Control logic implementation
Tinkercad / Circuit Simulation	Circuit prototyping and testing
Serial Monitor	Debugging and sensor monitoring

System Behaviour
Condition	System Response
Bright light + No motion	Lights OFF
Bright light + Motion	Blue LED ON
Dark + No motion	Lights OFF
Dark + Motion	White LED ON
Solar active	Green LED + Buzzer
Backup active	Red LED

Methodology
Input Layer
LDR senses light intensity
Ultrasonic sensor detects movement
Processing Layer
Arduino processes sensor data
Decision-making based on thresholds
Output Layer
LEDs indicate lighting states
Buzzer indicates solar operation

Algorithm
Initialize sensors and outputs
Read LDR values
Determine day/night condition
Trigger ultrasonic sensor
Detect nearby objects
Toggle lighting accordingly
Indicate active power source
Repeat continuously in loop

Results
The system demonstrated:

Accurate light sensing
Reliable motion detection
Instant response to environmental changes
Significant reduction in unnecessary lighting usage
Performance Highlights
Estimated energy-saving efficiency: 85–95%
Fast real-time response
Stable operation under multiple test conditions
Effective hybrid power indication

Applications
Smart homes
Smart street lighting
Campus infrastructure
Renewable energy demonstration systems
Smart city prototypes
Industrial automation environments
Sustainable residential systems

Future Scope
IoT integration for remote monitoring
AI-based predictive energy management
Mobile app control
MPPT solar optimization
LiFePO4 battery integration
Smart grid connectivity
Multi-home microgrid expansion
Advanced environmental sensing

Key Concepts Used
Embedded Systems
Renewable Energy Integration
Sensor-Based Automation
Hybrid Power Management
Smart Lighting Systems
Energy Conservation
Real-Time Decision Systems
Sustainable Infrastructure
Tech Stack
Arduino
Embedded C
Sensor Interfacing
Hybrid Energy Systems
Automation Logic
Smart Control Systems

Author
Pranav J
