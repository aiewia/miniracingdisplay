# Sim Racing OLED Dash (RB19 Style)

🚧 **Work In Progress (WIP)** 🚧  
This project is under active development. Expect bugs, incomplete features, and frequent changes.

🤖 **AI-Assisted Development**  
Parts of this project (including firmware logic and documentation) were generated and refined using AI tools.  
All integration, testing, and tuning were performed by the project author.

---

## Overview

This is an Arduino-based OLED dashboard designed for sim racing.

Features:
- Gear display
- Proportional RPM bar (Standard mode)
- RB-style shift indicator mode
- Adjustable shift window tuning
- DRS indicator
- Pit limiter screen
- Multi-sim compatibility (F1 series, Assetto Corsa, others)

---

## Modes

### Standard Mode
- Proportional RPM bar
- Uses simulator-reported MaxRPM
- Designed for broad compatibility

### RB Mode
- Half bar at 10,000 RPM
- Full bar at 11,600 RPM
- Flash above 12,200 RPM
- F1-style top LED sweep

---

## Hardware Requirements

- Arduino-compatible board (UNO R4 RECCOMENDED)
- 128x64 SH1106 OLED display
- SimHub (or compatible telemetry output)
- Basic wiring knowledge

---

## License

This project is licensed for **personal and non-commercial use only**.

You may:
- Use it
- Modify it
- Share it

You may NOT:
- Sell it
- Use it in commercial hardware builds
- Rebrand or claim authorship

See the LICENSE file for full terms.

---

## Disclaimer

This project is provided "as is", without warranty of any kind.  
Use at your own risk.

---

## Status

This is a hobby project and will continue to evolve.  
UI layout, shift logic, and telemetry structure may change over time without notice.
