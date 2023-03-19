**ARCTOS custom version**

This is a 6 axis version of grbl implemented in Arctus 3D printed robotic arm. Tested in open-loop mode without a gripper.
It runs on Arduino MEGA, other boards are not supported for now.  
Axes are named as X,Y,Z,A,B,C. First two axis runs in normal mode, and others in COREXY, so there are COREZA and COREBC features implemented. 
COREZA is a special type of kinematics with Z:A ratio 24:1. 
Wiring is illustrated bellow: 
![Pinout](https://github.com/ArctosRobotics/Arctos-grbl-v0.1/blob/edge/PINOUT.png)

