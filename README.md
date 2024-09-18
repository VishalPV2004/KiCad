# KiCad
I love designing PCBs for embedded systems and IOT applications, here I used a student, beginner-friendly PCB tool KiCAD to make my designs

# Introduction 
![KiCadIntro](https://github.com/user-attachments/assets/3d40ceb4-51dc-471f-ab5c-c16cb9b88ab5)

### Left panel : 
+ New Project option is used to create a new project
+ Open Project is used to open an existing project
+ Sch files can be archived and unarchived by the next two options.
+ Used to refresh the app
+ Last option is used to trace back the directory of the current project.

### Right panel : 
+ Schematic Editor - used to edit/create schematics
+ Symbol Editor - used to edit/create our own symbols of schematics
+ PCB Editor - facilitates the desiging of PCB editing
+ Footprint Editor - used to create footprint of our own design
+ Gerber viewer - provides the facility to view the final product before sending to manufacturer
+ Image Converter - used to place logos, images on our design to make it custom
+ Calculator Tools - used to color code the resistor, calculate track width, via size, electrical spacing
+ Drawing Sheet Editor - used to provide documentation of the project like name, organizations
+ Plugin and Content Manager - used to get third party features which is updated by the developers  

# Schematic Editor
![SchematicEditor](https://github.com/user-attachments/assets/7bcb354e-1660-4f4a-a6f0-0e7be2eae388)

### Bottom pane : (L -> R)
+ Zoom in and Zoom out can be done using scroller, Z variable signifies the magnitude of how much it is being zoomed in
+ X and Y variables represent the position of the crosshair on the screen
+ dx, dy, dist are used to measure the distance from one point to another
+ 
   ↳ Place the cursor at source point, press space, now navigate to the destination point, the distance will be shown there.

### Left pane : (T -> B)
+ Show Grid - used to enable or disable grids while designing
+ Grid Overrides - used to customize the grid settings for individual layers or specific objects within a PCB design
+ Below 3 are used to set the unit for measurement, it could be inches, mils or millimeters.
+ Full-window crosshair - used to enable full screen crosshair
+ Show hidden pins - used to show the hidden pins, mostly of the power flag
+ Below 3 are used to modify the angle at which the wire cuts, it could be 90, 45 or customized
+ Annotate automatically - used to name components automatically like u1,u2...usually turned off, bcoz when I remove any element, I dont want any discontinuity in numbers
+ Hierarchy Navigator - used to manage multiple schematic sheets together, used while desinging larger desings
+ Properties Manager - used to display the properties of the specific selected component in design
