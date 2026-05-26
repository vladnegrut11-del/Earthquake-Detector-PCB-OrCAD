# Earthquake Detection Circuit - Custom PCB Design

## Project Overview
This repository contains the complete Electronic Design Automation (EDA) project for an analog earthquake detection and seismic vibration monitoring system. The project covers the full hardware development lifecycle, from initial schematic capture to a fully routed, production-ready 2-layer Printed Circuit Board (PCB).

## Technical Specifications & Features
Signal Conditioning: Integrated an M741 operational amplifier to handle low-frequency, low-amplitude analog signals from the seismic sensor, requiring precise gain and filtering stages.
Noise Mitigation: Implemented precise trace clearances and a dedicated partial ground plane (GND) on the Bottom layer to prevent interference in the analog signal path.
Design Integrity: Achieved strict schematic-to-layout equivalence with 0 Design Rule Check (DRC) errors after rigorous database verification (DBdoctor).
Manufacturing Ready: Includes complete manufacturing assets conforming to industry standards.

## Tools & Technologies
Cadence OrCAD Capture 17.2 – Schematic Design & Netlist Generation (`orWirelist64`)
Cadence OrCAD PCB Editor 17.2 – Component Placement, Manual Routing & Copper Pour Validation

## Repository Structure
/Hardware - Source files: Schematic database (`.dsn`), Netlist files (`.dat`), and the final board layout (`.brd`).
/Fabrication - Industry-standard Gerber files (`.art`), drill parameters, and manufacturing configuration files.
/Docs - Full fabrication blueprints including Top/Bottom layers, Silkscreen, Assembly drawings, Assembly Bill of Materials (BOM), and the post-processed Wirelist in PDF format.

---
Developed as an engineering project at the Faculty of Electronics, Telecommunications and Information Technology (ETTI), Polytehnica University of Bucharest.
