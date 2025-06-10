# Analog Voltmeter - EN2091 Project

This repository contains the design files, schematics, simulation results, and documentation for the Analog Voltmeter developed by Group **Wired Wizards** for the EN2091 course at the Department of Electronic and Telecommunication Engineering, University of Moratuwa.

## 🧪 Project Overview

The **Analog Voltmeter** is a fundamental instrument that measures voltage by displaying it on a mechanical needle dial. This project presents a custom-designed, low-cost analog voltmeter capable of measuring voltage in **three different ranges** using op-amp-based amplification and conversion circuits.

## 👥 Team Members

- BANDARA R.M.T.D. (220067G)  
- KUMARAGE R.V. (220343B)  
- RANSIKA L.G.C. (220514C)  
- SAMUDITHA H.K.P. (220562U)

## 📋 Table of Contents

- [Working Principle](#working-principle)
- [System Model & Design Parameters](#system-model--design-parameters)
- [Schematics](#schematics)
- [PCB Design](#pcb-design)
- [Enclosure](#enclosure)
- [Simulation](#simulation)
- [Bill of Materials](#bill-of-materials)
- [Conclusions and Future Work](#conclusions-and-future-work)
- [References](#references)

## 🔧 Working Principle

The analog voltmeter operates by converting electrical signals into mechanical motion using a coil and permanent magnet. The deflection of the needle represents the input voltage level.

### Key Points:
- Magnetic coil interaction
- Calibrated mechanical deflection
- Amplified voltage-to-current conversion

## 🛠️ System Model & Design Parameters

- Amplification using TL072 op-amps
- Sensitivity and accuracy optimized for educational and lab use
- Designed with rapid response time and minimal ripple

## 🔌 Schematics

The circuit includes:
- AC-DC conversion
- Overvoltage protection
- Voltage amplification and switching

(Schematic images available in `/schematics` folder or report)

## 🖨️ PCB Design

- 2-layer PCB with organized layout
- Clear labeling and logical component grouping
- AC input via vias, ergonomic design for enclosure fitting

## 🧱 Enclosure

- Compact, sloped front panel design for better visibility
- Clearly labeled rotary switch
- Easy maintenance with accessible component layout

## 🧪 Simulation

Simulated using **Proteus**:
- Validated switching mechanism
- Verified ripple reduction using 470μF filter capacitors

## 📦 Bill of Materials

| Component         | Description                                  | Qty |
|------------------|----------------------------------------------|-----|
| TL072CP          | Op-amp (non-inverting amplifier)             | 1   |
| Potentiometer    | Voltage divider                              | 2   |
| Capacitors       | Filtering and decoupling                     | 10  |
| Resistors        | Various resistance values                    | 7   |
| BC558 Transistor | Overvoltage protection                       | 2   |
| Diodes           | Bridge rectifier                             | 4   |
| Transformer      | AC voltage step-down                         | 1   |
| Voltage Regulators | LM317, LM137                              | 2   |
| Varistor, Zener  | Voltage protection                           | 2   |

## ✅ Conclusions and Future Work

The project successfully delivers a reliable and accurate analog voltmeter with multiple range options and a robust power supply. 

### Possible Improvements:
- Auto-range selection
- Battery-powered portable version

## 🔗 References

- [Overvoltage Protection Circuit – CircuitDigest](https://circuitdigest.com/electronic-circuits/overvoltage-protection-circuit)
- [TL072 Datasheet – Texas Instruments](https://www.ti.com/product/TL072)
- [BC558 Datasheet – AllDataSheet](https://www.alldatasheet.com/view.jsp?Searchword=BC558)
- [Zener Diode 1N4749 – Futurlec](https://www.futurlec.com/Diodes/1N4749pr.shtml)
- [LM317 Regulator – TI](https://www.ti.com/lit/gpn/LM317)
- [LM137 Regulator – TI](https://www.ti.com/lit/ds/symlink/lm137.pdf)

---

📁 **Note**: Please refer to the `Analog_project.pdf` for complete design documentation including all figures and simulation visuals.

