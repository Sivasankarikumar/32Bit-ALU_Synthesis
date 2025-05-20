# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

![Screenshot (124)](https://github.com/user-attachments/assets/0f25a75f-3cb7-42f5-b829-b5dbe1c4467f)

#### Synthesis RTL Schematic :

![Screenshot (125)](https://github.com/user-attachments/assets/5afe7ea6-9036-4f92-bdb9-604b41e12940)

#### Area report:

![Screenshot (126)](https://github.com/user-attachments/assets/004a78c9-9a96-4137-8ec3-e46b2c1e5866)

#### Power Report:

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
