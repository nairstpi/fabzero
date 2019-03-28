## PCB Preparation
Milling the designed Printed Circuit Board (PCB) will be done through the use of mini CNC milling machine. The one we have in our lab is MonoFab DGSHAPE SRM-20, the pictorial representation of the same is given below. 
![DGSHAPE SRM-20](/./img/dgshape_srm20.png "SRM-20")

The SRM-20 portable milling machine can mill a broad range of materials, including modeling wax, chemical wood, foam, acrylic, poly acetate, ABS and PC board. 

The X, Y and Z strokes for the machine are 8, 6 & 2.38 inches respectively and the workpiece table size can be 9.14(X) and 6.17(Y) inches weighing upto 2 Kgms. The maximum distance from the collet tip to the table is 5.15 inches. The X, Y and Z axis drive systems are controlled by stepper motor, whereas the spindle motor is DC motor and the speed of the spindle varies from 3000 to 7000 rpm.

The milling process is commanded through the 'V-Panel toolbar for the SRM-20' software installed in the connected system. The following are the steps to accomplish the milling process.
- For printing the trace, the milling bit has to be selected as 1/64. 
- Just fit the milling bit to the spindle, not so tightly. 
- Approximately, the X, the largest axis of the machine, and Y axis has to be moved through the V-Panel to the coordinates where the milling has to be started.
- Now carefully loosen the bit and make it to touch the milling platform and with a little force against the platform, tight the bit and set the Z axis to zero. 
- Comfortably move the X, Y axis to the exact starting co-ordinate, where milling is to be done, by lifting the Z axis by 2mm. At this position set the X, Y axis to zero.

![Screenshot of the V-Panel for the origin set](/./img/vpanel_origin.png)

- By selecting the cut option, load the trace file in .rml format, ensure the previous files if any, and then give the command to mill the trace by using the output option in the window pop up. 
- Once the milling of the traces is completed, replace the bit with 1/32 as earlier.
- Now set the Z axis to zero, similar to the previous setting. 
- Make the X, Y axis to the previous starting co-ordinate, by opting the Move To Origin button.
- Load the cut file in .rml format and give the command to mill the outline as above.
- Remove the bit and place the bits in the appropriate enclosures meant for it.
- Now the printed PCB may be carefully removed by slightly lifting along the sides by using a screw-driver.


![](/./img/milled_pcb.png)

Snapshot of the PCB I have designed using KiCAD is shown above, which is unique and not the one shared by the mentor Sibu.