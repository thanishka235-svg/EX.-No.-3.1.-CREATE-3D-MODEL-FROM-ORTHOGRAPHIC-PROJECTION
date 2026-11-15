# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:

## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
Step 1: Create the Main Body (Fork Profile)
Start by sketching the side profile shown in the top-left view (when rotated upright) and extruding it to the overall width.
1. Start a Sketch: Select the Front (XZ) Plane and click Create Sketch.
2. Draw the U-Shape:
    1.Draw an outer rectangle 40 mm wide (11+18+11) and 52 mm tall.
    2.Inside the top edge, draw a cutout rectangle 18 mm wide (centered, leaving 11 mm walls on each side) and 41 mm deep (52-11 , leaving an 11 mm thick base at the bottom).

3.Finish Sketch & Extrude:
    1.Click Finish Sketch and select Extrude (E).
    2.Select the U-shaped profile and extrude it symmetrically (or one direction) to a depth of 32 mm (from the bottom-right view).

![image](https://user-images.githubusercontent.com/113594316/198551199-8d9b7f6c-6ea7-4d59-8e8c-173f2b5e088f.png)

Step 2: Round the Ends & Drill the Pin Holes
Next, shape the rounded tips of the two fork arms and create the through-holes.

1.Apply Fillets to the Arms:
      1.Select the Fillet tool (F).
      2.Select the 4 outer top vertical/horizontal edges at the tips of the two fork arms.
      3.Enter a radius of 16 mm (half of the 32 mm depth, which creates the full semicircle indicated by the R8 / concentric arc geometry—Note: if the outer radius matches the R16 outer width of 32 mm, use 16 mm for a full round; if following the labeled R8 strictly on corners, enter 8 mm instead. Looking at the isometric view, the outer tip is fully rounded with a 16 mm radius concentric to the Ø16 mm hole).

2.Sketch the Through-Hole:
        1.Select the outer flat side face of one of the fork arms and click Create Sketch.
        2.Draw a circle concentric with the rounded top edge (located 36 mm up from the bottom flat face of the fork base).
        3.Dimension the circle diameter to 16 mm (Ø16).

3.Cut the Hole:
       1.Click Finish Sketch and select Extrude (E).
       2.Select the 16 mm circle, set Operation to Cut, and set Extent Type to All so it cuts cleanly through both arms.

![image](https://user-images.githubusercontent.com/113594316/198551220-c7aa6694-4427-48e2-9d91-cd7e9615d651.png)

Step 3: Add the Cylindrical Shaft
Finally, add the cylindrical stem extending from the bottom center of the fork base.

1.Start a Sketch on the Bottom Face:
        1.Orbit to the bottom flat face of the U-shaped body, select it, and click Create Sketch.

2.Draw the Shaft Circle:
        1.Draw a circle at the exact center of the 40 mm × 32 mm rectangular face.
        2.Set the diameter to 18 mm (Ø18).
3.Extrude the Shaft:
        1.Click Finish Sketch and select Extrude (E).
        2.Select the 18 mm circle, set Operation to Join, and extrude it outward by 32 mm (this brings the total overall height to 

![image](https://user-images.githubusercontent.com/113594316/198551270-45875855-43a7-4471-af35-bd10cd9dd153.png)


![image](https://user-images.githubusercontent.com/113594316/198551370-54509915-ec69-4862-9c17-156d61a83b11.png)

## INPUT:

<img width="952" height="647" alt="Screenshot 2026-11-15 200456" src="https://github.com/user-attachments/assets/30d832ac-c20d-4f3d-9b47-0254c4c7ce50" />

## OUTPUT:

<img width="1013" height="710" alt="Screenshot 2026-11-15 200353" src="https://github.com/user-attachments/assets/3c75c606-2f79-40aa-a1c6-7231fbaee1e8" />

## RESULT:
Thus, 3D model is created from orthographic projection.
