# VLSI-LAB-EXP-6

# SCHEMATIC ENTRY AND SIMULATION OF CMOS INVERTER, CMOS NAND AND CMOS NOR USING CADENCE TOOL

# AIM: 
To design and simulate the CMOS inverter and observe the DC and transient responses using cadence tool.

# APPARATUS REQUIRED:
⦁ Laptop with MobaXterm
⦁ Cadence tool

# PROCEDURE:

# SCHEMATIC ENTRY:

# Creating a new library:
 ⦁ In the library manager, execute File - New library. The new library form appears. ⦁ In the new library form, type ‘my design lib’ in the name section. ⦁ In the field of directory section, verify that the path to the library is set to ~/Database / Cadence- analog – lab –bl3 and click ok. ⦁ In the next ‘technology file for new library form select option attach to an existing tech file and click ok. ⦁ In the ‘attach design library to technology file’ form, select gpdk045 form the cyclic field and click ok. ⦁ After creating a new library you can verify it from the library manager. ⦁ If you right click on the ‘my design lib’ and select properties, you will find that gpdk045 library is attached as techlib to ‘my design lib’.

 # Creating a schematic cell view:
⦁In the CIW or library manager, execute file – new – cell viw. ⦁ Setup the new file form as follows, Do not edit the library path file and the above might be different from the path shown in your form. ⦁ Click ok when done the above setting. A black schematic window for the inverter design appears.

# Adding components to schematic:
⦁ In the inverter schematic window, click the instance fixed menu icon to display the add instance form. ⦁ Click on the browse button. This opens up a library browser from which you can select components and the symbol view. ⦁ After you complete the add instance form move your cursor to the schematic window and click left to place a component. ⦁ This is a table of components for building the inverter schematic. ⦁ After entering components, click cancel in the add instance form or press ESC with your cursor in the schematic window
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/86bb3db0-34a5-4da9-8b97-0eba5b7be210)

# Adding pins to schematic:
⦁ Click the pin fixed menu icon in the schematic window. You can execute create pin or press ‘p’. ⦁ Add pin form appears. Type the following in the ADD pin form in the next order leaving space between the pin. ⦁ Select cancel and then the schematic window enter window file or press the f bind key.

# Saving the design:
Click the check and save icon in the schematic editor window observe CIW output for any errors.

# BUILDING THE INVERTER TEST DESIGN:

# Creating the inverter test cell view:
⦁ In the CIW or library manager, execute file – new – cell view. ⦁ Setup the newfile as shown below. ⦁ Click ok when done. A blank schematic window for the inverter test design appears. ⦁ Using the components list and properties/ comments in this table build the inverter test schematic. ⦁ Add the above components using create – instance or by pressing I. ⦁ Click the wire (narrow) icon and wire your schematic. ⦁ Click create wire name or press c to name the i/p (vsin) and output wires as in below schematic. ⦁ Click on the check and save icon to save the design.
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/52f46968-e1ac-464a-aad0-799bbdd5b8a1)

# ANALOG SIMULATION WITH SPECTRA:

# Starting the simulation environment:
⦁ In the Inverter-test schematic window execute launch – ADEL. The variable virtuoso analog design environment (ADE) simulation window appears. Choosing a simulator: ⦁ In the simulation window (ADE) execute setup – simulator / directory / host. ⦁ In the choosing simulator form, set the simulator field to specra and click ok. ⦁ In the simulation window (ADE) execute the setup model libraries. To complete, move the cursor and click ok.

# Choosing Analysis:
⦁ Click the choose- Analysis icon in the simulation window (ADE). ⦁ The choosing analysis form appears. ⦁ To Setup the transient analysis. ⦁ In the analysis section select tron. ⦁ Set the stop time as 100ns ⦁ Click at the moderate or enabled button and the bottom and then click apply. ⦁ To set for DC analysis ⦁ In the analysis section select DC. ⦁ Turn on save DC operating point. ⦁ Turn on the component parameters. ⦁ Double click the select Vpulse source or Type V0 (capital V zero). ⦁ Select the DC voltage in the select window parameter and click in the form start and stop voltages are 0 to 1.8. ⦁ Select the enable button and click apply and then click ok.

# Selecting output for plotting:
⦁ Execute the o/p’s to be plotted -select on sschematic in the simulation window. ⦁ Follow the prompt at the bottom. Click on the o/p net vout input vin of the inverter. Press esc with the cursor after selecting.

# Running the simulation:
⦁ Execute the simulation Netlist and run in the simulation window to start the simulation on the icon. This will create the netlist as well as run the simulation. ⦁ When the simulation finishes the transient and DC plots automatically will be popped up along with netlist.
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/13542dac-0317-4ba4-b9b0-af101817c28e)

![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/51193adc-31dc-48dc-9aa1-1f4308149ca0)

# CMOS NAND GATE NAND SCHEMATIC
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/f6e7c8b7-b17c-4148-8882-e163e0d2ecf7)

# NAND TEST CELL VIEW
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/cda881b3-3d72-43c8-bf65-0601059b2ca9)

# NAND SIMULATION WITH SPECTRA
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/6e7b2803-a3f0-4b8c-8b28-3f7c95e0d6e5)

# CMOS NOR GATE NOR SCHEMATIC
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/d6b11339-07cc-4388-ab5d-5566b7a10ef5)

# NOR TEST CELL VIEW
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/689e934e-bd17-4ba0-a6f1-a80b62287422)

# NOR SIMULATION WITH SPECTRA
![image](https://github.com/prithyusha/VLSI-LAB-EXP-6/assets/159164885/f3a16798-3e9d-4b69-85cd-0a21be237c16)

# RESULT:
Thus the design and simulation the CMOS inverter and observe the DC and transient responses using cadence tool is verified successfully.

