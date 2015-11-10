# edgeLord.py
A simple Maya Python script for aligning vertex normals to an edge loop, for use with edge wear decals.

It works by taking an edge loop and going through each vertex in the loop and aligning the perpendicular verticles to the active vertex. 
This ensures that the normals point in the same direction which helps with shading on normal mapped decals along edges.

To use; Place the script in your Maya scripts folder and call it using:

import edgeLord

edgeLord.run()

This readme currently sucks, so for more details on the technique and images of the effect in action look at this thread:
http://polycount.com/discussion/160770/normals-from-edgeloop-s-script-for-those-lovely-edge-decals
