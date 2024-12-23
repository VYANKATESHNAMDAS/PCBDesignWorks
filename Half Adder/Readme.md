# Half Adder Circuit Project

This project demonstrates the design and implementation of a Half Adder circuit using Proteus software. 
The Half Adder is a combinational circuit that performs binary addition of two input bits, producing a Sum and a Carry as outputs.

## Features

- Input Switches: Two single-pole double-throw (SPDT) switches for binary inputs A and B.

- Logic Gates: XOR gate (74LS86) and AND gate (74LS08) for logic operations.

- Output Indicators: Two LEDs to display the Sum (Green LED) and Carry (Red LED).

- Proteus Design Files: Includes the schematic, PCB layout, and 3D view of the circuit.

### Components Used

 1. Logic ICs:

    - 74LS86 (XOR gate)

    - 74LS08 (AND gate)

 2. Resistors:

    - R1, R2: 470 Ω each

 3. LEDs:

    - Sum Output: Green LED

    - Carry Output: Red LED

 4. Switches:

    - SW1 and SW2: SPDT switches for inputs

 5. Power Supply:

    - B1: 5V DC


### Project Files

  -Schematic: Logical representation of the circuit, showing connections between components.

  - PCB Layout: Tracks and component placements for fabricating the circuit.

  - 3D View: Visualization of the final PCB design.


### How to Use

  - 1. Open the provided Proteus project files.

  - 2. Simulate the circuit to observe the Half Adder functionality.

      - Set the positions of SW1 and SW2 to provide binary inputs (0 or 1).

      - The Green LED will light up for the Sum output.

      - The Red LED will light up for the Carry output.

  - 3. Optionally, use the PCB design to fabricate the circuit for physical implementation.



### Explanation of Operation

  - The XOR gate (74LS86) computes the Sum output based on the inputs A and B.

    - Sum = A ⊕ B

  - The AND gate (74LS08) computes the Carry output.

    - Carry = A ∧ B

  

### Author

  - Designed and implemented by Vyankatesh.

