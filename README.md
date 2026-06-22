# Hardware

This repository contains hardware design files for various products and subsystems, including but not limited to:

- Flight Controllers (FC)
- Electronic Speed Controllers (ESC)
- Radio Control Systems (RC)
- Video Transmitters (VTX)
- Power Distribution Units (PDU)
- Sensor Boards
- Companion Computers
- Other supporting avionics and embedded hardware

## Naming Convention

Project directories shall follow the format:

    <MCU_OR_CPU>_<HARDWARE>_RevX

Examples:

    STM32F405_FlightController_Rev1
    STM32F405_ESC_Rev1
    ESP32S3_RC_Rev1
    ESP32S3_VTX_Rev1
    RPiCM4_CompanionComputer_Rev1

### Rules

- Use underscores (_) as separators.
- Do not use spaces in directory names.
- MCU/CPU name must appear first.
- Hardware name must appear second.
- Revision number must appear last.

## Repository Contents

Each project directory may contain:

- Schematics
- PCB Layouts
- Manufacturing Files
- Bill of Materials (BOM)
- Assembly Documentation
- Design Notes

## Revision Policy

New hardware revisions shall be created as separate directories following the established naming convention. Previous revisions should be retained for traceability and historical reference.

