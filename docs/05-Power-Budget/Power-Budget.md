---
title: Power Budget
---
title: Power Budget
---

# Power Budget

**Team Number:** ###<br>
**Project Name:** Robotic Gripper – Tactile Force Sensing Node (Board 3)<br>
**Team Member Names:** (team member names)<br>
**Version:** 1

## Section A: All Major Components

| Component Name | Part Number | Supply Voltage Range | Qty. | Absolute Maximum Current (mA) | Total Current (mA) | Unit |
|---|---|---|---|---|---|---|
| Microcontroller (PIC18F57Q43 Curiosity Nano) | DM164150 | +1.8 – 5.5V | 1 | 250 | 250 | mA |
| Quad Op-Amp | MCP6004-I/P | +1.8 – 6.0V | 1 | 30 | 30 | mA |
| Force Sensor (FSR + 1 kΩ divider) | Interlink FSR 402 (30-81794) | +5V | 1 | 5 | 5 | mA |

## Section B: +5V Power Rail

| Component Name | Part Number | Supply Voltage Range | Qty. | Absolute Maximum Current (mA) | Total Current (mA) | Unit |
|---|---|---|---|---|---|---|
| Microcontroller (PIC18F57Q43 Curiosity Nano) | DM164150 | +1.8 – 5.5V | 1 | 250 | 250 | mA |
| Quad Op-Amp | MCP6004-I/P | +1.8 – 6.0V | 1 | 30 | 30 | mA |
| Force Sensor (FSR + 1 kΩ divider) | Interlink FSR 402 (30-81794) | +5V | 1 | 5 | 5 | mA |
| | | | | | **Subtotal** | **285 mA** |
| | | | | | **Safety Margin** | **25%** |
| | | | | | **Total Current Required on +5V Rail** | **356.25 mA** |

## Section C: Regulator

| Component Name | Part Number | Supply Voltage Range | Qty. | Absolute Maximum Current (mA) | Total Current (mA) | Unit |
|---|---|---|---|---|---|---|
| +5V Regulator | LM7805 (TO-220) | +7 – 35V | 1 | 1500 | 1500 | mA |
| | | | | | **Total Remaining Current Available on +5V Rail** | **1143.75 mA** |

**Regulator or Source Choice (+5V Rail):** LM7805 linear regulator
