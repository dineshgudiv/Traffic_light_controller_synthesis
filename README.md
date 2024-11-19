# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

## Synthesis RTL Schematic :
![WhatsApp Image 2024-11-18 at 11 41 05_d2527155](https://github.com/user-attachments/assets/e5ec51a2-a446-42c0-a0bf-8efea3b4a90e)


## Area report:
![WhatsApp Image 2024-11-18 at 11 41 04_2c5fb24e](https://github.com/user-attachments/assets/9bb1eef8-7fbf-4cd5-9fb0-e4c95052015b)

## Power Report:
![WhatsApp Image 2024-11-18 at 11 41 05_99088dea](https://github.com/user-attachments/assets/495ede75-2a11-4723-8787-10037fbfa6f3)

## Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
