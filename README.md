# E05b-Physics
Exploring 2D physics and collisions.

In main1.py I added in gravity so that the balls just fall. To add gravity, you make x=0 so it only applies accleration on the y-axis. Then set y equal to any negative number. The higher the number, the stronger the gravity. 

In main2.py, the goal was to reverse the velocity of the ball when it hits the wall so it makes the balls continue moving, just in a different direction.

*main3.py* implements the worst, most-naive version of collision physics using the built-in sprite collision detection. Assuming all the animal heads have the same mass, adjust lines 53–60 to make the collisions more realistic.

