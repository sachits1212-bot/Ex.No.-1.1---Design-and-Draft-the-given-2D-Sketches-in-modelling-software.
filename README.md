# Ex.No.-1.1
# Design and Draft the given 2D Sketches in modelling software.

## AIM

To create a fully constrained 2D sketch of the given mechanical component using Autodesk 
Fusion 360 by applying the specified dimensions, geometric constraints, and dimensional 
relationships accurately. 

## REQUIREMENTS

Hardware:  
* Processor: Intel Core i3 or above  
* RAM: Minimum 4 GB 
* Hard Disk: Minimum 10 GB free space 
* Monitor: 14-inch or larger display  
* Input Devices: Standard keyboard and 3-button mouse

Software:  
* Operating System: Windows 10/11 (64-bit) or macOS  
* Software: Autodesk Fusion 360 – Educational/Commercial License
  
## PROCEDURE:

Step 1: Create New Design and Set Units Launch Autodesk Fusion and open a new design. 
Check the Document Settings and set the units to mm. Select Create Sketch and choose the 
XY Plane. The sketch environment with the origin is then displayed. 

<img width="427" height="456" alt="Screenshot 2026-10-10 134636" src="https://github.com/user-attachments/assets/64e5985b-ccde-4a84-a21b-9f458fb9b0d1" />

Step 2: Draw Reference/Construction Lines Choose the Line Tool (L) and turn on Construction 
mode. Draw one vertical and one horizontal construction line through the origin (0,0). These 
reference lines are used to maintain symmetry and accurately locate the different features

<img width="305" height="395" alt="Screenshot 2026-10-10 134652" src="https://github.com/user-attachments/assets/235ca27e-8779-4908-9780-9da77df3e867" />

.Step 3: Construct the Main Hub and Internal Pattern Turn off Construction mode and create two 
concentric circles at the origin having Ø40 mm and Ø66 mm. Draw an R6 mm circle on the inner 
circle and create a circular pattern of 6 instances about the origin. Trim the unwanted portions to 
obtain the required internal spline/cutout arrangement. 

Step 4: Add the Main and Side Bosses Locate the upper boss at 65 mm above      the origin 
and draw concentric circles of Ø20 mm and Ø32 mm. Locate the lower   boss 50 mm below the 
origin and draw Ø10 mm and Ø20 mm circles. Position the side bosses at 47 mm horizontally 
and 26 mm below the origin, with inner Ø14 mm and outer Ø20 mm circles. 

<img width="413" height="391" alt="Screenshot 2026-10-10 134716" src="https://github.com/user-attachments/assets/4339deed-23d6-45db-a47f-0853d3f8a769" />

Step 5: Form the Outer Profile Using Arcs Create connecting arcs between the central hub and 
the upper boss using R64 mm arcs and apply tangent constraints. Similarly, connect the central 
hub with the left and right bosses using R20 mm tangent arcs. Add the required connecting arcs 
between the side bosses and bottom boss with the specified radii.  

Step 6: Clean and Complete the Sketch Use the Trim Tool (T) to remove unnecessary portions 
of circles and arcs. Check the dimensions, alignment, symmetry, and tangent constraints. 
Ensure that the required profile is closed and fully constrained, then select Finish Sketch.

Step 7: Extrude the Completed Profile Select Create → Extrude (E) and choose the required 
closed profile. Exclude the internal holes and cutouts from the selected region. Enter the 
required thickness, such as 10 mm, select New Body, and click OK to obtain the final 3D componend

## RESULT
<img width="751" height="542" alt="Screenshot 2026-10-10 134744" src="https://github.com/user-attachments/assets/df230cca-0d43-412b-8755-3721e614bdd5" />
<img width="1012" height="725" alt="Screenshot 2026-10-10 134020" src="https://github.com/user-attachments/assets/d3cac2c2-3a98-4b07-a791-7c81447fe24a" />

