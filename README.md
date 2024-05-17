EXP.NO: 06 

# SCHEMATIC ENTRY AND CIRCUIT SIMULATION OF A CMOS INVERTER

AIM:  

To Simulate and Synthesis Inverter using CADENCE

APPARATUS REQUIRED: Cadence Virtuoso
 
PROCEDURE: 

Commands to get into Cadence

1.	Right Click and open the terminal window

2.	Type the following commands as follows and press enter.

i)	tcsh

ii)	source /home/install/cshrc

iii)	virtuoso 

Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”

2.	Close the 2nd window

3.	Use 1st window i.e virtuoso window(CIW) for further processing.

i)	Create a New Library

ii)	Create Schematic Cell view.

iii)	Create the Symbol for schematic Cell view.

iv)	Create the test Cell view.

v)	Analog simulation by spectre

Procedure for Creating New Library.

a)	File –New – Library

b)	Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK

c)	Attach the library to the technology library gpdk045.Click OK

Create Schematic Cell view.

a)	Go to 1st window i.e virtuoso(CIW)

b)	File-New-Cell view

c)	Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic

d)	Type: Schematic press OK

e)	Add the required components from the libraries and make the connections.

f)	Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos

g)	Analog library	Vdd, Gnd, Vcc, Vpulse, Vsin

h)	Make the connections by using fixed narrow wire key

i)	Click Check and Save button

Creating the Symbol for schematic Cell view

a.	In the schematic window, execute

Crate – Cell view – From Cell view

The cell view from cell view window appears

Check Lib Name, Cell Name, From View name must be schematic Press ok

b.	Now Symbol generation form appears. Click Ok If No changes required

c.	A new window with with default symbol is created.

d.	Edit the symbol if you want to give actual symbol shape else continue.

i.	Execute Create-Cell view-from cell view

ii.	Library Name and Cell Name must be same which you have used for schematic. Press OK

iii.	Check for the position of pin side.Prss OK

iv.	Edit for the shape by Create-Shape-Choose required options to edit.

Creating the new test cell view

a)	Go to CIW window, Execute File-New-Cell view

b)	Setup the new file form

Library: Select the one you a created.

Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test

View: Schematic

Type: Schematic  press OK

Analog simulation by SPECTRE.

a.	In test cell view window

i.	Launch – ADE L(Analog Design Environment)

b.	Execute Setup—Simulation/directory/Host A new window opens

c.	Set the simulation window to spectre and click ok

d.	Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.

e.	Execute Analysis – Choose. A window opens.

f.	Select the type and set the specifications and press OK

g.	Execute Output s—to be plotted – Select on Schematic

h.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

i.	Execute Simulation -- Net list and Run


INVERTER SCHEMATIC CELL VIEW:

![image](https://github.com/Karthikeyan8296/VLSI-EXP-6/assets/165583967/0bfab037-98c2-4183-af6b-b3c7d9f45984)

Specifications:  

Vpulse 	V1 = 0	Vdc	= 1 V2 = 1

td = 0,tr=tf=1 n, ton= 100n ,T=200n

Simulation Settings

Setup for transient analysis:

1.	Stop time =400n

Setup for D.C analysis

1.	Component to be selected in schematic is	for d.c analysis

2.	Start = -1 Stop = 1 resp.


EXPECTED WAVEFORM:
 
![Exp1](https://github.com/Karthikeyan8296/VLSI-EXP-6/assets/165583967/5d398013-c8e9-4dfa-9e36-213eef5e5293)





# SCHEMATIC ENTRY AND CIRCUIT SIMULATION OF A TWO INPUT NAND GATE

AIM:  

To Simulate and Synthesis Two input NAND gate using CADENCE

APPARATUS REQUIRED: Cadence Virtuoso
 
PROCEDURE: 

Commands to get into Cadence

1.	Right Click and open the terminal window

2.	Type the following commands as follows and press enter.

i)	tcsh

ii)	source /home/install/cshrc

iii)	virtuoso 

Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”

2.	Close the 2nd window

3.	Use 1st window i.e virtuoso window(CIW) for further processing.

i)	Create a New Library

ii)	Create Schematic Cell view.

iii)	Create the Symbol for schematic Cell view.

iv)	Create the test Cell view.

v)	Analog simulation by spectre

Procedure for Creating New Library.

a)	File –New – Library

b)	Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK

c)	Attach the library to the technology library gpdk045.Click OK

Create Schematic Cell view.

a)	Go to 1st window i.e virtuoso(CIW)

b)	File-New-Cell view

c)	Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic

d)	Type: Schematic press OK

e)	Add the required components from the libraries and make the connections.

f)	Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos

g)	Analog library	Vdd, Gnd, Vcc, Vpulse, Vsin

h)	Make the connections by using fixed narrow wire key

i)	Click Check and Save button

Creating the Symbol for schematic Cell view

a.	In the schematic window, execute

Crate – Cell view – From Cell view

The cell view from cell view window appears

Check Lib Name, Cell Name, From View name must be schematic Press ok

b.	Now Symbol generation form appears. Click Ok If No changes required

c.	A new window with with default symbol is created.

d.	Edit the symbol if you want to give actual symbol shape else continue.

i.	Execute Create-Cell view-from cell view

ii.	Library Name and Cell Name must be same which you have used for schematic. Press OK

iii.	Check for the position of pin side.Prss OK

iv.	Edit for the shape by Create-Shape-Choose required options to edit.

Creating the new test cell view

a)	Go to CIW window, Execute File-New-Cell view

b)	Setup the new file form

Library: Select the one you a created.

Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test

View: Schematic

Type: Schematic  press OK

Analog simulation by SPECTRE.

a.	In test cell view window

i.	Launch – ADE L(Analog Design Environment)

b.	Execute Setup—Simulation/directory/Host A new window opens

c.	Set the simulation window to spectre and click ok

d.	Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.

e.	Execute Analysis – Choose. A window opens.

f.	Select the type and set the specifications and press OK

g.	Execute Output s—to be plotted – Select on Schematic

h.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

i.	Execute Simulation -- Net list and Run


NAND SCHEMATIC CELL VIEW: 
 
![image](https://github.com/Karthikeyan8296/VLSI-EXP-6/assets/165583967/603d2812-0cd9-46fd-8247-2e6eaa12886d)

Specifications:  

Vpulse 	V1 = 0	Vdc	= 1 V2 = 1

td = 0,tr=tf=1 n, ton= 100n ,T=200n

Simulation Settings

Setup for transient analysis:

1.	Stop time =400n

Setup for D.C analysis

1.	Component to be selected in schematic is	for d.c analysis

2.	Start = -1 Stop = 1 resp.

EXPECTED WAVEFORM:

![Exp 2](https://github.com/Karthikeyan8296/VLSI-EXP-6/assets/165583967/bf191e59-3bf8-409d-a816-8ea89fb4c7a9)

# SCHEMATIC ENTRY AND CIRCUIT SIMULATION OF A TWO INPUT NOR GATE

AIM:  

To Simulate and Synthesis Two input NOR using CADENCE

APPARATUS REQUIRED: Cadence Virtuoso
 
PROCEDURE: 

Commands to get into Cadence

1.	Right Click and open the terminal window

2.	Type the following commands as follows and press enter.

i)	tcsh

ii)	source /home/install/cshrc

iii)	virtuoso 

Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”

2.	Close the 2nd window

3.	Use 1st window i.e virtuoso window(CIW) for further processing.

i)	Create a New Library

ii)	Create Schematic Cell view.

iii)	Create the Symbol for schematic Cell view.

iv)	Create the test Cell view.

v)	Analog simulation by spectre

Procedure for Creating New Library.

a)	File –New – Library

b)	Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK

c)	Attach the library to the technology library gpdk045.Click OK

Create Schematic Cell view.

a)	Go to 1st window i.e virtuoso(CIW)

b)	File-New-Cell view

c)	Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic

d)	Type: Schematic press OK

e)	Add the required components from the libraries and make the connections.

f)	Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos

g)	Analog library	Vdd, Gnd, Vcc, Vpulse, Vsin

h)	Make the connections by using fixed narrow wire key

i)	Click Check and Save button

Creating the Symbol for schematic Cell view

a.	In the schematic window, execute

Crate – Cell view – From Cell view

The cell view from cell view window appears

Check Lib Name, Cell Name, From View name must be schematic Press ok

b.	Now Symbol generation form appears. Click Ok If No changes required

c.	A new window with with default symbol is created.

d.	Edit the symbol if you want to give actual symbol shape else continue.

i.	Execute Create-Cell view-from cell view

ii.	Library Name and Cell Name must be same which you have used for schematic. Press OK

iii.	Check for the position of pin side.Prss OK

iv.	Edit for the shape by Create-Shape-Choose required options to edit.

Creating the new test cell view

a)	Go to CIW window, Execute File-New-Cell view

b)	Setup the new file form

Library: Select the one you a created.

Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test

View: Schematic

Type: Schematic  press OK

Analog simulation by SPECTRE.

a.	In test cell view window

i.	Launch – ADE L(Analog Design Environment)

b.	Execute Setup—Simulation/directory/Host A new window opens

c.	Set the simulation window to spectre and click ok

d.	Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.

e.	Execute Analysis – Choose. A window opens.

f.	Select the type and set the specifications and press OK

g.	Execute Output s—to be plotted – Select on Schematic

h.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

i.	Execute Simulation -- Net list and Run

NOR SCHEMATIC CELL VIEW: 

![image](https://github.com/Karthikeyan8296/VLSI-EXP-6/assets/165583967/5b8f312a-25b7-46a7-bb54-e32a8eb930ab)

Specifications:  

Vpulse 	V1 = 0	Vdc	= 1 V2 = 1

td = 0,tr=tf=1 n, ton= 100n ,T=200n

Simulation Settings

Setup for transient analysis:

1.	Stop time =400n

Setup for D.C analysis

1.	Component to be selected in schematic is	for d.c analysis

2.	Start = -1 Stop = 1 resp.

EXPECTED WAVEFORM:

![Exp 3 Karthik](https://github.com/Karthikeyan8296/VLSI-EXP-6/assets/165583967/1992bd54-0aef-46ee-8174-bb4d2af3ab4a)


RESULT:

The Simulate and Synthesis Inverter, Two input NAND gate, Two input NOR gate using CADENCE is successfully verified.
