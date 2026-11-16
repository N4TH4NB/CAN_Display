# CAN Display

A custom automotive dashboard display designed to visualize vehicle data through the CAN bus.

The project focuses on developing a PCB with an STM32H7 microcontroller, a 7-inch TFT display, external memory, and support for additional sensors and communication interfaces.

## Hardware

Main components and features currently planned:

- **MCU:** STM32H743IIT6 (ARM Cortex-M7)
- **Display:** 7" IPS TFT, 800 × 480, RGB interface
- **Touch:** Resistive touchscreen with TSC2007 (I²C)
- **External RAM:** Winbond W9825G6KH-6 (32 MB SDRAM)
- **Communication:** CAN bus
- **Power Supply:** Automotive 12 V input with 5 V and 3.3 V regulators
- **Power Management:** ACC detection and controlled shutdown
- **Planned peripherals:** GNSS, IMU, microSD, and external Flash memory

## Software

Firmware is planned to use the STM32H7 peripherals and LVGL for the graphical user interface.

## Development Status

🚧 **Work in Progress**

The project is currently in the hardware design stage. Schematics, component selection, and peripheral integration are still under development.

## License

License to be defined.
