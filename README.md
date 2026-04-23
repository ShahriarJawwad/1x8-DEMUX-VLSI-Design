# 1×8 Demultiplexer (VLSI Design)

## Overview

This project presents the design and implementation of a 1×8 Demultiplexer using CMOS logic as part of VLSI laboratory work. The design demonstrates the complete digital IC design flow starting from logic-level simulation to schematic design, layout implementation, and performance analysis.

The system routes a single input signal to one of eight outputs based on a 3-bit select line.

---

## Design Flow

Logisim Simulation → CMOS Schematic (Cadence Virtuoso) → Layout Design → RC Extraction → Performance Analysis

---

## Functional Description

A 1×8 DEMUX has:
- 1 input (D)
- 3 select lines (S2, S1, S0)
- 8 outputs (Y0–Y7)

Only one output is active at a time depending on the select input combination.

---

## Simulation (Logisim)

![Logisim Simulation](logisim_simulation/screenshots/Simulation.png)

---

## Cadence Virtuoso Design

### Schematic Design

![Schematic1](images/circuit_images/Schematic1.png)

![Schematic2](images/circuit_images/Schematic2.png)

![Schematic3](images/circuit_images/Schematic3.png)

---

### Layout Design

![Layout](images/circuit_images/Layout1.png)

---

### Symbol View

![Symbol](images/circuit_images/Symbol.png)

---

## RC Extraction (RCX)

![RCX](images/circuit_images/RCX.png)

---

## Performance Analysis

### Input vs Output Waveform

![Input Output](images/result_waveforms/Input_Output.png)

### Power Analysis

![Average Power](images/result_waveforms/average_power.png)

![Power Dissipation](images/result_waveforms/Power_dissipation.png)

---

## Key Metrics

- Propagation delay analyzed from simulation results  
- Power consumption evaluated using Cadence tools  
- Layout verified using RC extraction (parasitic effects included)

---

## Stick Diagram

![Stick Diagram](stick_diagram/Stick_Diagram.png)

---

## Tools Used

- Logisim (Digital Simulation)
- Cadence Virtuoso (Schematic & Layout)
- CMOS VLSI Design Flow Tools
- Git & GitHub for version control

---

## Conclusion

The project successfully demonstrates the full VLSI design cycle of a 1×8 Demultiplexer. It connects theoretical digital design concepts with practical CMOS implementation and physical layout considerations.

---

## Author

Shahriar Jawwad  
Department of Electronics & Telecommunication Engineering
