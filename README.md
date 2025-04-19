# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-04-19 101154](https://github.com/user-attachments/assets/86fc64fc-1733-4ae3-878f-d2aec0300871)


## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

   ![Screenshot 2025-04-19 101135](https://github.com/user-attachments/assets/d2985105-1642-439d-bcae-3d4f9c2e1f66)
   ![Screenshot 2025-04-19 101145](https://github.com/user-attachments/assets/7e121e01-6627-4b62-804b-b566a5216072)
   ![Screenshot 2025-04-19 101202](https://github.com/user-attachments/assets/23e89c19-c761-4833-8bb5-8d0a8276a00b)





## Output
#### 1. Transient Analysis Output:

   ![Screenshot 2025-04-19 101212](https://github.com/user-attachments/assets/2b053619-0842-4453-be6c-be2aa92b9334)


## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


