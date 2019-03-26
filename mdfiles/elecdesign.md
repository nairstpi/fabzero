## Electronic Design
For design of electronics circuit, we used predominantly the software called KiCAD 5.1.0-1. 
The steps involved in designing any typical circuit is narrated down below.  
- Open KiCAD and start new project in the appropriate directory as desired.  
- Select Schematic Layout Editor button, so that Eschema window will get popped up.  
- Use the place symbol option to include the required components of the circuit, the type of components depends shall be as per the lab inventory.  
- Connect the circuit components as per the diagram by opting place wire button.  
- Use no connection flags for unused pins if any. All these buttons can be invoked from the right panel or even from the menu options if desired so.  
- Annotate the unnumbered components automatically by using annotate button. (R? to R1, D? to D1 and so on).  
- If the circuit is complete and annotation is done, perform electrical rule check to ensure that there are no misconnections in the circuit, opted using the BUG button. Clear the errors if any.  
- Assign PCB footprint for the schematic symbols, footprint shall be as per lab inventory. Select Apply, save & Continue.    
- Generate Netlist by using the button.    
- Click the button Run 'PCBnew to Layout PCB'. This will convert the schema into layout and opens in new window.    
- Realign the components conveniently to house within the layout and replace the white connection lines by route tracks.  
- Use add file zone button or press B to fill GND in the entire circuits for F.Cu layer.  
- For Edge Cuts, use add graphic line button for drawing a outer box along the boundary. An yellow line appears along the boundary, select this line and give thickness as 0.8 mm. Why?  
- From the File menu, select Plot option and do the following mandatory setting.

- a. Plot format as SVG.  
- b. In Layer, F. Cu and Edge.Cuts shall only be selected.  
- c. In General Options, opt Negative plot, Check zone filling before plotting.

Plot Menu Window options

![Screenshot](/./img/plotmenu_sshot.png "Screenshot of Plot menu").

- Two .svg files gets created.  
- Open the SVG files and by pressing shift button, select only the required trace/cut image and proceed to export as .png files to a desired directory by selecting appropriate dpi. say @2000 pixels. (Please remember this dpi setting).    
- Open [fabmodules.org](http://fabmodules.org/ "fabmodules") and select the input trace file (.png) and output format as Roland Mill (.rml) and follow as below.  

    - a. PCB traces 1/64 as the process.   
    - b. In the input area options, ensure the selected dpi (KiCAD given value) and in the output area the machine selection as SRM-20.  
    - c. Set X0, Y0 & Z0 values to zero and all other fields to default while ensure the cut depth as 0.1 mm and tool diameter as 0.4 mm.
    - d. Press calculate and save the .rml file.  

- Select the input Outline/cut file (.png) and output format as Roland Mill (.rml) and proceed as follows.

    - PCB Outline 1/32.

    - In the input area options, ensure the dpi as above and to invert the image (heightmap logic).

    - Set X0, Y0 & Z0 values to zero and all other fields to default while ensure the cut depth as 0.6 mm, stock thickness as 1.7 mm. and tool diameter as 0.79 mm.

    - Press calculate and save the .rml file.

