# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.

## AIM

To sketch the given drawing with dimensions using fusion 360 tool.

## REQUIREMENTS

  1. Autodesk fusion 360
  2. Windows 10
  3. 16 GB of RAM (integrated graphics recommend 2 GB or more)
  4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
  
## PROCEDURE
1. Set Up the Base Circles

• Create a Sketch: Click Create Sketch on the top toolbar and select the XY Plane.
• Draw Center Circles: Use the Center Diameter Circle (C) tool at the origin (0,0) to draw two concentric circles with diameters of 40.00 mm and 66.00 mm.
• Draw the Top Boss: Draw a vertical construction line (L + X) straight up from the origin with a length of 65.00 mm. At the top endpoint, draw two concentric circles with diameters of 20.00 mm and 32.00 mm.

2. Create the Lower-Right Cutout and Bosses

• Locate the Bottom-Center Boss: Draw a vertical construction line straight down from the origin with a length of 50.00 mm. At the bottom endpoint, draw two concentric circles with diameters of 10.00 mm (inner hole, matching the lower-right boss) and 20.00 mm (outer boss).
• Locate the Lower-Right Boss: From the center of the bottom-center boss, draw a horizontal construction line to the right with a length of 47.00 mm, then go straight up 24.00 mm. At this endpoint, draw two concentric circles with diameters of 10.00 mm and 20.00 mm.
• Create the Bottom Cutout Arc: Draw a circle with a diameter of 40.00 mm (radius 20 mm) positioned between the bottom-center boss and the lower-right boss. Apply Tangent constraints so it smoothly touches the 20.00 mm outer circle of the bottom-center boss and the 20.00 mm outer circle of the lower-right boss, then use Trim (T) to remove the excess arc.

3. Add Outer Connecting Arcs and Pattern

• Draw Side Tangent Arcs: Use the 3-Point Arc tool to connect the 32.00 mm top outer circle to the 20.00 mm lower-right outer circle. Apply a Tangent constraint at both ends and set the arc diameter to 40.00 mm (radius 20.00 mm).
• Mirror to the Left Side: Select the lower-right boss circles, the bottom cutout arc, and the side tangent arc. Use the Mirror tool across the vertical center axis to duplicate the exact geometry onto the left side.
• Trim the Outer Profile: Use the Trim (T) tool to clean up any overlapping inner segments of the 66.00 mm base circle so the outer perimeter forms one continuous closed loop.
<img width="237" height="453" alt="WhatsApp Image 2026-11-11 at 10 19 53 PM" src="https://github.com/user-attachments/assets/e8825f3c-2756-4344-8332-054244b972a6" />


4. Create the Inner Center Notches

• Draw One Notch: Zoom into the 40.00 mm center circle. Place a point on its perimeter and draw a circle with a diameter of 12.00 mm (radius 6 mm).
• Pattern the Notches: Go to Create > Circular Pattern, select the 12.00 mm circle as the object, and select the center origin as the Center Point. Set the quantity to 6 and click OK.
• Trim the Inner Profile: Use the Trim (T) tool to remove the outer halves of the six 12.00 mm circles and the inner circle segments between them, leaving the scalloped inner hub.
<img width="267" height="346" alt="WhatsApp Image 2026-11-11 at 10 18 31 PM" src="https://github.com/user-attachments/assets/24976f19-8898-4308-a86f-bd0416ee2a46" />

5. Finalize the Sketch

• Check Constraints: Confirm that all sketch lines have turned from blue to black, indicating the profile is fully constrained.
• Extrude (Optional): Click Finish Sketch, press E for Extrude, select the shaded inner profile, and pull it to your desired thickness to turn it into a 3D part.
<img width="382" height="165" alt="WhatsApp Image 2026-11-11 at 10 29 48 PM" src="https://github.com/user-attachments/assets/59d2a3e1-39e7-43ec-9b8a-e5dd45ed0da8" />





## SKETCHS
<img width="939" height="721" alt="49b2d811-85d4-40f0-9087-2ffaa817fc70" src="https://github.com/user-attachments/assets/c94c552c-f59a-4d43-b50f-09668ea2c3c1" />


## OUTPUT
<img width="648" height="734" alt="Screenshot 2026-11-11 223340" src="https://github.com/user-attachments/assets/30795950-13b6-44c3-9589-308f9522ab00" />
<img width="966" height="682" alt="Screenshot 2026-11-11 222948" src="https://github.com/user-attachments/assets/3a875484-f111-4f09-826e-749b823f51eb" />


## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool.
