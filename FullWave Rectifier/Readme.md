# Full-Wave Rectifier
This repository contains files and documentation for a Full-Wave Rectifier circuit, including its schematic, PCB layout, and 3D model.

## Project Overview
A Full-Wave Rectifier is an electronic circuit that converts an alternating current (AC) input into a direct current (DC) output. 
This circuit uses diodes to achieve full-wave rectification, which allows current flow in both directions, providing a more efficient DC output compared to a half-wave rectifier.

### Repository Structure

/schematic: Contains the circuit schematic for the Full-Wave Rectifier.

/pcb_design: Contains the PCB design files (Gerber files, etc.) for the rectifier.

/3d_view: Contains 3D model views of the PCB for visual reference.

### Requirements
Components:
  - 1] 4 x Diodes (1N4007 or similar)
  - 2] Capacitors and resistors as specified in the schematic
  - 3] Transformer for AC input (specification depends on desired output)

### Software:

Proteus software for opening the schematic and PCB files.

Clone the repository:
git clone https://github.com/VYANKATESHNAMDAS/full-wave-rectifier.git

Open the /schematic and /pcb_design files with KiCad or similar software.
Refer to the 3D views in the /3d_view folder for an understanding of component placements.

### Usage
  - Assembly: Follow the PCB layout and assemble the circuit.
  - Testing: Connect an AC source to the input and use a multimeter to verify DC output voltage.
  - Applications: Suitable for power supplies and other circuits requiring DC conversion.  
