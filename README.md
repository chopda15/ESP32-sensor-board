# ESP32-C3 IoT Sensor Board with Li-ion Power Management

Custom-designed IoT PCB built in KiCad featuring the ESP32-C3-WROOM-02 module, integrated Li-ion charging circuitry, environmental sensing, onboard storage, and USB-C connectivity.

This project was developed to practice real-world embedded hardware design workflows including schematic capture, PCB layout, signal integrity considerations, power management, DFM validation, and manufacturing preparation.

---

# Features

## Microcontroller
- ESP32-C3-WROOM-02
- Wi-Fi + BLE connectivity
- Low-power IoT architecture

## Power System
- TP4056 Li-ion battery charger
- USB-C power input
- Single-cell LiPo battery support
- Battery charging and protection circuitry
- 3.3V regulated power rail

## Sensors & Peripherals
- BME280 environmental sensor
  - Temperature
  - Humidity
  - Pressure
- Ambient light sensor
- Sound sensor with microphone amplifier
- OLED display via I2C
- SPI flash memory
- Micro SD card interface

## User Interface
- Status LEDs
- Push buttons
- USB-UART interface for programming/debugging

---

# PCB Design Highlights

## Signal Integrity
- Differential routing for USB signals
- SPI trace optimization
- Reduced trace lengths for high-speed signals
- Ground plane implementation
- Decoupling capacitor placement optimization

## Power Distribution
- Copper pours for stable power delivery
- Wide power traces to minimize voltage drop
- Multiple decoupling capacitors for noise reduction

## Manufacturing Considerations
- ERC and DRC validation
- DFM analysis before fabrication
- Gerber generation
- BOM and centroid file generation
- Silkscreen refinement
- 3D PCB validation

---

# Tools & Technologies

- KiCad 9
- ESP32-C3
- TP4056
- JLCPCB DFM tools
- Git & GitHub

---
