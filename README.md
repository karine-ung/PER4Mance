# PER4Mance: Prototyping Environment for HMI Research on Alarm Flood Management
## Description

"PER4Mance" is a prototyping environment that simulates the process control of a chemical plant. For this experiment, the data from the Tennessee Eastman Process (TEP) industrial process is used. PER4Mance has a Graphical User Interface (GUI) that was designed for the TEP and which enables inputs from operators.

The main goal of this prototyping environment is to promote research on the interactions between operators and complex systems during an alarm flood conditions. In this simulation, an integrated diagnostic tool provides a solution that can be pre-set to provide a correct or incorrect diagnosis. This function was created to encourage research on operator's diagnostic performance, and trust in the machine.

## Setup
In order to launch the simulation, the files need to be opened in MATLAB. 
- Open the "MultiLoop_mode1.mdl" file. This will launch the Simulink model of the TEP
- Open "TElib.mdl".
- Open "temexd_mod.c". 
#### The opened files don't need to be changed, they just need to be opened.
- Go to "app" folder.
- Open "fault_selection_App.mlapp".
- Run the program.
The program will show whether a user wants to activate a fault, which fault needs to be activated specifically, and when will it occur. A user will also be asked to input whether the diagnostic tool needs to provide a correct or incorrect diagnostic.
