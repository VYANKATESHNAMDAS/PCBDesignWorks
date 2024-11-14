# Bridge Rectifier Project
This project demonstrates the design and functionality of a Bridge Rectifier circuit in Proteus. 
A bridge rectifier converts AC (Alternating Current) to DC (Direct Current), and this design includes additional components for voltage regulation and stabilization.

## Project Overview
  - Software Used: Proteus Design Suite
  - Purpose: To convert AC voltage to DC voltage using a bridge rectifier configuration, along with a voltage regulator and capacitor filters for a stable DC output.
  - Creator: Vyankatesh (VYANKII)

## Components Used
  - 1]781 Voltage Regulator	
  - 2]Bridge Rectifier
  - 3]2-Pin Connector	
  - 4]Capacitor (Disc 100nF)	
  - 5]Capacitor Pol.(100µF)	
  - 6]Capacitor Pol. (47µF)	
  - 7]LED	
  - 8]Resistor (1kΩ)	
  - 9]Transformer (2P2S)
  - 10]AC Voltage Source
  - 11]DC Voltmeter

### Circuit Schematic
The schematic of the bridge rectifier circuit includes:

  - A transformer to step down the input AC voltage.
  - A bridge rectifier to convert AC to pulsating DC.
  - Filter capacitors to smooth the output.
  - A 781 voltage regulator IC to provide a stable DC output.
  - An LED indicator with a 1k resistor to show the presence of DC voltage.

### PCB Design
  - 1]Layout: The PCB layout was designed in Proteus, ensuring optimal component placement and wiring.
  
  - 2]3D View: A 3D representation of the PCB is available, providing a realistic visualization of the final design.
     

### Working Principle
  - AC Input: The AC voltage source provides an alternating input voltage to the transformer.
  - Step Down: The transformer steps down the AC voltage to a suitable level.
  - Rectification: The bridge rectifier converts AC to DC, producing a pulsating DC output.
  - Filtering: Capacitors smooth the pulsations, providing a more stable DC voltage.
  - Regulation: The 781 voltage regulator IC ensures a steady DC output voltage.
  - Indicator: The LED lights up to indicate the presence of DC voltage at the output.

### Simulation and Testing
The simulation of the bridge rectifier circuit was conducted in Proteus.
The output can be observed with a DC voltmeter connected across the output terminals to verify the rectified and regulated DC voltage.

### Files Included
  - Schematic and PCB Design: Files for the schematic and PCB layout.
  - 3D View: A 3D representation of the PCB.
  - Simulation File: Proteus simulation for testing and verification.
  - Video: Demonstration of the circuit in action.

### How to Use
  - Open the project file in Proteus.
  - Run the simulation to observe the working of the bridge rectifier.
Check the DC voltage across the output terminals to confirm rectification and regulation.
