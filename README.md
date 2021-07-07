# 3D Objects Simulation
- The project is based on modeling as well as the movement of 3D objects like cube, cuboid, and pyramid when linear transformations are applied to them. The project illustrates the implementation of different transformations such as rotation, shearing, translation, shearing, mirroring, scaling, and the inverse of these transformations.

- Although there are many projects available and developed where these operations are performed these are automated but we have taken into consideration the user’s input and the program creates the object as per the input by the user about the object choice, vertices of the objects as well as the value of factors involved in the transformations as per the user choice. Our program allows the user to see the real-time effects of the transformations chosen by the user in the previous step. This also makes users understand how these transformations work and make the user crystal clear about the linear algebra concepts which are used to develop and apply these types of transformations as well as the effect of SVD and inverse of a transformation.




## Run Locally

Clone the project

```bash
  git clone https://github.com/gauravbajaj27/3D_Object_Simulation
```

Go to the project directory

```bash
  cd 3D_Object_Simulation
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
jupyter notebook
```
Open 3D_Object_Simulation.ipynb and select Kernel>Restart & Run All

  
## Features and working of the application
Following are the instructions to perform linear transformations on the 3D Object:

### **1. Commands for transformation in cube:** 

**a. Rotation by rotation angle 1.0 degrees in respective directions**

- "I" - Rotated in X direction

- "J" - Rotated in Y direction

- "K" - Rotated in Z direction

**b. Mirroring relative to respective planes**

- "F" - Reflection relative to XY plane

- "G" - Reflection relative to YZ plane

- "H" - Reflection relative to ZX plane

**c. Translation by 0.5 units in respective directions**

- "A" - Translate left

- "D" - Translate right

- "W" - Translate up

- "S" - Translate Down

- "Mouse Wheel Down" - Translate Back

- "Mouse Wheel Up" - Translate Forward

**d. Shearing by shearing factor 1.0**

- "B" - Sheared in X direction

- "N" - Sheared in Y direction

- "M" - Sheared in Z direction

**e. Scaling by scaling factor 2.0**

- "X" - Scaled in X direction

- "Y" - Scaled in Y direction

- "Z" - Scaled in Z direction

**f. Restore your object to original co-ordinates by pressing R**

**g. Undo the latest transformation by pressing U**

**h. See SVD in real-time by pressing Q key**

**i. "ESCAPE"- Exit**  

### **2. Commands for transformation in cuboid:** 

**a. Rotation by rotation angle 1.0 degrees in respective directions**

- "I" - Rotated in X direction

- "J" - Rotated in Y direction

- "K" - Rotated in Z direction

**b. Mirroring relative to respective planes**

- "F" - Reflection relative to XY plane

- "G" - Reflection relative to YZ plane

- "H" - Reflection relative to ZX plane

**c. Translation by 0.5 units in respective directions**

- "A" - Translate left

- "D" - Translate right

- "W" - Translate up

- "S" - Translate Down

- "Mouse Wheel Down" - Translate Back

- "Mouse Wheel Up" - Translate Forward

**d. Shearing by shearing factor 1.0**

- "B" - Sheared in X direction

- "N" - Sheared in Y direction

- "M" - Sheared in Z direction

**e. Scaling by scaling factor 2.0**

- "X" - Scaled in X direction

- "Y" - Scaled in Y direction

- "Z" - Scaled in Z direction

**f. Restore your object to original co-ordinates by pressing R**

**g. Undo the latest transformation by pressing U**

**h. See SVD in real-time by pressing Q key**

**i. "ESCAPE"- Exit**
 

### **3. Commands for transformation in pyramid:**

**a. Rotation by rotation angle 1.0 degree(Defualt) in respective directions**
    
"I" - Rotated in X direction

"J" - Rotated in Y direction

"K" - Rotated in Z direction

**b. Mirroring relative to respective planes**
  
"F" - Reflection relative to XY plane

"G" - Reflection relative to YZ plane

"H" - Reflection relative to ZX plane

**c. Translation by 0.5 units(Default) in respective directions**

"A" - Translate left

"D" - Translate right

"W" - Translate up

"S" - Translate Down

"Mouse Wheel Down" - Translate Back

"Mouse Wheel Up" - Translate Forward

**d. Shearing by shearing factor 1.0 (default)**

"B" - Sheared in X direction

"N" - Sheared in Y direction

"M" - Sheared in Z direction

**e. Scaling by scaling factor 2.0 (default)**

"X" - Scaled in X direction

"Y" - Scaled in Y direction

"Z" - Scaled in Z direction

**f. Restore your object to original co-ordinates by pressing R**

**g. Undo the latest transformation by pressing U**

**h. See SVD in real-time by pressing Q key**

**i. "ESCAPE"- Exit** 

### **Below is the screenshot of working of the application:**

Performing transformations on cube
![GIF-1](Images/cuboid_transformations.gif)


## Documentation

Below is the detailed report containing information about the transformations that can be applied on 3D objects in the simulation and the algorithms used behind them.

[Project Report](https://drive.google.com/file/d/14e-WJjNQoJzTlzzu07TPJnn8Qk-l_hAX/view?usp=sharing)

  
## Authors

- [Gaurav Bajaj](https://github.com/gauravbajaj27)
- [Shubham Jain](https://github.com/Jimmy290901)
- [Hirmay Sandesara](https://github.com/Hirmay)
- [Homak Patel](https://github.com/Homak-Patel)


  
