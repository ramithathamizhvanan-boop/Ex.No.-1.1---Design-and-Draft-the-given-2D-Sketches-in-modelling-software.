# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.

## AIM

To sketch the given drawing with dimensions using fusion 360 tool.

## REQUIREMENTS

  1. Autodesk fusion 360
  2. Windows 10
  3. 16 GB of RAM (integrated graphics recommend 2 GB or more)
  4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
  
## PROCEDURE

1.Step 1: Initialize the Document and Units
Open Autodesk Fusion and start a blank project. Access the Document Settings panel on the left browser tree to confirm or change the active units to millimeters (mm). Click on Create Sketch and pick the XY Plane to enter the 2D drafting space centered around the origin.

<img width="713" height="963" alt="1" src="https://github.com/user-attachments/assets/b1827046-fed0-4c56-af5c-b7bfc20fe5a1" />

Step 2: Establish the Symmetry Axes
Activate the Line Tool (L) and switch on Construction mode in the Sketch Palette. Sketch two intersecting reference lines—one completely vertical and one horizontal—passing directly through the origin (0,0). These dashed lines will serve as alignment anchors to keep your geometry symmetrical.
<img width="531" height="700" alt="2" src="https://github.com/user-attachments/assets/0bada522-a56a-450b-8878-b2947658ce70" />

Step 3: Model the Central Hub and Spline Cutouts
Disable Construction mode to draw solid geometry. Create a pair of concentric circles centered at the origin with diameters of Ø40 mm and Ø66 mm. On the perimeter of the inner circle, sketch a smaller circle with a radius of R6 mm. Use the Circular Pattern tool to replicate this R6 mm circle 6 times around the origin point. Finally, use the Trim (T) tool to cut away the overlapping lines, forming the star-like internal spline profile.


<img width="816" height="492" alt="3" src="https://github.com/user-attachments/assets/1ba09adc-a868-4fdc-b9fb-0937ba66bab5" />


Step 4: Position and Draft the Outer Bosses
• Top Boss: Move 65 mm straight up from the origin along the vertical construction axis. Draw concentric circles with diameters of Ø20 mm and Ø32 mm.
• Bottom Boss: Move 50 mm straight down from the origin. Draw concentric circles measuring Ø10 mm and Ø20 mm.
• Side Bosses: Move 47 mm horizontally (both left and right) and 26 mm down from the origin. At these two coordinates, sketch concentric circles with an inner diameter of Ø14 mm and an outer diameter of Ø20 mm.

Step 5: Outline the Perimeter with Tangent Arcs
Bridge the gaps between the different bosses to create the outer boundary:
• Connect the central hub to the top boss using R64 mm arcs, ensuring you apply a Tangent Constraint to both ends of the arcs.
• Connect the central hub to the left and right side bosses using R20 mm tangent arcs.
• Use the remaining designated radii arcs to smoothly connect the side bosses to the bottom boss.


<img width="1080" height="491" alt="4" src="https://github.com/user-attachments/assets/4e6b2700-09c1-4a2a-88f1-0a853588595b" />


Step 6: Refine and Finalize the 2D Geometry
Select the Trim Tool (T) to snip away the internal overlapping curves of the outer circles and arcs, leaving a clean outer perimeter. Verify that all geometric constraints (especially tangents) are applied, ensuring the sketch turns fully black (fully constrained) and forms a sealed loop. Click Finish Sketch to exit the 2D environment.

<img width="829" height="366" alt="5" src="https://github.com/user-attachments/assets/812262b9-7f76-41c7-aa87-e48059a0e54a" />


Step 7: Generate the 3D Solid Body
Launch the Extrude (E) command from the Create menu. Click inside the main outer profile to select it, making sure to leave the central spline and the outer boss holes unselected. In the settings panel, input a thickness of 10 mm, verify the operation is set to New Body, and hit OK to render your completed 3D part.


<img width="686" height="694" alt="6" src="https://github.com/user-attachments/assets/65c811a2-f959-4d22-8b4a-a905bf1e417e" />


## OUTPUT


<img width="770" height="561" alt="Screenshot 2026-11-23 135419" src="https://github.com/user-attachments/assets/b1236054-7d9f-4766-885e-01e2a5315d14" />


<img width="691" height="537" alt="Screenshot 2026-11-23 135440" src="https://github.com/user-attachments/assets/db4df78a-db33-4c46-b1b5-bc0b7fc0701a" />



## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool.
