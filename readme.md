
# Passive IoT Device Works with Energy Harvesting
## Description
This project aims to design a passive watch that can warn blind people of nearby vehicles and pedestrians by vibration. The watch is powered by a solar panel and uses an Arduino ultra-low power processor as the main control chip. The watch employs millimeter wave radar technology to detect vehicles and personnel sensing radar technology to detect pedestrians, achieving comprehensive safety monitoring. The watch has two modes: optional mode and charge mode. In optional mode, the watch vibrates when vehicles and pedestrians are detected approaching from behind or the opposite direction within a certain distance. In charging mode, the watch switches off all sensors to save power and focuses on collecting energy with the solar panel and storing it. Users can switch between the two modes by lifting the solar panel pad.

The motivation for this project was to overcome the limitations of existing solutions for blind people's travel safety, such as canes, guide dogs or smartphone apps, which are either cumbersome, expensive or require active operation. The project also considers the user's comfort and aesthetics by designing a lightweight and stylish watch that can be worn on any wrist size.

The project was completed as part of the CE301 - Individual Capstone Project Challenge at the University of Essex, under the supervision of Hossein Anisi and Jon Chamberlain.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Installation
To install and run this project, you will need:

- Arduino IDE
- FRDM k32L2B development board
- LD2410 millimeter wave radar module
- VL53L0X ToF sensor module
- WH-BLE106 low power Bluetooth module
- SPV1040TTR boost converter chip
- ADP5091ACPZ battery management chip
- Solar panel (6V, 1W)
- Hilink 79G milimeter wave antenna.
- Lithium-ion battery (3.7V, 500mAh)
- Vibration motor (3V, 75mA)
- Buzzer (3V, 30mA)
- Switch (SPDT)
- Resistors, capacitors, diodes and wires

Follow these steps to install and run the project:

1. Clone this repository to your local machine.
2. Open the Arduino IDE and select the atemga328p board from the Tools menu.
3. Connect the atemga328p board to your computer via USB cable.
4. Upload the Passive_Watch.ino sketch to the board.
5. Connect the other components according to the schematic diagram in Appendix A.
6. Put on the watch and switch to optional mode or charge mode as desired.

## Usage
To use this project, follow these instructions:

- In optional mode, the watch will vibrate when it detects vehicles or pedestrians approaching from behind or in front of you within a certain distance. The vibration intensity and frequency will vary according to the distance and speed of the approaching objects.
- In charge mode, the watch will turn off all sensors and focus on harvesting energy from the solar panel and storing it in the battery. 
- To switch between optional mode and charge mode, lift or lower the solar panel pad using the hinges.

## Contributing
This project is open for contributions. If you are interested in contributing to this project, please follow these steps:

1. Fork this repository to your GitHub account.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes in your branch and commit them with clear messages.
4. Push your branch to your forked repository.
5. Create a pull request from your branch to this repository's main branch.
6. Wait for feedback or approval from the project owner.

