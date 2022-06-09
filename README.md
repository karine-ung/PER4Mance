# PER4Mance: Prototyping Environment for HMI Research on Alarm Flood Management
## Description

"PER4Mance" is a prototyping environment that imitates a process control of a chemical plant. For this experiment, the data from the Tennessee Eastman Process (TEP) industrial process is used. PER4Mance has a GUI that is applied to the TEP to illustrate a chemical process control.

The main goal of the project is to investigate the interaction between operators and complex systems during an alarm flood condition. In this simulation, an integrated diagnostic tool provides a solution that can be pre-set to correct or incorrect. This is done to check the reliability and trust of a user for the diagnostic tool.

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
