# Rtype-Datapath-project-in-logisim
This is a academic project of computer Architecture Lab course  

This repository contains a project for simulating an R-type datapath using Logisim. It was developed as part of a Computer Architecture Lab course to demonstrate the core working principles of R-type instructions in a simplified CPU design.

### Project Overview
The R-type datapath is a fundamental part of a CPU architecture, used to execute arithmetic and logical operations.

#### Tools Used
This project utilized the following tool for design and simulation:

Logisim: A free, educational tool for designing and simulating digital logic circuits. Version 2.7.1 was used to create and test the R-type datapath.

## This project implements the datapath components, including the connections between:

#### ALU (Arithmetic Logic Unit): Performs operations such as addition, subtraction, and bitwise logic.
#### Register File: Manages input and output registers for operations.
#### Control Signals: Direct the flow of data and operations in the datapath.
Features
#### Logisim Design: Fully functional R-type datapath simulated in Logisim.
#### Components Used:
Multiplexers (MUX)
Splitters
ALU
Registers
Control Units
Instruction Support: Includes operations such as ADD, SUB, AND, OR, and XOR.
Circuit Design
#### The design includes the following major elements:

Instruction Fetch: Decodes R-type instructions.
##### Execution Unit:
Register inputs are selected and routed to the ALU.
ALU performs operations based on control signals.
#### Write-back:
ALU results are written back to the appropriate register.
The design adheres to the MIPS architecture principles, ensuring clarity and modularity. 

#### How It Works
Load R-type instructions (e.g., ADD, SUB) into the instruction fetch unit.
Control signals route data through the datapath.
Observe the ALU operation and result stored in the destination register.
#### Example Simulation
Instruction: ADD $t1, $t2, $t3

Input: $t2 = 5, $t3 = 10

Output: $t1 = 15

The simulation demonstrates how operands are fetched, processed in the ALU, and the result is written back.


