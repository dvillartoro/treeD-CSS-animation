# treeD-CSS-animation
A 3D animation using only CSS

I wanted to show some CSS animation or a projects including perspectives, so I decided to create some Minecraft blocks to build something bigger. In this case: a 3D tree.

We first create a basic cube. Taking advantage of before and after properties we can create three faces in a single layer and build a cube with only two layers. This is not necessary but it reduces the number of HTML elements having a cleaner code.

We add textures for each block: wood, leaves, stone...

We also generate a 3D grid css classes that will help us to handle the blocks easily. Dividing our space into 15 parts each axis we can place the block (x, y, z)=(0,0,1) just on top of the block (x, y, z)=(0, 0.1), for instance.

Finally we add some additional details:

 - A special top texture for wooden blocks.
 - Some grass decorating the floor.
 - Two additional layers to make fluffier leaves blocks.
 - A small butterfly flapping in th air.
 - 
It only remains to add an inmersive animation for the environment created.
