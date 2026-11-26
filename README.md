# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
To construct a precise 2D CAD/engineering drawing of the symmetric
mechanical flange profile using standard drafting primitives (circles, tangent lines,
fillets, and arrayed features) according to the specified dimensions.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
 
 ## PROCEDURE

 Step 1: Set Up Reference Axes & Base Grid
 
 1. Draw primary vertical and horizontal centerline axes intersecting at the
origin
2. Offset the main vertical centerline to the left and right by 50𝑚𝑚 (0, 0) . to
establish parallel centerlines at 𝑥 =− 50 𝑥=+50 and .
3. Offset the main horizontal centerline up and down by 60𝑚𝑚 to establish
horizontal lines at 𝑦 =+ 60 and 𝑦=−60 .
4. Mark the 6 outer hole centers:
   * **Top-left:** (− 50, 60)
   * **Top-right:** (50, 60)
   *  **Middle-left:** (−70,0)(offset 20𝑚𝑚 further left from 𝑥=−50)
   *  **Middle-right:** (70,0) (offset 20𝑚𝑚 further right from 𝑥=+50 )
   *  **Bottom-left:** (−50,−60)
   *  **Bottom-right:** (50,−60)
  
   <img width="460" height="756" alt="image" src="https://github.com/user-attachments/assets/29a81df4-e274-4eb1-a34c-996a7e865818" />

 Step 2:Draw Central Geometry
 
1.From center origin (0,0):
* Draw the innermost circle with radius 𝑅16
* Draw concentric reference circles with radii **R21 **, **R32 **, and **R40 **.

2. Construct the central web pattern:

* Draw vertical parallel offset lines at 𝑥 =± 3 (total gap width 𝑅40 6𝑚𝑚 ) through
the center.
* Construct 6 radial slots/spokes within the annular region between ** 𝑅21 ** and
** 𝑅32 **.

<img width="423" height="580" alt="image" src="https://github.com/user-attachments/assets/39c8968b-75a1-4053-a6e2-9f73ba325ed9" />

Step 3:Construct Outer Circular Features

1. **Hole Circles:**
Draw circles of radius ** 𝑅15 ** at all 6 outer center points.

2. **Outer Bosses:**
* At top-left (−50,60) , top-right (50,60) , bottom-left(50,60) , and bottom-right
(50,−60), draw outer arcs of radius ** 𝑅21 **.

* At middle-left (−70,0) and middle-right (70,0) , draw outer concentric circles of
radius **𝑅20 **.

Step 4:Connect Tangent Lines & Fillets

1. *Outer Straight Tangents:* Draw straight line segments tangent to the outer
arcs connecting:
* Top-left arc (𝑅21) to middle-left arc (𝑅20).
* Bottom-left arc (𝑅21) to middle-left arc (𝑅20).
* Top-right arc (𝑅21) to middle-right arc (𝑅20).
*  Bottom-right arc (𝑅21) to middle-right arc (𝑅20).

2. *Top & Bottom Inner Fillets:*
* Create internal tangent fillets of radius *𝑅20* connecting the top-left arc (𝑅21)
and top-right arc (𝑅21), resting smoothly against the central *𝑅40* boundary.
* Create identical *𝑅20* internal fillets at the bottom connecting the bottom-left
arc (𝑅21) and bottom-right arc (𝑅21)

<img width="455" height="647" alt="image" src="https://github.com/user-attachments/assets/b486c797-a824-4d52-b07e-5dd38347f82f" />

Step 5:Final Cleanup & Dimensioning

1. Trim all overlapping construction geometry to leave a clean outer boundary
and inner features.
2. Apply centerlines, dimensions, hatch/shading, and radius annotations
matching the technical drawing.

 ## OUTPUT

 <img width="996" height="648" alt="image" src="https://github.com/user-attachments/assets/f28f7ff3-5926-4a8e-934e-aa485a3e7394" />
<br>
 <img width="912" height="651" alt="image" src="https://github.com/user-attachments/assets/f6edc4c6-d915-4b02-aeff-92ac415764c8" />

 ## RESULT
 Thus the given sketch is drawn and drafted using fusion 360 tool.
