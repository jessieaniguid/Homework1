# Homework1
PART A:

In this portion of the assignment, I made three cubes and placed three directional lights. The leftmost cube implements a basic phong shader and doesn't react to real time lighting. In the middle I made a vertex displacement shader that alters the cube's geometry in a way that makes it move up and down. Finally, I have a cube that applies a basic wooden texture. Unlike the phong shader, this shader reacts to changing light sources. 

For the lights, I have two directional lights simply rotating on their x and y axes. I also have another directional light that rotates around a world vertex and acts like a miniature sun. 


PART B:

In this part, I have a plane and plastered on it is an image of me drinking wine. I used a shader that takes a pixel's 8 nearby neighbours, adds theirs colors together, and divides their sum by 9. This essentially takes the average colors of a pixel's surrounding neighbourhood. This produces a blur like effect. 

For the mouse input I made use of the professor's mouse input script which reads the x position of the mouse. I then used that x position inside the shader as a multiplier to the effect. The more left the cursor is, the more definite the image. On the other hand, the more the cursor is to the right, the blurrier it gets.

PART C:

In this part of the project, I made adjustments to the code David gave during section. Aside from introducing three colors to the equation, one alteration I made was instead of instantiating the colors as black or white, I started with blue, red, and green. Additionally, I implemented a variation called tHigh life or THigh life. This is similar to the original game of life, except for two rules. First, if a horizontal line is formed containing the current cell, the current cell is dead. Second, whenever 4 individuals surround a living cell, that cell continues on to live. This creates similar movement that can be seen in Conway's game of life, but this movement appears in front of a complex maze like background. 