# VLSI-EXPT-6
# SCHEMATIC ENTRY AND CIRCUIT SIMULATION OF A CMOS INVERTER, TWO INPUT AND GATE, TWO INPUT NOR GATE 
## AIM:
      To Schematic and Simulate Inverter using CADENCE virtuoso.
## APPARATUS REQUIRED: CADENCE VIRTUOSO
## PROCEDURE :
Procedure for Commands to get into Cadence
1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
3.i) tcsh
ii) source /home/install/cshrc
iii) virtuoso
## PROCEDURE FOR SCHEMATIIC SIMULATION USING CADENCE :
1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window(CIW) for further processing.
i) Create a New Library ii) Create Schematic Cell view.
iii) Create the Symbol for schematic Cell view. iv) Create the test Cell view.
v) Analog simulation by spectre
## PROCEDURE FOR CREATING NEW LIBRARY :
a)	File –New – Library
b)	Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click
OK
c)	Attach the library to the technology library gpdk045.Click OK
## CREATE SCHEMATIC CELL VIEW : 
a)	Go to 1st window i.e virtuoso(CIW)
b)	File-New-Cell view
c)	Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex:
Inverter View: Schematic
d)	Type: Schematic press OK
e)	Add the required components from the libraries and make the connections.
f)	Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. Thisopens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin
h)	Make the connections by using fixed narrow wire key
i)	Click Check and Save button
## CREATING THE SYMBOL FOR SCHEMATIC CELL VIEW :
a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok b. Now Symbol generation form appears. Click Ok If No changes required
c.	A new window with with default symbol is created.
d.	Edit the symbol if you want to give actual symbol shape else continue.
i.	Execute Create-Cell view-from cell view
ii.	Library Name and Cell Name must be same which you have used for schematic. Press OKiii. Check for the position of pin side.Prss OK iv. Edit for the shape by Create-Shape-Choose required options to edit
## CREATING THE NEW TEST CELL VIEW :
a)	Go to CIW window, Execute File-New-Cell view
b)	Setup the new file form
Library: Select the one you a created.
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
View: Schematic
Type: Schematic press OK Analog simulation by SPECTRE. a. In test cell view window
b.	Launch – ADE L(Analog Design Environment)
c.	Execute Setup—Simulation/directory/Host A new window opens
d.	Set the simulation window to spectre and click ok
e.	Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as statthen press OK.
f.	Execute Analysis – Choose. A window opens.
g.	Select the type and set the specifications and press OK
h.	Execute Output s—to be plotted – Select on Schematic
i.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mousej. Execute Simulation -- Net list and Run
## SIMULATION SETTINGS:
Setup for transient analysis:
1.	Stop time = 400n Setup for D.C analysis
2.	Component to be selected in schematic is for d.c analysis
3.	Start = -1 Stop = 1 resp.

## CMOS INVERTER :
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/037f6e39-424c-4f16-9229-3916112ec014)
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/d1d49fbf-41c9-4ce0-876b-19301ce01fb8)
## OUTPUT :
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/8c1fd898-b842-4e50-8352-fb4edbdc96bf)

NAND GATE :
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/0e74e6cd-8e2b-427a-be5b-446ec4595f54)
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/6613fa3c-0c9e-4571-afe9-7f2f81019f63)
## OUTPUT :
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/b392d2cc-c4d7-4c09-a186-5f4a44f29355)

## NOR GATE :
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/ab00f9f3-682c-4d1f-9306-2b5be07bbb1d)
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/5254aaa8-09ef-42b2-ac13-3611b07d0b84)
## OUTPUT :
![image](https://github.com/JAYASHREEER/VLSI-EXPT-6/assets/166278992/d34235a4-ae36-480e-bc55-c1ed9f8a0738)

## RESULT :
        The schematic and simulate inverter using CADENCE is done and verified successfully








