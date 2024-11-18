# Ex No: 05 Design-Implementation-of-1-Bit-Full-Adder-using-Cadence-Tools
     

## Aim:

To design and implement a 1-bit full adder circuit using Cadence EDA tools and to understand its behavior in digital arithmetic operations.

## Tools Required:

•	Personal Computer

•	Cadence Virtuoso Software

## Circuit Diagram:

![IMG-20241115-WA0006](https://github.com/user-attachments/assets/9b7907e2-47d3-4014-9317-998a850366b4)

## SCHEMATIC SIMULATION:

PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION
Commands to get into Cadence
1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window(CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre


i)	Procedure for Creating New Library.

•	File –New – Library

•	Name : Give name for ur library Ex: VLSILAB_EXP_1

•	Enable Attach to an existing technology library, Click OK

•	Attach the library to the technology library gpdk045.Click OK

ii)	Create Schematic Cell view.

•	Go to 1st window i.e virtuoso(CIW)

•	File-New-Cell view

•	Setup the new file form
	  Library: Select the one you a created.
	  Cell : Give the experiment name Ex: Inverter View_Schematic
	  Type: Schematic press OK
•	Add the required components from the libraries and make the connections.

• Go to instance fixed menu or use shortcut key “I” from keypad to go instances

•	Click on browse. This opens the library browser

•	Now select the appropriate library for components like 
• Gpdk45 ------------------------nmos1v,  pmos1v

• Create Input and Output pins

•	Make the connections by using fixed narrow wire key

•	Click Check and Save button

![IMG-20241112-WA0014](https://github.com/user-attachments/assets/d98e25b3-b7a9-4c76-808f-e3d8e25c4410)




 
iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute 

•	Create – Cell view – From Cell view

•	The cell view from cell view window appears

•	Check Lib Name, Cell Name, From View name must be schematic Press ok

•	Now Symbol generation form appears. Click Ok If No changes required

•	A new window with with default symbol is created.

•	Edit the symbol if you want to give actual symbol shape else continue.

•	Execute Create-Cell view-from cell view

•	Library Name and Cell Name must be same which you have used for schematic. Press OK

•	Check for the position of pin side.Prss OK

•	Edit for the shape by Create-Shape-Choose required options to edit.
![IMG-20241112-WA0013](https://github.com/user-attachments/assets/9761214f-a5e9-4a46-a952-117e66cc187c)




iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view

•	Setup the new file form

•	Library: Select the one you created.

•	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test

•	View: Schematic

•	Type: Schematic press OK

•	Follow the step 3(ii)  to make the required connections
![IMG-20241112-WA0009](https://github.com/user-attachments/assets/0c16a45a-f5e1-4fc8-aabe-3750bc57408d)


 
## Analog simulation by SPECTRE.
•	In test cell view window

•	Launch – ADE L(Analog Design Environment)

•	Execute Setup—Simulation/directory/Host A new window opens

•	Set the simulation window to spectre and click ok

•	Execute Analysis – Choose. A window opens.

•	Select the type and set the specifications and press OK

•	Execute Output s—to be plotted – Select on Schematic

•	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

•	Execute Simulation -- Net list and Run
![Screenshot 2024-11-14 153045](https://github.com/user-attachments/assets/6c26bcc7-f42d-4c9e-a494-193bd9d11ec1)



## For Transient Analysis Settings: 
 
![Screenshot 2024-11-14 153107](https://github.com/user-attachments/assets/4cece571-f64f-4538-952a-77dd7dae08a1)

 ## Output:
 
![Screenshot 2024-11-14 142733](https://github.com/user-attachments/assets/dd168097-963b-4685-8f52-8f770a3d20af)


 

## Result:

The design and implementation of the 1-bit full adder using Cadence EDA tools were successfully completed. The simulation results verified the correct operation of the full adder, with accurate sum and carry outputs for all input combinations.
