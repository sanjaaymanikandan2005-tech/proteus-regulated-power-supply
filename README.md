# Regulated DC Power Supply Design and Simulation

## Project Overview
A regulated DC power supply simulated using Proteus. The circuit converts AC input into regulated DC outputs for low-voltage electronic circuits.

## Output Specifications
- **12 V DC:** 7812 voltage regulator
- **5 V DC:** 7805 voltage regulator
- **3.3 V DC:** 78L33 voltage regulator

## Components Used
- AC source and transformer
- Bridge rectifier
- Filter capacitors
- 7812, 7805 and 78L33 voltage regulators
- Indicator LEDs and current-limiting resistors
- Input fuse

## Working Principle
1. The transformer provides AC voltage to the rectifier.
2. The bridge rectifier converts AC into pulsating DC.
3. Filter capacitors smooth the rectified voltage.
4. Voltage regulators provide the 12 V, 5 V and 3.3 V DC outputs.
5. LEDs indicate the output rails during simulation.

## Simulation 
<img width="1917" height="1045" alt="image" src="https://github.com/user-attachments/assets/eac63249-adb1-4745-955e-a956bd8f9121" />


## Simulation Results
The Proteus simulation displayed output voltages of approximately 12 V, 5 V and 3.3 V.
After simulation starts,
<img width="1357" height="946" alt="image" src="https://github.com/user-attachments/assets/05388243-44fc-494e-bfa3-4874b2ac3376" />


## Tools Used
- Proteus Design Suite

## Project Status
Simulation completed. Further component-rating and protection checks are required before any physical implementation.

## Safety Note
This project is a simulation exercise. Do not connect a physical circuit directly to mains voltage without appropriate isolation, protection, and qualified supervision.
