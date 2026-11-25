# Easy-Bitx Dual Band

Arduino-based VFO/BFO firmware for the **Easy-Bitx HF Transceiver**, supporting 40m and 20m amateur radio bands.

The firmware uses an Arduino Nano and Si5351 clock generator with a 10 MHz IF architecture. It provides frequency tuning, BFO adjustment, EEPROM frequency storage, band switching and a 16×2 LCD interface.

## Features

- Dual-band operation: 40m and 20m.
- Si5351-based VFO and BFO generation.
- USB/LSB operation.
- Rotary encoder frequency tuning.
- Five selectable tuning steps (1 Hz to 10 kHz).
- Adjustable BFO frequency.
- EEPROM settings storage.
- Automatic band filter relay switching.
- LCD frequency and S-meter display.

## Hardware Platform

- Arduino Nano (ATmega328P)
- Si5351 clock generator
- 16×2 parallel LCD
- Rotary encoder with push button
- Band filter switching relay

## Installation

1. Install the Arduino IDE.
2. Install the required libraries: Si5351Arduino, Rotary, EEPROMex and EasyButton.
3. Open `EasyBitx_v1.6_dualBand_v1.6.0.ino`.
4. Select Arduino Nano and the appropriate processor.
5. Compile and upload.

## Development History & Credits

This firmware has its roots in earlier Easy-Bitx VFO/BFO projects.

- **J. CesarSound** – Original code (2020).
- **Nitin William (VU3GAO)** – Easy-Bitx Dual Band VFO/BFO firmware (2021).
- **Sunil Lakhani** – Previously supplied Easy-Bitx kits using this firmware.
- **RADIOKITS-BR** – Subsequent modifications (2025).

This repository preserves the dual-band firmware implementation for amateur radio enthusiasts interested in the Easy-Bitx platform.

---

**73 de VU3HZW**
