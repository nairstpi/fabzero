## Designing of 3D Objects & Printing

### Designing:

FreeCAD is the software used in our training for designing the 3D structures/objects. The basic usage of the software was explained to us by Francisco. All of us installed the latest version of the FreeCAD software and started creating objects. Few assignments were given to us to design some handy objects needed for the lab equipment and the object which I got to make is a small stand for placing the milling bit, to be used by SRM-20 milling machine. The steps I followed for designing the same is captured and narrated infra.

- Open FreeCAD and create an empty document.
- From the workbench dropdown menu, select Part and the part tools panel will appear.
- For the bit stand, I have selected a cube for the base of the stand, measuring L(50), W(28.5) & H(10), all in mm.
- Copy and paste another cube with measurement as L(50), W(13.5) & H(15) amd move to the center of the base cube in Y axis and on the top of the base cube in Z axis.
- Chamfer is also created at this stage, as it would be difficult to create this after applying fillets.
- To make the cubes more appealing without sharp edges, fillets are applied by selecting the cubes and the edges to be smoothened. Here it is good to notice that filleted shapes will be named in the left panel as fillet and fillet001. It is better to apply fillets after making the entire object. 
- Now to make the entire shapes as one, select boolean and union between the above made fillets. Now the entire shape would appear as fusion.
- In order to create the holes for the milling bit, pick cylinder and set the radius as 1.75 mm ( slightly higher than the radius of the bit-3mm) and height as 15 mm. Consider the error of the machine as well which could be around 3 to 5 %.
- Move the cylinder in Z axis for 10 mm and in Y axis for 14.25, at the center of the base cube of 28.5mm.
- Create four more cylinders of same dimensions, move the cylinders to 5mm, 15mm, 25mm, 35mm, 45mm in the X axis.
- Run boolean operation of difference between the fusion created at step 10 above and the cylinders just created, now we have cut, cut001, cut002, cut003 and cut004 respectively.
- Now the design is ready for printing. Final design for printing may be see [**_here._**](/./img/bitstand_sshot.png)

### Printing

We use **Sindoh** make **3DWOX DP200** model printer for printing the 3D objects or designs. Mentor Francisco explained the basic functionality of how to use this printer. 

3DWOX DP200 is a good user-friendly printer having features like assisted bed levelling, auto filament loading, print monitoring, user safety and convenience, 5" touch panel with intuitive GUI and a wide range of connectivity options like USB, LAN and Wifi. Details with specifications can be viewed by clicking [**_here._**](https://3dprinter.sindoh.com/product/dp200 "3DWOX DP200 Specifications")

![Sindoh 3DWOX DP200](/./img/3dwox_dp200.png "3DWOX DP200")

