# EX No.3.2. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE: 02-11-2026
## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

### Step-1: Start Sketch command and Select the Plane  
1. Open Autodesk Fusion 360.
2. Create a new design file.
3. Click on Create Sketch.

<img width="296" height="370" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/54a4b3ef-fa06-4c57-b3d4-29d9c8dd4301" />

4. Select the Front(XZ) Plane.
### Step-2: Create the Curved Portion  
1. Select the Circle > Center Diameter Circle  tool from the Sketch toolbar.
2. Draw the circle of radius to 220 mm with origin as center.
3. Use the line tool to make the circle a semi circle and use the Trim tool to trim the unnecessary parts .
4. Select the Rectangle  tool.
5. Draw a rectangular opening at the centre of the curved portion.
6. Set the length to 120 mm and the width to 60 mm.
7. Use the Trim tool to cut the unnecessary parts.
8. Click Finish Sketch to complete the front profile. 

<img width="261" height="326" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/74917821-9b56-4bf4-88a6-8f16a94a155d" />
  
### Step-3: Extrude the Profile 
1. Select the Extrude command from the Solid toolbar.
2. Choose the profile.
3. Enter the extrusion distance as 150mm.
4. Press Enter to complete the extrusion.
	
<img width="454" height="806" alt="Screenshot      (82)" src="https://github.com/user-attachments/assets/e17af8fd-84b5-46ce-9379-6f5615628d12" />
	
### Step-4: Create a new Offset Plane
1. Click Construct > Offset plane from the solid toolbar.
2. Then select the Left(YZ) plane.
3. Set the offset distance to 60mm.
4. Press Enter.

<img width="374" height="665" alt="Screenshot      (83)" src="https://github.com/user-attachments/assets/a1bf8c9f-66ab-463b-948b-66b9bd2f6a88" />
	
### Step-5: Sketch on the new Offset Plane
1. Click Create Sketch and Select the newly created offset plane.
2. Select the Rectangle  tool.
3. Draw a Rectangle at the base of the surface
4. Set the length to 120 mm and the width to 30 mm.
5. Click Finish Sketch.
### Step-6: Extrude the Profile
1. Select the Extrude command from the Solid toolbar.
2. Select the rectangular sketch.
3. Enter 150 mm as the extrusion distance.
4. Press Enter to complete the extrusion.
### Step-7: Fillet
1. Click the Fillet from the solid toolbar.
2. Select the both sides from the rectangular profile that need to be filleted.
3. Type the fillet radius as 60 mm and press enter.

<img width="415" height="738" alt="Screenshot    (84)" src="https://github.com/user-attachments/assets/9fe3f6b2-1070-43c7-a99d-b37a3d487d15" />
  
### Step-8:  Create the Circular Hole 
1. Select Sketch > Create Sketch.
2. Choose the top surface of the side profile.
3. Select Circle > Center Diameter Circle.
4. Draw a circle of diameter of 40 mm at the center of the side profile.
5. Maintain an origin-to-centre distance of 150mm.

### Step-9: Mirror
1. Click Create > Mirror from the solid toolbar.
2. Select the profile at the side and select the left(YZ) plane as the mirror plane.
3. Press Enter to mirror.

<img width="454" height="806" alt="Screenshot      (82)" src="https://github.com/user-attachments/assets/9b95c41d-d623-4db1-b202-779fef72dfab" />
  
### Step-10: Create the Centre Hole

1. Select Sketch > Create Sketch.
2. Choose the top surface of the model as the sketch plane.
3. Select Circle > Center Diameter Circle.
4. Using the Center Diameter Circle tool ,draw a circle with origin as the centre.
5. Set its diameter to 20 mm.
6. Click Finish Sketch.

### Step-11: Extrude the Profile
1. Select the Extrude command from the Solid toolbar.
2. Select the circular sketch.
3. Change the operation to Cut.
4. Set the extent to Through All.
5. Press Enter to create the hole.
### Step-12: Create drawing file
1. Click File > New > Drawing
2. Place the required views of the projection.
3. Mark the dimensions.

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198823540-38a1b79a-1f68-4876-add9-adf59b98b386.png)

## OUTPUT:

<img width="1021" height="730" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/c993cd51-77ab-4702-a104-6fdf300d8c2e" />

<img width="928" height="663" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/9d645c35-44dc-41cd-93ee-406d99953352" />

## RESULT:
Thus, 3D model is created from orthographic projection.



