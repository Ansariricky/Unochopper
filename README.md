# FlightController

This repository contains the hardware design files for various flight control system components, including:

- Flight Controllers (FC)
- Electronic Speed Controllers (ESC)
- Radio Control (RC) Systems
- Video Transmitters (VTX)
- Power Distribution Units (PDU)
- Sensor and Peripheral Boards
- Supporting Avionics Hardware

## Naming Convention

Project directories shall follow the format:

    <MCU_OR_CPU>_<HARDWARE>_RevX

Examples:

    STM32F405_FlightController_Rev1
    STM32F405_FlightController_Rev2
    ESP32S3_RC_Rev1
    ESP32S3_VTX_Rev1
    ESP32S3_ESC_Rev1

### Rules

- Use underscores (_) as separators.
- Do not use spaces in directory names.
- MCU/CPU name should appear first.
- Hardware type should appear second.
- Revision number should appear last.

## Contents

Each project directory may contain:

- KiCad Schematics
- PCB Layouts
- Manufacturing Files
- Bill of Materials (BOM)
- Assembly Documentation
- Design Notes

## Revision Policy

Previous revisions are retained for traceability. New hardware revisions should be created as a new directory using the established naming convention.

