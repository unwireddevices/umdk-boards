# Unwired Mesh Development Kit (UMDK)

Unwired Development Kit is a set of boards for rapid prototyping Internet of Things devices — gateways, mesh networks, LoRa networks, and a variety of sensors, controls, and actuators, including widely used analog and digital industrial interfaces such as DALI, 0-10V PWM or RS-485.

The set consists of over 20 boards with 45x45mm base size (althought some boards are bigger). Main boards are UMDK-RF and UMDK-ONE — former is a baseboard for Unwired Mesh or Unwired Range Modules, and latter is a baseboard for Unwired One embedded computer. Each specific device prototype consists of a baseboard and single or multiple expansion boards with interfaces and controls needed for this devices. Unwired One can be an expansion too — in combination with UMDK-GATE or UMDK-GATE/E, which means it would work as Wi-Fi/Ethernet/USB interface for the UMDK-RF mainboard with Unwired Mesh or Unwired Range Module, but would not be able to control other expansion boards directly.

All files are in Diptrace format.

Module | Purpose
--- | ---
umdk-10v | 0-10V analog interface adapter
umdk-16x2 | 16x2 LCD display with I2C bus extender
umdk-1rac | High-power AC relay with external MCU-controlled triac to lower inrush currents
umdk-2032 | CR2032 power supply with optional voltage boost
umdk-2aa | 2xAA battery power supply with step-up DC/DC and discharge control
umdk-2dim | Phase angle AC dimmer and zero cross detector
umdk-2led | DC LED driver with PWM control and up to 2x60V/1A load
umdk-2rdc | Regular relays
umdk-420 | Isolated 4-20 mA current loop interface
umdk-4btn | Pushbuttons and LEDs
umdk-5vio | Bidirectional voltage level shifter (5V/3.3V)
umdk-6fet | 6-channel MOSFET driver for DC loads up to 50V/3A
umdk-acc | 6-axis gyroaccelerometer (LSM6DS3)
umdk-dali | Isolated DALI (Digital Addressable Lighting Interface) adapter
umdk-gate | Gateway device based on Unwired One embedded computer
umdk-gps | GPS/GLONASS receiver
umdk-grv | External sensors adapter (partially compatible with Groove kits)
umdk-gsm | GSM/GPRS modem (SIM800 based)
umdk-hbr | Dual half-bridge motor driver
umdk-jtag | SWD/JTAG programmer with in-build GDB server
umdk-lion | Li-ion battery backup with charger and discharge control
umdk-lir | IR remote control and receiver
umdk-lit | Amient light sensor (TI OPT3001)
umdk-lmt | External temperature sensors adapter (TI LMT01)
umdk-one | Unwired One embedded computer adapted
umdk-pga | Programmable gain multichannel analog frontend
umdk-pir | PIR motion sensor
umdk-rfu | Unwired Range and Unwired Mesh radio modems adapter with USB-UART
umdk-rs485 | Isolated RS485 adapter
umdk-sht21 | Temperature, humidity and barometric pressure sensor (SHT21, LPS331AP)
umdk-sound | Sound level sensor
umdk-spk | Speaker
umdk-tbtn | Touch buttons
umdk-thp | Temperature, humidity and barometric pressure sensor (BME280)
