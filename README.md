# Dual NE555 Timer LED Driver PCB

A compact, 2-layer PCB designed in KiCad featuring a dual NE555 timer circuit configured to drive an 8-LED array with dedicated current balancing and complete ground plane isolation.

## Overview
This project demonstrates complete schematic capture, circuit layout, and design for manufacturing (DFM) for a pulse-driven 555 timer board.

### Key Technical Specifications
* **Input Voltage:** 9V DC (Standard 9V Battery footprint)
* **Core ICs:** 2x NE555D Precision Timers (SOIC-8)
* **Output:** 8x Radial 3mm LEDs driven via NPN switching transistor
* **Protection & Stability:**
  * Dedicated 220Ω series current-limiting resistors for each LED to prevent thermal runaway
  * Solid top and bottom ground plane (F.Cu/B.Cu) copper pours to minimize EMI
  * 0.6 mm widened primary power routing to prevent voltage drops

## Design Files
* **EDA Tool:** KiCad 8.0+

## License
MIT License - feel free to use or modify this hardware design for your own projects.
