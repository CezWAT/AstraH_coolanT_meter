# AstraH_coolanT_meter
Simple Arduino based engine coolant temperature meter for Astra H

Opel/Vauxhall Astra H lacks coolant meter. This simple project is about bringing it to the dashboard.
The goal is to make a device, using Arduino and compatible modules with a modified fuel gauge, that that listens for the data from engine ECU.

Used hardware:
* Arduino Nano
* L9110 module to control original fuel meter motor
* MCP2515 based module to read CAN data

Used libraries:
* https://github.com/autowp/arduino-mcp2515
* https://github.com/FancyFoxGems/HalfStepper

CAN informations source:
* https://github.com/JJToB/Car-CAN-Message-DB
