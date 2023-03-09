# 3D-Graphics-Modelling
This repository contains a 1 min animation done for the master's course 3D Graphics &amp; Modelling, while being on Erasmus.

First of all, I imported the 3D model of the UCC. 
Then, I created my first character, Supreme Leader Snoke. For this, I sculpted his face,
taking into account his facial features, like scars. The eyes were added separately.
After sculpting, came his body, which was made from a cube. The cube was subdivided, and then 
the shape was grabbed from above to obtain a more oval form. 
After this, the surface was smoothed. I used mirroring for left and right. I cut two holes for the arms, 
from which I made extrusion. I did not construct fingers separately but formed mitten hands instead. 
I also created legs in the same manner as the arms, but in the meantime, I realised that I would probably
use a long robe instead, made from a cone. 
Finally, I added a basic humanoid armature, discarding the unnecessary bones and adding some where
it was necessary. In order to behave properly, I assigned automatic weights for the bones and tested
whether they work correctly.
My second character is Luke Skywalker. His face was sculpted from a cube, which was subdivided. After
I formed his skull, I created holes for his eyes, then added his eyeballs. I added a neck and I formed 
his nose and mouth afterwards and finally created his ears. I added corresponding materials for the 
eyes and skin. I added some hair as well, which needed to be combed to obtain a realistic aspect. When
the head was ready, I created the body of Luke, starting from a cube, making subdivisions. The body was
mirrored, so I could work more easily and symmetrical. I created the body and added armature in the 
same manner as before. I also added a laser sword to Luke. I had to correct by weight paint the part
which would move with the swords.
In the next step, I created some 3d text with some simple effects like extruding. The title is composed
of two different texts to obtain a more interesting aspect, one built in the other.
I divided my project in different scenes, so I could work easier with different objects.
I used 3-point lighting for illuminating the title and for Snoke as well when he is showed alone, declaring
attack. This lighting technique offers a good illumination for the model, acting from 3 different positions,
key light being the strongest. The other ones are the fill light from the other side and dim light from
behind.
To place the clock image in the right position, I UV unwrapped the shape which corresponded to it and then
applied the image as a texture. (source: https://thegraphicsfairy.com/clock-face/)
For the walls of the UCC building, I used bump mapping. First I took an image from 
https://pixabay.com/photos of bricks and then changed the black and white contrast and applied it to the
texture to obtain a more realistic effect. The image for the roof was taken from 
http://www.imageafter.com/image.php?image=b3_walls095.jpg&download=no
Other materials were taken from BlenderKit.
Procedural texturing was used for the pillars, which is more visible in the last scene, where Luke attacks
Snoke by his sword.
I used inverse kinematics to animate a step of my character, Luke. I put inverse kinematics bones to
Luke's heels and knees.
I animated the scenes separately and then rendered images for them. Finally, these images were put together
in the video sequencer (of the 3. Scene)

Storyline:
The title comes in first, getting bigger.
Supreme Leader Snoke is presented who waves his hand as declaring attack.
The main scene is presented, the UCC main campus, along with the other main character, Luke Skywalker.
As a fine detail, the time is also presented on the building clock.
Snoke attacks Skywalker from behind, coming through the gate. Luke turns around.
Luke starts to chase Snoke and manages to lead him in a corner, between pillars.
Luke attacks snoke with his sword and Snoke is covered in smoke.
Snoke disappears.
The End
