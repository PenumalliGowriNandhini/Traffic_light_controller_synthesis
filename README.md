# Traffic_light_controller_Synthesis

# Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

# Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

# Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

# Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

# Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

# Synthesis RTL Schematic :
![Screenshot 2024-11-18 120045](https://github.com/user-attachments/assets/48142693-6c65-4b59-b4de-f2b7da661a2e)
# Area report:
![Screenshot 2024-11-18 120113](https://github.com/user-attachments/assets/fe21a62a-a1d0-4191-ab30-2e825bd9fe30)
# Power Report:
![Screenshot 2024-11-18 120127](https://github.com/user-attachments/assets/0fe0c0cd-4d89-476d-9f2b-c82f5d1a3fc8)
# Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
