Exercise 1 - Valentin Rosar, 1479040

# Task 1:
Step 1: Added a plane is partially below the spheres. This leads to overlap of the farther away sphere and helps distinguish where the spheres are positioned in the room. (Depth Cue: Occlusion)

Step 2: Added a checkerboard material to the plane to give a sense of scale and perspective such that the size of the larger sphere can be estimated via the occlusion. The checkerboard material is using a shader graph that i managed to build with the help of ChatGPT. (Depth Cue: Linear Perspective)

Step 3: Added a light from above such that the small sphere casts a shadow onto the plane. This makes it possible to estimate the size and exact position of the small sphere in the space via its shadow on the checker board. (Depth Cue: Relative Size)

Note: Unfortunately i could not work out why the larger sphere does not cast any shadows, even though the light, shader and other conditions are the same for both spheres. However the effect remains clear in my opinion. 

# Task 2:
On the VR Side the floor was somehow tied to the camera tracking on the right eye while the floor for the left eye was stationary. The tilting and moving of my head left and right however correctly processed the depth between the two spheres and against the checkered floor i could observe the red sphere moving left and right while the blue sphere seemed stationary. This suggested my head that the blue sphere had to be way further back. The size difference could be perceived from the beginning without any changes. I do not know if this is intended or not. I just replaced the regular camera with the meta camera rig and the spheres became clearly distinguishable in their size when wearing the VR headset.