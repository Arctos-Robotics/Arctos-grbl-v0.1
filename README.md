**ARCTOS custom version**

This is a 6 axis version of grbl implemented in Arctos 3D printed robotic arm. Tested in open-loop mode without a gripper.
It runs on Arduino MEGA, other boards are not supported for now.  
Axes are named as X,Y,Z,A,B,C. First two axis runs in normal mode, and others in COREXY, so there are COREZA and COREBC features implemented. 
COREZA is compensating for the A motor position in v0.16.7. In v0.2 COREZA should be commented out

Use [this tutorial](https://arctosrobotics.com/2023/03/27/how-to-flash-the-arctos-grbl-firmware/) to flash the firmware. 
 
Wiring is illustrated bellow: 
![Pinout](https://github.com/ArctosRobotics/Arctos-grbl-v0.1/blob/edge/PINOUT.png)

